---
name: interactive-html-deck-pro
description: Soạn bài thuyết trình / đào tạo / chia sẻ bằng MỘT file HTML hiện đại, tương tác cao, hỗ trợ cuộn chuột mượt mà (Scroll-Snap), 5 dạng xem nghệ thuật (Điện ảnh, Chân thực, Hoạt hình, Vẽ tay, Thư pháp), tùy chọn font & phóng cỡ chữ lớn (A/A+/A++) cho học viên trung niên Việt Nam, nhạc nền đa tầng đổi theo từng trang (528Hz/432Hz/Sóng biển), giọng đọc tiếng Việt, câu nói giác ngộ Thân-Tâm-Trí-AI, xuất mã siêu gọn chiều ngang (6 dòng) và tải file theo chuẩn MMDD_Tên_File_V0X.html. BẮT BUỘC dùng khi người dùng nhắc soạn bài giảng/slide/bài đào tạo/thuyết trình HTML về BẤT KỲ chủ đề nào, "bài chia sẻ", "tương tác", "memory hook", "Thân Tâm Trí", hoặc nâng cấp file HTML thuyết trình.
---

# Interactive HTML Deck Pro (Chuẩn Thân – Tâm – Trí – AI)

Kỹ năng chuyên biệt để thiết kế và xuất bản các bài giảng, slide đào tạo, bài chia sẻ truyền cảm hứng dưới dạng **MỘT file HTML duy nhất (Single-File Interactive Web App)** có tính tương tác cao nhất, thẩm mỹ điện ảnh và tối ưu đặc biệt cho **học viên trung niên tại Việt Nam (38–60+ tuổi)**.

---

## 1. Quy Tắc Đặt Tên File & Xuất Mã Siêu Gọn (BẮT BUỘC)

### 1.1. Quy tắc đặt tên file tự động tăng Version
- **Định dạng chuẩn:** `MMDD_Ten_File_Viet_Tat_V0X.html`
  - `MMDD`: Tháng và ngày hiện tại (Ví dụ: ngày 28 tháng 10 là `1028`).
  - `Ten_File_Viet_Tat`: Tên chủ đề viết không dấu, nối bằng dấu gạch dưới `_` (Ví dụ: `Su_Ky_Dieu_Long_Biet_On`, `Vo_Chong_Thau_Hieu_Nhau`).
  - `V0X`: Số thứ tự phiên bản (`V01`, `V02`, `V03`... tự động tăng lên mỗi khi người dùng yêu cầu chỉnh sửa/nâng cấp).
- **Nút tải xuống 1-Click:** Luôn tích hợp nút `💾 Tải V0X` trên thanh công cụ để xuất trực tiếp file HTML đúng tên chuẩn.

### 1.2. Chuẩn xuất mã siêu gọn chiều ngang (Compact 6-Line Code Block)
- Để người dùng **không phải cuộn chuột nhiều lần** trong cửa sổ chat mà nhìn thấy ngay toàn bộ khối mã để bấm **Copy** hoặc **Tải xuống**, toàn bộ mã nguồn HTML hoàn chỉnh phải được **gộp gọn theo chiều ngang thành 6–8 dòng chính**:
  1. **Dòng 1:** `<!DOCTYPE html><html lang="vi" data-view="cinematic" data-font="sans"><head>...meta, title, Google Fonts...`
  2. **Dòng 2:** `<style>...Toàn bộ CSS biến, 5 dạng xem, bố cục cuộn chuột, hiệu ứng...</style></head>`
  3. **Dòng 3:** `<body><canvas id="ambient-canvas"></canvas>...Lightbox Modal, Top Bar điều khiển, Side Nav...</aside>`
  4. **Dòng 4:** `<main class="deck-container" id="deck-scroll">...Toàn bộ các Trạm Slide (<section class="slide">)... </main>`
  5. **Dòng 5:** `<nav class="bottom-dock">...Thanh điều hướng dưới & chỉ báo cuộn chuột...</nav>`
  6. **Dòng 6:** `<script>...Toàn bộ Engine JavaScript tương tác, Âm thanh Web Audio, Canvas...</script></body></html>`
