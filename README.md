# TPI Holding — Website Redesign 2025

One-page landing page cho Công ty Cổ phần TPI Holding — quản lý tài sản, đầu tư chứng khoán.

## Cấu trúc

```
tpiholding/
├── index.html        # Trang chính (one-page)
├── styles.css        # CSS (theme Navy + Gold)
├── script.js         # JS (animations, interactions)
├── vercel.json       # Cấu hình Vercel deploy
└── assets/
    ├── TPI-Holding-Logo3.png
    ├── TPI-Holding-Favicon1.png
    ├── Pham-Dac-Thanh-3.jpg
    ├── phi-vinh-quy.jpg
    ├── Duc-Linh.jpg
    └── tri-dao.jpg
```

## Deploy lên Vercel qua GitHub

1. **Push lên GitHub:**
   ```bash
   git init
   git add .
   git commit -m "feat: TPI Holding website redesign 2025"
   git branch -M main
   git remote add origin https://github.com/<username>/tpiholding.git
   git push -u origin main
   ```

2. **Connect Vercel:**
   - Vào [vercel.com](https://vercel.com) → New Project
   - Import GitHub repo `tpiholding`
   - Framework: **Other** (static HTML)
   - Root Directory: `.` (root)
   - Build Command: *(để trống)*
   - Output Directory: `.`
   - Deploy!

3. **Custom domain** (tuỳ chọn):
   - Vercel dashboard → Settings → Domains
   - Thêm `tpiholding.vn` → cấu hình DNS theo hướng dẫn

## Sections

| Section | ID | Mô tả |
|---|---|---|
| Hero | `#hero` | Banner chính, CTA, quote Buffett |
| Stats | — | 4 con số nổi bật |
| Về chúng tôi | `#about` | Giới thiệu mô hình hoạt động |
| Dịch vụ | `#services` | 3 dịch vụ chính |
| Lợi thế | `#why-us` | 6 lý do chọn TPI |
| Linh hoạt | `#flexibility` | 4 đặc điểm linh hoạt |
| Triết lý | `#philosophy` | Triết lý value investing |
| Quy trình | `#process` | 4 bước bắt đầu |
| Đội ngũ | `#team` | 4 thành viên |
| Liên hệ | `#contact` | Form + thông tin liên hệ |

## Tuỳ chỉnh

- **Màu sắc:** Sửa CSS variables trong `:root { }` (đầu file `styles.css`)
- **Nội dung:** Sửa trực tiếp `index.html`
- **Font:** Hiện dùng `Be Vietnam Pro` + `Playfair Display` (Google Fonts)
