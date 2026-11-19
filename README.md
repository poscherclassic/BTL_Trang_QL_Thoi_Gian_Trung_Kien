# Trang web quản lý thời gian và học tập

Website tĩnh bằng HTML5 và CSS3 giúp sinh viên xem thời khóa biểu, ghi chú lịch trình, theo dõi danh sách công việc và ghi chú theo ngày.

## Nội dung

- Thời khóa biểu theo các ngày trong tuần; ô môn học có thể chỉnh sửa trực tiếp.
- Khu vực nhập ghi chú lịch trình.
- Danh sách công việc gồm các ô checkbox và nội dung có thể chỉnh sửa.
- Chọn ngày và ghi chú sự kiện trong ngày.
- Liên kết đến GitHub và Facebook.
- Giao diện xanh lá, bố cục co giãn trên màn hình nhỏ và hỗ trợ giảm chuyển động.

## Công nghệ

- HTML5: cấu trúc nội dung và các điều khiển biểu mẫu.
- CSS3: bố cục, màu sắc, hiệu ứng, trạng thái tương tác và responsive.
- Không có JavaScript, backend, cơ sở dữ liệu hoặc thư viện ngoài.

## Chạy dự án

1. Tải hoặc clone repository.
2. Mở `index.html` bằng trình duyệt hiện đại.
3. Chỉnh sửa nội dung trực tiếp trên trang.

Có thể chạy bằng tiện ích Live Server trong VS Code để tự tải lại trang khi sửa file.

## Cấu trúc thư mục

```text
.
├── index.html
├── css/
│   └── style.css
├── assets/
│   └── anh_chan_dung.jpg
├── README.md
├── CHANGELOG.md
└── AI_LOG.md
```

## Giới hạn hiện tại

Các trường ghi chú, ngày và ô `contenteditable` chỉ thay đổi nội dung trong phiên trình duyệt hiện tại. Dự án chưa lưu dữ liệu vào `localStorage` hay máy chủ; tải lại trang có thể làm mất nội dung đã nhập. Giao diện hiện tập trung vào HTML và CSS, chưa có chức năng tự động hóa thao tác.

## Tài liệu dự án

- [Lịch sử thay đổi](CHANGELOG.md)
- [Nhật ký sử dụng AI](AI_LOG.md)

## Tác giả

Đồ án website quản lý thời gian và học tập của Trung Kiên.

