# MAISON LUXE – Web bán túi xách & giày dép cao cấp

Website e-commerce một trang (React 18 + Three.js), giao diện sáng/tối, hero 3D.

## Tính năng
- Hero 3D (túi xách, giày, ví), dải thương hiệu, ô danh mục nghiêng 3D
- Tìm kiếm, lọc danh mục, lọc theo giá, sắp xếp
- Chi tiết sản phẩm (màu, size), yêu thích, giỏ hàng, mã giảm giá `LUXE10`
- Đăng ký / đăng nhập, thanh toán, lịch sử đơn hàng, hủy đơn
- Footer đầy đủ

> Tài khoản và đơn hàng đang lưu trong `localStorage` của trình duyệt (bản demo, mật khẩu chưa mã hóa).
> Muốn chạy thật cần thêm backend và cơ sở dữ liệu.

## Chạy thử trên máy
Mở trực tiếp `index.html` bằng trình duyệt, hoặc:
```bash
npx serve .
```

## Đưa lên GitHub
```bash
git init
git add .
git commit -m "MAISON LUXE storefront"
git branch -M main
git remote add origin https://github.com/<ten-ban>/maison-luxe.git
git push -u origin main
```

## Deploy lên Vercel
1. Vào https://vercel.com, chọn **Add New → Project**, import repo GitHub vừa tạo.
2. Framework Preset: **Other**. Để trống Build Command và Output Directory.
3. Bấm **Deploy**. Vercel sẽ phục vụ `index.html` như một trang tĩnh.

Hoặc dùng CLI: `npx vercel --prod`
