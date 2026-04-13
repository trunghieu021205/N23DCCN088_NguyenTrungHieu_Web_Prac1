# N23DCCN088_Nguyễn Trung Hiếu - Web Practice 1

## Thông tin sinh viên
- **Họ và tên**: Nguyễn Trung Hiếu
- **Mã số sinh viên**: N23DCCN088
- **Lớp**: Nhóm 2 - Thực hành Lập trình Web
- **Bài tập**: Thực hành 1 - Xây dựng Blog Listing Page với Next.js & Tailwind CSS

## Mô tả bài làm

Bài thực hành này tập trung vào việc xây dựng một trang **Blog Listing** và **Blog Detail** sử dụng **Next.js (App Router)** kết hợp với **Tailwind CSS**.

### Các tính năng đã hoàn thành:

### Trang chính (Blog Listing - `/`)
- Khởi tạo dự án Next.js với App Router và Tailwind CSS
- Fetch danh sách bài viết từ API `JSONPlaceholder`
- Xây dựng component `Header` và `BlogCard` tái sử dụng
- Hiển thị danh sách bài viết dưới dạng responsive grid (1 cột trên mobile, 2 cột tablet, 3-4 cột desktop)
- Áp dụng hiệu ứng hover, `line-clamp` và transition mượt mà

### Trang chi tiết bài viết (`/blog/[id]`)
- Sử dụng Dynamic Route với `[id]`
- Fetch dữ liệu chi tiết của bài viết theo ID
- Giao diện đẹp, responsive trên mọi thiết bị
- Thiết kế hiện đại với gradient header, shadow card, typography tối ưu
- Nút "Back to Blog" có hiệu ứng hover

### Công nghệ sử dụng
- **Next.js 16** (App Router)
- **Tailwind CSS v4**
- **JavaScript**
- Fetch API (Server Component)

### Hướng dẫn chạy dự án

```bash
# Clone repository
git clone https://github.com/trunghieu021205/N23DCCN088_NguyenTrungHieu_Web_Prac1.git

# Vào thư mục dự án
cd N23DCCN088_NguyenTrungHieu_Web_Prac1

# Cài đặt dependencies
npm install

# Chạy dự án
npm run dev
