# ĐỜI NÀY CÓ GÌ VUI? — BIG UPDATE 3.0

Single-file mobile web game prototype following Visual Bible 1.0.

## Chốt đã tích hợp
- Portrait mobile, fixed UI, 4 bottom tabs: Nhà / Điện thoại / Đời sống / Thêm.
- Không còn tab Việc ở bottom; công việc nằm trong Điện thoại → Xin việc.
- Phòng trọ chỉ có nhân vật chính + một bong bóng thoại/narration, không có NPC đứng bên trái.
- 3 jobs: Phở / Văn phòng / Shipper.
- Travel riêng trước mỗi ca.
- Job state machine đơn giản: ACTION → PROGRESS → ACTION; có HỦY.
- Tiền chỉ cộng ở bước cuối.
- Phone là scene riêng. Social là scene riêng, tự chuyển 7 giây, nút duy nhất là ĐÓNG.
- Shop mở từ Nhà hoặc Phone.
- Life/personality/messages/schedule/wallet.
- LocalStorage key mới DNCSV_BIG_3 để không bị state/UI cũ của bản trước.
- Tất cả hình ảnh được nhúng Base64 trong index.html, không cần thư mục asset.

## Upload GitHub Pages
Chỉ cần upload đúng file `index.html` này vào thư mục đang được GitHub Pages publish. Không cần upload folder asset.