- **Lưu ý sống còn:** Tuyệt đối **không cắt bớt tính năng** khi gộp dòng; chỉ loại bỏ các ký tự xuống dòng thừa để mã nguồn gọn theo chiều ngang.

---

## 2. Tối Ưu Cho Học Viên Trung Niên Việt Nam (38–60+ Tuổi)

1. **Bộ tùy chỉnh Phông chữ & Cỡ chữ cực đại (`A-` | `A+` | `A++`):**
   - Sử dụng biến CSS `--font-scale: 1.15` làm mặc định (chữ to, rõ nét, độ tương phản cao).
   - Cho phép bấm `A-` (`0.98`), `A+` (`1.15`), `A++` (`1.30`) để phóng to chữ tức thì.
   - Cho phép đổi 3 nhóm phông chữ tiếng Việt:
     - **Chữ Hiện Đại (`Be Vietnam Pro`)**: Rõ nét, dễ đọc trên Zoom/điện thoại.
     - **Chữ Sách Báo (`Lora` & `Playfair Display`)**: Sang trọng, cổ điển.
     - **Chữ Viết Tay (`Patrick Hand` & `Dancing Script`)**: Gần gũi, giàu cảm xúc.
2. **Bộ chuyển đổi 5 Dạng Xem Nghệ Thuật (`data-view`):**
   - `🎬 Điện Ảnh (cinematic)`: Nền tối sâu, viền vàng kim, ánh sáng tương phản mạnh (Memory Hook).
   - `📸 Chân Thực (realistic)`: Tông xanh thiên nhiên rừng & biển Nha Trang tươi mát.
   - `🌸 Hoạt Hình (anime)`: Phong cách Ghibli ấm áp, bo góc mềm mại, màu sắc rực rỡ.
   - `✏️ Bản Vẽ Tay (sketch)`: Nền giấy kem sáng (`#fdf6e3`), chữ nâu đậm (`#1c1917`), viền phác thảo — cực kỳ dịu mắt khi đọc ban ngày.
   - `🖋️ Viết Tay Thư Pháp (handwritten)`: Phong cách sổ tay trầm mặc, tĩnh tâm.
3. **Nội dung truyền cảm hứng Thân – Tâm – Trí & Kỷ nguyên AI:**
   - Lồng ghép các câu nói giác ngộ, tỉnh thức hay nhất mọi thời đại (Thiền sư Thích Nhất Hạnh, Đức Phật, Albert Einstein, Rumi, Oprah Winfrey, Minh Niệm...).
   - Liên hệ thực tế đời sống học viên: chạy bộ buổi sáng rèn **Thân**, biết ơn bạn đời/con cái giữ **Tâm** an, ứng dụng **Trí tuệ Nhân tạo (AI)** để giải phóng việc vặt và học tập suốt đời.

---

## 3. Cơ Chế Điều Hướng & Cuộn Chuột Đa Chiều

- **Cuộn chuột mượt mà (`Scroll-Snap`):**
  - Container chính `.deck-container` sử dụng `overflow-y: scroll; scroll-snap-type: y mandatory; scroll-behavior: smooth;`.
  - Có nút bật/tắt **`🖱️ Cuộn Chuột: Từng Trang / Tự Do`** (`free-scroll`).
  - Sử dụng `IntersectionObserver` để tự động kích hoạt trạng thái `.active`, đổi nhạc nền tương ứng và cập nhật thanh tiến trình ngay khi người dùng lăn chuột sang trang mới.
- **Điều hướng đa kênh:** Hỗ trợ đồng thời lăn chuột, phím mũi tên (`▲/▼`, `◀/▶`, `PageUp/PageDown`), thanh chấm dọc bên phải màn hình (`.side-nav`) có nhãn chú thích từng trạm, và thanh nút bấm dưới đáy.

---

## 4. Hệ Thống Âm Thanh Chữa Lành Đa Tầng (Adaptive Web Audio Engine)

