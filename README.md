# Web/app học tập — Hóa học 8, Bài 11

**Bài 11: Muối**
Môn Khoa học tự nhiên 8 (phân môn Hóa học) — Chương trình GDPT 2018, sách Kết nối tri thức với cuộc sống.

Giáo viên: Lê Văn Thắng — Trường TH và THCS Phước Hưng, xã Nhơn Hội, tỉnh An Giang.

## Nội dung

Web/app học tập 6 phần: Khởi động, Khám phá, Mô phỏng, Sơ đồ tư duy, Luyện tập (10 câu trắc nghiệm tự chấm), Vận dụng.

Mô phỏng gồm 4 thí nghiệm Hình 11.1 (SGK trang 50), mỗi mô phỏng có hình minh họa SVG thay đổi theo từng bước:
1. Ống (1): đinh sắt + dung dịch CuSO₄ (muối tác dụng với kim loại).
2. Ống (2): dung dịch BaCl₂ + dung dịch H₂SO₄ (muối tác dụng với acid).
3. Ống (3): dung dịch BaCl₂ + dung dịch Na₂SO₄ (muối tác dụng với muối).
4. Ống (4): dung dịch CuSO₄ + dung dịch NaOH (muối tác dụng với base).

Lưu ý: phương trình HNO₃ + Na₂CO₃ trong tài liệu gốc in thiếu hệ số 2 trước HNO₃ nên chưa cân bằng; bản web này đã sửa thành phương trình cân bằng 2HNO₃ + Na₂CO₃ → 2NaNO₃ + CO₂ + H₂O.

## Cách dùng

- Mở file `index.html` bằng trình duyệt bất kì (không cần máy chủ).
- Học sinh đăng nhập bằng Họ tên + Lớp, học 6 phần, làm 10 câu trắc nghiệm rồi nộp bài.
- Điểm trắc nghiệm hiện lưu trên máy học sinh. Sau khi gắn link Apps Script Web App (/exec), điểm sẽ tự động lưu về Google Sheets của giáo viên (đang chờ Google mở lại việc tạo dự án Apps Script).

## File trong repo

- `index.html` — web/app hoàn chỉnh, tự chứa (hình ảnh nhúng base64).
- `Web_Hoc_Tap_Hoa8_Bai11.md` — bản sao toàn bộ mã nguồn kèm khóa đáp án.
- `Code.gs` — mã Apps Script ghi điểm về Google Sheets (chờ deploy lấy link /exec).
- `assets-flow/` — 3 ảnh nền gốc (Gemini, 1376×768) + logo giáo viên.
