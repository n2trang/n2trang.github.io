# Hướng dẫn đăng trang web lên mạng (miễn phí)

Trang web của bạn đã sẵn sàng. Theo các bước dưới đây để có một địa chỉ web kiểu `https://[tên-của-bạn].github.io` — **hoàn toàn miễn phí, không giới hạn thời gian**.

---

## Bước 1 — Tạo tài khoản GitHub (3 phút)

1. Vào https://github.com/signup
2. Email → mật khẩu → username (chọn cái bạn muốn dùng làm địa chỉ web, ví dụ `nguyenngoctrang` → website sẽ là `nguyenngoctrang.github.io`)
3. Xác nhận email

**Lưu ý:** username sẽ trở thành phần đầu của URL. Đặt sao cho chuyên nghiệp.

---

## Bước 2 — Tạo "kho chứa" (repository) cho website (2 phút)

1. Sau khi đăng nhập, bấm nút **+** góc trên phải → **New repository**
2. **Repository name:** gõ chính xác `[username-của-bạn].github.io`
   - Ví dụ username là `nguyenngoctrang` → tên repo phải là `nguyenngoctrang.github.io`
   - Cú pháp này GitHub bắt buộc, sai thì không hoạt động
3. Chọn **Public** (bắt buộc để dùng tính năng Pages miễn phí)
4. **KHÔNG** tích "Add a README file"
5. Bấm **Create repository**

---

## Bước 3 — Tải file website lên (5 phút)

1. Trên trang repo vừa tạo, bạn sẽ thấy dòng "**Quick setup**" — bỏ qua nó
2. Bấm vào link **"uploading an existing file"** (gần cuối trang)
3. Mở folder `nguyenngoctrang_website` trên máy bạn — chọn **TẤT CẢ** file/folder bên trong (gồm `index.html` và folder `images`), kéo vào ô upload
4. Cuộn xuống, bấm **Commit changes**
5. Đợi khoảng 30 giây để GitHub xử lý

---

## Bước 4 — Bật GitHub Pages (1 phút)

1. Trong repo, bấm tab **Settings** (góc trên phải repo)
2. Cuộn menu trái xuống, bấm **Pages**
3. Mục "Source": chọn **Deploy from a branch**
4. Mục "Branch": chọn `main` → folder `/ (root)` → bấm **Save**
5. Đợi 1-2 phút

---

## Bước 5 — Truy cập trang web của bạn

Mở trình duyệt, gõ:

```
https://[username-của-bạn].github.io
```

Ví dụ: `https://nguyenngoctrang.github.io`

🎉 **Xong rồi!** Trang web đã online, ai cũng truy cập được, miễn phí, vĩnh viễn.

---

## Cập nhật nội dung sau này

Khi cần sửa nội dung (đổi số điện thoại, thêm kinh nghiệm, đổi ảnh...):

1. Vào repo trên GitHub → bấm file `index.html` → bấm icon bút chì (Edit)
2. Sửa nội dung → cuộn xuống bấm **Commit changes**
3. Website sẽ tự động cập nhật trong 1-2 phút

Hoặc nhờ tôi sửa giúp, gửi lại file mới, bạn chỉ cần xoá file cũ trên repo và upload file mới.

---

## Nâng cấp lên domain riêng (tuỳ chọn — ~250.000đ/năm)

Sau này nếu muốn địa chỉ kiểu `nguyenngoctrang.com` thay vì `nguyenngoctrang.github.io`:

1. Mua domain ở **Namecheap** (~10 USD/năm) hoặc **Cloudflare** (~10 USD/năm, rẻ nhất)
2. Trong **Settings → Pages → Custom domain**, nhập domain
3. Trong trang quản lý domain, thêm CNAME record trỏ về `[username].github.io`

Tôi có thể hướng dẫn chi tiết khi bạn quyết định.

---

## File trong gói này

```
nguyenngoctrang_website/
├── index.html         ← trang web (mở thử bằng Chrome trên máy)
├── images/
│   └── profile.jpg    ← ảnh chân dung
└── HUONG_DAN.md       ← file này
```

Bạn có thể mở `index.html` bằng cách nhấp đúp — Chrome/Edge sẽ mở luôn trang web ở chế độ xem trước, không cần internet.

---

## Vài lưu ý

- **Song ngữ:** Trang có nút **VI/EN** ở góc trên phải, click để chuyển ngôn ngữ.
- **Mobile:** Trang hoạt động tốt trên điện thoại — bạn thử mở trên iPhone/Android xem.
- **SEO:** Khi gõ tên bạn lên Google, có thể mất 1-2 tuần để Google index trang. Bạn có thể chủ động khai báo tại https://search.google.com/search-console