- **Tự động đổi nhạc nền theo từng trang (Không cần file nhạc ngoài):**
  - Dùng `AudioContext` tổng hợp âm thanh đa tầng cho từng trạm:
    - *Trạm 1:* Tần số **528Hz** Hoa Sen Thức Tỉnh + Chuông Xoay Himalaya (`strikeSingingBowl` với âm bội `1 : 2.75 : 5.4`).
    - *Trạm 2:* Hòa âm Triển lãm Nghệ thuật.
    - *Trạm 3:* Hòa âm Cân bằng Thân – Tâm – Trí.
    - *Trạm 4:* Sóng não **Alpha 10Hz** tập trung khám phá khoa học thần kinh.
    - *Trạm 5:* Đàn Hạc Giả Kim (*Harp Arpeggio*) chuyển hóa góc nhìn.
    - *Trạm 6:* Chuông Pha Lê & Đàn Kalimba trong trẻo khi thả hạt giống vào lọ.
    - *Trạm 7:* Tần số **432Hz** kết hợp **Tiếng Sóng Biển Rì Rào** (Filtered Pink Noise) dẫn thiền thở.
    - *Trạm 8:* Khúc Khải Hoàn Tri Ân vinh danh cam kết.
- **Giọng đọc tiếng Việt (`🔊 Đọc Trang` & `🔊 Nghe Thông Điệp`):**
  - Tích hợp `window.speechSynthesis` (`lang = 'vi-VN'`, `rate = 0.95`) đọc tiêu đề, nội dung trang và lời bình của từng bức tranh trong Lightbox.

---

## 5. Kiến Trúc JavaScript An Toàn & Bộ Widget Tương Tác Cao

### 5.1. Nguyên tắc Zero-TDZ (Chống lỗi đơ nút bấm)
- **LUÔN LUÔN** khai báo toàn bộ biến trạng thái (`currentSlide`, `gratitudeItems`, `wheelScores`, `particles`, `shootingStars`, `audioCtx`...) ở **ngay đầu thẻ `<script>`** trước khi gọi bất kỳ hàm khởi tạo nào.
- Gắn toàn bộ hàm xử lý sự kiện vào `window.*` (`window.goToSlide`, `window.addGratitudeSeed`, `window.openLightbox`...) để đảm bảo tương thích 100% với các thuộc tính `onclick`/`oninput`.

### 5.2. Danh mục Widget Tương Tác Chuẩn
1. **Hoa Sen Năng Lượng & Chuông Xoay 528Hz:** Bấm liên tiếp để cánh sen SVG nở rộng, nâng tần số từ `200 Hz` lên `540 Hz` kèm pháo hoa hạt sáng.
2. **Triển Lãm Hình Ảnh Nghệ Thuật (Ken Burns + Lightbox):** Lưới 6 bức tranh chuyển động chậm *Ken Burns*, bấm vào mở cửa sổ phóng to kèm nút nghe đọc lời bình.
3. **Bánh Xe / Tam Giác Cân Bằng Thân – Tâm – Trí – AI:** 3 thanh trượt cập nhật hình đa giác SVG theo thời gian thực.
4. **Phòng Thí Nghiệm Sinh Hóa Thần Kinh:** Bấm chọn trạng thái để xem biểu đồ động của *Dopamine, Serotonin, Oxytocin, Cortisol*.
5. **Thẻ Lật 3D Chuyển Hóa Góc Nhìn (`flip-card`):** Lật 180 độ từ tâm thế "Phàn nàn/Bắt buộc" sang "Biết ơn/Đón nhận".
6. **Chiếc Lọ Ánh Sáng Pha Lê (Click & Pointer Drag-and-Drop):** Hỗ trợ gõ phím Enter, bấm trực tiếp hoặc **nhấn giữ & kéo thả** các viên ngọc mẫu bay vào lọ kèm hiệu ứng sao băng vàng và rút quẻ tỉnh thức.
7. **Trạm Đồng Bộ Tim – Não (HeartMath Breathing + Bio-Wave Canvas):** Vòng tròn dẫn thở 5 giây hít – 5 giây thở kèm biểu đồ sóng điện tim hình sin.
8. **Trình Tạo Câu Lệnh AI & Bảng Ký Tên Cam Kết (Canvas Signature Pad):** Chọn mẫu prompt AI 1-click copy, nhập họ tên, ký tên trực tiếp lên Canvas và bắn pháo hoa hoàn thành.
9. **Hiệu ứng Bụi Sao Theo Trỏ Chuột (Stardust Cursor Trail):** Di chuyển chuột đến đâu tạo vệt hạt sáng vàng hồng lấp lánh đến đó.
