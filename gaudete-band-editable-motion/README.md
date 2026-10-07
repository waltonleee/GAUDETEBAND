# Gaudete Band – Editable HTML Layout

Bản này đã dựng lại bằng HTML/CSS thật, không dùng nguyên từng slide tham chiếu làm một tấm ảnh.

## Có thể thao tác trực tiếp
- Toàn bộ chữ là text HTML: bôi đen/copy được.
- Ảnh thành viên và ảnh sân khấu là file ảnh riêng trong `assets/`: có thể right-click / Save image as / thay ảnh riêng.
- Các hình trang trí chính được dựng bằng CSS.
- Responsive cho desktop và mobile.

## Cấu trúc
- `index.html`
- `assets/` – ảnh riêng của từng thành viên / sân khấu

## GitHub Pages
Upload `index.html` và toàn bộ thư mục `assets` vào root repository.

Settings → Pages → Deploy from a branch → `main` → `/ (root)`.

## Video Demo
Ở cuối `index.html`, tìm:
`const videoUrl = '';`
và điền link YouTube / Vimeo / Google Drive.

## Thay ảnh
Giữ nguyên tên file trong `assets` là nhanh nhất. Chỉ cần chép ảnh mới đè lên file cũ.


## Motion khi cuộn trang
Bản này đã thêm motion nhẹ bằng CSS + JavaScript thuần:
- fade-up cho heading và text;
- stagger rất nhẹ cho member cards / USP / gallery;
- ảnh profile reveal bằng fade + zoom nhỏ;
- parallax rất nhẹ trên desktop;
- hero entrance cinematic nhẹ;
- hover card và button;
- tự tắt gần như toàn bộ animation nếu thiết bị bật `prefers-reduced-motion`.

Không dùng thư viện ngoài nên vẫn phù hợp GitHub Pages.
