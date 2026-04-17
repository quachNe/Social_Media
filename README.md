# 📱 Ứng Dụng Mạng Xã Hội

Một nền tảng mạng xã hội hiện đại và tương tác được xây dựng bằng **React** và **Vite**, với các tính năng cập nhật theo thời gian thực, xác thực người dùng và các chức năng xã hội như bài đăng, nhắn tin và quản lý bạn bè.

## ✨ Tính Năng

- **Xác Thực Người Dùng** - Hệ thống đăng nhập và đăng ký an toàn
- **Hồ Sơ Cá Nhân** - Tùy chỉnh hồ sơ với ảnh đại diện và thông tin
- **Bảng Tin & Bài Đăng** - Tạo, chia sẻ và tương tác với bài đăng
- **Quản Lý Bạn Bè** - Thêm/xóa bạn bè và xem danh sách bạn
- **Trò Chuyện Thời Gian Thực** - Nhắn tin trực tiếp giữa các người dùng
- **Thông Báo** - Nhận thông báo về lời mời kết bạn và tin nhắn
- **Tìm Kiếm** - Tìm kiếm và khám phá người dùng khác
- **Thiết Kế Đáp Ứng** - Tối ưu hóa cho tất cả các kích thước màn hình

## 🛠️ Công Nghệ Sử Dụng

- **Frontend Framework:** React 19.1.1
- **Build Tool:** Vite 7.1.2
- **Routing:** React Router DOM 7.9.1
- **Thư Viện Giao Diện:** Material-UI (MUI)
- **Quản Lý Trạng Thái:** React Context API
- **Styling:** CSS3 + Emotion (CSS-in-JS)
- **Kiểm Tra Chất Lượng:** ESLint

## 📦 Cài Đặt

### Yêu Cầu
- Node.js (phiên bản 16 trở lên)
- npm hoặc yarn

### Các Bước Cài Đặt

1. **Clone kho lưu trữ**
   ```bash
   git clone <repository-url>
   cd Social_Media
   ```

2. **Cài đặt các phụ thuộc**
   ```bash
   npm install
   ```

3. **Khởi động máy chủ phát triển**
   ```bash
   npm run dev
   ```
   Ứng dụng sẽ có sẵn tại `http://localhost:5173`

## 📝 Các Lệnh Sẵn Có

| Lệnh | Mô Tả |
|------|-------|
| `npm run dev` | Khởi động máy chủ phát triển với HMR |
| `npm run build` | Xây dựng dự án cho sản xuất |
| `npm run preview` | Xem trước bản dựng sản xuất cục bộ |
| `npm run lint` | Chạy ESLint kiểm tra chất lượng mã |

## 📁 Cấu Trúc Dự Án

```
src/
├── Pages/                  # Các component trang chính
│   ├── Home/              # Trang Trang Chủ/Bảng Tin
│   ├── Login/             # Trang Đăng Nhập
│   ├── Register/          # Trang Đăng Ký
│   ├── Profile/           # Trang Hồ Sơ Người Dùng
│   ├── FriendVisit/       # Xem Hồ Sơ Bạn Bè
│   ├── ChangePassWord/    # Trang Đổi Mật Khẩu
│   └── Research/          # Trang Tìm Kiếm/Khám Phá
│
├── Components/            # Các component giao diện tái sử dụng
│   ├── Feed/              # Component Bảng Tin
│   ├── Post/              # Component Bài Đăng
│   ├── Share/             # Component Tạo Bài Đăng
│   ├── Topbar/            # Thanh Điều Hướng Trên Cùng
│   ├── Sidebar/           # Thanh Điều Hướng Bên Trái
│   ├── Rightbar/          # Thanh Bên Phải
│   ├── ChatWindown/       # Giao Diện Trò Chuyện
│   ├── MiniChat/          # Widget Trò Chuyện Nhỏ
│   ├── Notification/      # Trung Tâm Thông Báo
│   ├── ListFriend/        # Danh Sách Bạn Bè
│   ├── Online/            # Người Dùng Trực Tuyến
│   ├── Ads/               # Component Quảng Cáo
│   └── context/           # Context API (Auth)
│
├── App.jsx                # Component Ứng Dụng Chính
├── Data.js                # Dữ Liệu Giả Lập
└── index.css              # Kiểu Toàn Cục
```

## 🔐 Xác Thực

Ứng dụng sử dụng **React Context API** để quản lý trạng thái và xác thực. Các tuyến đường được bảo vệ đảm bảo chỉ người dùng đã xác thực mới có thể truy cập các trang nhất định.

- Đăng nhập chuyển hướng người dùng chưa xác thực
- Quản lý phiên qua AuthContext
- Chức năng đăng xuất có sẵn trong ứng dụng

## 🎨 Định Dạng Tùy Chỉnh

- **CSS Modules** cho các kiểu riêng của component
- **Material-UI** cho các component được xây dựng sẵn
- **Emotion** cho định dạng CSS-in-JS nâng cao
- Thiết kế đáp ứng với phương pháp mobile-first

## 🚀 Phát Triển

### Hot Module Replacement (HMR)
- Các thay đổi được phản ánh ngay lập tức trong quá trình phát triển
- Không cần làm mới trang

### Cấu Hình ESLint
- Kiểm tra chất lượng mã tự động
- Chạy `npm run lint` để xác định các vấn đề

## 📱 Hỗ Trợ Trình Duyệt

- Chrome (mới nhất)
- Firefox (mới nhất)
- Safari (mới nhất)
- Edge (mới nhất)

## 🤝 Đóng Góp

Chúng tôi hoan nghênh những đóng góp! Vui lòng tuân theo các bước sau:

1. Tạo nhánh tính năng (`git checkout -b feature/TinhNangTuyetVoi`)
2. Cam kết các thay đổi của bạn (`git commit -m 'Thêm TinhNangTuyetVoi'`)
3. Đẩy đến nhánh (`git push origin feature/TinhNangTuyetVoi`)
4. Mở Yêu Cầu Kéo

## 📄 Giấy Phép

Dự án này là mã nguồn mở và có sẵn theo Giấy Phép MIT.

## 📞 Hỗ Trợ

Nếu có bất kỳ câu hỏi hoặc vấn đề nào, vui lòng tạo một vấn đề trong kho lưu trữ hoặc liên hệ với những người duy trì.

---

**Hạnh Phúc Lập Trình! 🎉**
