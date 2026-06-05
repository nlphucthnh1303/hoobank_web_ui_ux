# HooBank - Modern UI/UX Website

Trang landing page HooBank demo giao diện ngân hàng số, xây dựng bằng React và Tailwind CSS với Vite. Dự án tập trung vào thiết kế hiện đại, responsive và cấu trúc component rõ ràng để dễ mở rộng.

---

## ✨ Mục tiêu dự án

- Xây dựng một landing page fintech với layout clean và gradient hiện đại.
- Triển khai frontend React với Tailwind CSS, tối ưu cho mobile và desktop.
- Tổ chức component tái sử dụng cho Navbar, Hero, Stats, Business, Billing, Testimonials, Clients và CTA.
- Cung cấp mẫu UI rõ ràng để mở rộng thành dashboard hoặc trang marketing.

---

## 📚 Tính năng chính

- Navbar responsive với menu điều hướng.
- Hero section thu hút với nội dung chính và CTA.
- Section hiển thị các chỉ số (stats) và lợi ích dịch vụ.
- Các cards Business, Billing và Card Deal.
- Phần đánh giá khách hàng và logo đối tác.
- Footer đơn giản với liên kết, thông tin bản quyền.

---

## 🛠️ Tech Stack

- **Frontend:** React
- **Bundler:** Vite
- **CSS:** Tailwind CSS
- **Build:** npm
- **Language:** JavaScript (ESM)
- **Tooling:** PostCSS, Autoprefixer

---

## 🏗️ Cấu trúc dự án (tóm tắt)

```
.
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── constants/
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
│   └── style.js
├── index.html
├── package.json
├── postcss.config.cjs
├── tailwind.config.cjs
└── README.md
```

Tham khảo các file chính: `src/App.jsx`, `src/main.jsx`, `src/constants/index.js`, `tailwind.config.cjs`.

---

## 🚀 Chạy dự án (Development)

### Yêu cầu

- Node.js 18+ và `npm` hoặc `yarn`.

### Các bước nhanh

```bash
# Clone repo
git clone <repo-url>
cd <repo>

# Cài đặt dependencies
npm install

# Chạy ứng dụng
npm run dev
```

Nếu dùng yarn:

```bash
yarn install
yarn dev
```

---

## ⚙️ Biến môi trường

Dự án này là frontend tĩnh nên không cần cấu hình biến môi trường mặc định. Nếu mở rộng thêm API hoặc dịch vụ bên ngoài, bạn có thể thêm file `.env` ở thư mục gốc.

---

## 🧩 Các lệnh hữu ích

```bash
npm install
npm run dev
npm run build
npm run preview
```

---

## 🧭 Hướng dẫn phát triển nhanh

- Thêm component mới: tạo file trong `src/components/`.
- Cập nhật dữ liệu hiển thị: sửa `src/constants/index.js`.
- Điều chỉnh layout/chung: dùng `src/style.js` và `src/index.css`.
- Mở rộng pages hoặc sections: chỉnh `src/App.jsx` để thêm component mới.

---

## 🤝 Đóng góp

- Fork repo → tạo branch mới → commit → push → gửi pull request.
- Giữ code sạch và comment rõ ràng khi thêm component.
- Kiểm tra responsive trên mobile và desktop trước khi merge.

---

## 📄 License

Kiểm tra file `LICENSE` trong repo hoặc thêm giấy phép phù hợp (ví dụ MIT).

---

Nếu bạn muốn, tôi có thể:

- Dịch sang tiếng Anh.
- Mở rộng phần hướng dẫn deploy.
- Thêm badge, logo hoặc ví dụ ảnh màn hình.
