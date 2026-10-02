# 🥧 TozPie Code — AI Coding Assistant Desktop

[![Official Website](https://img.shields.io/badge/Website-tozpie.net-6366F1?style=for-the-badge&logo=google-chrome&logoColor=white)](https://tozpie.net)
[![GitHub Release](https://img.shields.io/github/v/release/tozpie/tozpie?style=for-the-badge&color=0EA5E9)](https://github.com/tozpie/tozpie/releases/latest)
[![Windows](https://img.shields.io/badge/Platform-Windows%20x64-10B981?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/tozpie/tozpie/releases/latest)
[![macOS](https://img.shields.io/badge/Platform-macOS%20(Apple%20Silicon%20%2F%20Intel)-000000?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/tozpie/tozpie/releases/latest)
[![Auto Update](https://img.shields.io/badge/Auto--Update-Supported-F59E0B?style=for-the-badge&logo=sparkles&logoColor=white)](https://github.com/tozpie/tozpie/releases/latest)

> **TozPie Code** là ứng dụng trợ lý lập trình AI thế hệ mới trên Desktop, tích hợp Agent tự động hóa, Multi-LLM Gateway và giao diện tối ưu hóa cho lập trình viên hiện đại.
>
> 🌐 Trang chủ chính thức: **[https://tozpie.net](https://tozpie.net)**

---

## 📥 Tải về & Cài đặt

Tải phiên bản mới nhất tại mục **[Releases](https://github.com/tozpie/tozpie/releases/latest)**:

### 🪟 Windows (64-bit)
| Loại cài đặt | Định dạng | Tải về |
| :--- | :--- | :--- |
| **Bản cài đặt tiêu chuẩn (Khuyên dùng)** | `.exe` (NSIS Installer) | [📥 Tải TozPie Code Setup (.exe)](https://github.com/tozpie/tozpie/releases/latest) |
| **Bản Portable (Chạy ngay không cần cài)** | `.exe` (Standalone) | [📦 Tải TozPie Code Portable (.exe)](https://github.com/tozpie/tozpie/releases/latest) |

### 🍎 macOS (Apple Silicon & Intel)
| Loại chip | Định dạng | Tải về |
| :--- | :--- | :--- |
| **Apple Silicon (M1 / M2 / M3 / M4)** | `.dmg` / `.zip` | [📥 Tải TozPie Code cho Apple Silicon (arm64)](https://github.com/tozpie/tozpie/releases/latest) |
| **Intel Mac** | `.dmg` / `.zip` | [📥 Tải TozPie Code cho Intel Mac (x64)](https://github.com/tozpie/tozpie/releases/latest) |

---

## ✨ Tính năng nổi bật

### 🤖 1. Autonomous AI Coding Agent
- Tự động phân tích cấu trúc Workspace, định vị tệp tin liên quan.
- Tự động đọc code, tạo file mới, chỉnh sửa file nhiều vị trí an toàn.
- Thực thi lệnh terminal và tự sửa lỗi theo vòng lặp thông minh.
- Quản lý ngân sách ngữ cảnh (Context Budget) tối ưu lên đến hàng trăm nghìn tokens mà không bị tràn bộ nhớ.

### 🌐 2. Multi-Provider AI Gateway
- Hỗ trợ kết nối đa nền tảng: **OpenRouter**, **OpenAI** (GPT-4o, o3-mini), **Anthropic** (Claude 3.7 Sonnet, 3.5 Sonnet), **Google** (Gemini 2.5 Pro / Flash), **DeepSeek**, **Ollama Local** và các máy chủ tùy chỉnh (Custom Base URL).
- Chuyển đổi linh hoạt giữa các mô hình AI trực tiếp từ giao diện chat.

### 🔄 3. Cơ chế Cập nhật Tự động (Seamless Auto-Update)
- Tự động kiểm tra bản cập nhật mới nhất trong nền từ repo `tozpie/tozpie`.
- Tải về vi sai (differential download) siêu nhanh với file `.blockmap`.
- Khởi động lại áp dụng bản mới chỉ với 1 click mà không cần cài đặt lại thủ công.

### 🛡️ 4. Kiểm soát Quyền & Bảo mật (Permission Dock)
- Thanh cấp quyền trực quan: Cho phép bạn kiểm soát từng thao tác đọc/ghi file hoặc chạy lệnh terminal của AI.
- Chế độ **Pure Chat** (hỏi đáp thuần túy) và chế độ **Auto Agent** (tự động hóa) linh hoạt.

### ⚡ 5. Command Palette & Chuyển đổi Dự án Nhanh
- Nhấn `Ctrl + K` hoặc bấm tìm kiếm để tra cứu nhanh toàn bộ lịch sử trò chuyện.
- Tự động chuyển đổi workspace sang đúng thư mục của dự án đó khi mở đoạn chat.

### 🌍 6. Đa ngôn ngữ hoàn chỉnh
- Hỗ trợ 100% tiếng Việt và tiếng Anh chuẩn bản địa, dễ dàng chuyển đổi trong Cài đặt.

---

## 🚀 Hướng dẫn Bắt đầu Nhanh

1. **Cài đặt ứng dụng**: Tải và mở file `TozPie Code Setup x.x.x.exe`.
2. **Mở thư mục dự án**: Bấm **Mở thư mục (Open Workspace)** và chọn source code của bạn.
3. **Cấu hình API Key**:
   - Vào mục **Cài đặt ➔ Cổng kết nối AI (AI Gateway)**.
   - Điền API Key của nhà cung cấp bạn muốn (OpenRouter, Gemini, OpenAI, Claude,...).
4. **Bắt đầu lập trình**: Nhập câu hỏi, mô tả tính năng cần thêm hoặc kéo thả ảnh/tài liệu vào khung chat để AI hỗ trợ ngay!

---

## 💻 Yêu cầu hệ thống

- **Hệ điều hành**: Windows 10 / Windows 11 (64-bit).
- **RAM**: Tối thiểu 4GB (Khuyến nghị 8GB+).
- **Dung lượng trống**: 500MB.

---

## 🔄 Cách cập nhật ứng dụng

1. Khi có phiên bản mới, **TozPie Code** sẽ tự động thông báo và tải về trong nền.
2. Bạn chỉ cần nhấn **Khởi động lại ngay** khi có thông báo tải xong.
3. Hoặc vào mục **Cài đặt ➔ Thông tin ứng dụng ➔ Kiểm tra bản cập nhật** bất cứ lúc nào.

---

## 📬 Liên hệ & Đóng góp

- 🌐 Website: [https://tozpie.net](https://tozpie.net)
- 🐛 Báo lỗi & Góp ý: [GitHub Issues](https://github.com/tozpie/tozpie/issues)
- 💬 Thảo luận cộng đồng: [GitHub Discussions](https://github.com/tozpie/tozpie/discussions)

---

<div align="center">
  <sub>Phát triển và vận hành bởi đội ngũ <b>TozPie</b> • © 2026 TozPie. All rights reserved.</sub>
</div>
