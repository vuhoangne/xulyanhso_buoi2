# Xử Lý Ảnh Số - Buổi 2

## Mô tả
Đây là bài tập xử lý ảnh số buổi 2, thực hiện các phép biến đổi ảnh cơ bản và nâng cao bằng Python với OpenCV, NumPy, Matplotlib.

## Nội dung
- **Bài 1:** Menu chọn các phép biến đổi ảnh cơ bản (Image Inverse, Gamma-Correction, Log Transformation, Histogram Equalization, Contrast Stretching).
- **Bài 2:** Menu chọn các phép biến đổi tần số (Fast Fourier Transform, Butterworth Lowpass Filter, Butterworth Highpass Filter).
- **Bài 3:** Đổi thứ tự màu RGB và ngẫu nhiên chọn phép biến đổi trong câu 1.
- **Bài 4:** Đổi thứ tự màu RGB và ngẫu nhiên chọn phép biến đổi trong câu 2. Nếu là Butterworth Lowpass thì thêm Min Filter, nếu Butterworth Highpass thì thêm Max Filter.

## Hướng dẫn sử dụng
1. **Cài đặt thư viện:**
   ```bash
   pip install opencv-python numpy matplotlib scipy
   ```
2. **Chuẩn bị dữ liệu:**
   - Tạo thư mục `exercise` trong cùng thư mục với notebook.
   - Thêm các ảnh cần xử lý vào thư mục `exercise`.
3. **Chạy notebook:**
   - Mở file `bai_tap_xla.ipynb` bằng Jupyter Notebook hoặc Jupyter Lab.
   - Chạy lần lượt từng cell, nhập lựa chọn khi được hỏi.
   - Kết quả sẽ hiển thị và được lưu vào các thư mục `output1`, `output2`, `output3`, `output4`.

## Cấu trúc thư mục
```
XLA_lab2/
├── bai_tap_xla.ipynb
├── README.md
├── exercise/           # Thư mục chứa ảnh gốc
├── output1/            # Ảnh kết quả bài 1
├── output2/            # Ảnh kết quả bài 2
├── output3/            # Ảnh kết quả bài 3
└── output4/            # Ảnh kết quả bài 4
```

## Liên hệ
- Họ tên: (Lê Nguyễn Vũ Hoàng)
- MSSV: (2174802010606)

---
Nếu có thắc mắc hoặc lỗi phát sinh, vui lòng liên hệ hoặc tạo issue trên GitHub.
