# 🫀 Phân tích Bệnh Tim bằng Luật Kết hợp & Phân cụm

## 📌 Giới thiệu
Dự án này tập trung vào việc **phân tích dữ liệu bệnh tim** bằng các kỹ thuật **khai phá dữ liệu (Data Mining)**, cụ thể là:
- **Luật kết hợp (Association Rules)** với thuật toán **Apriori**
- **Phân cụm dữ liệu (Clustering)** với thuật toán **K-Means**

Mục tiêu là tìm ra:
- Các mối quan hệ tiềm ẩn giữa các thuộc tính bệnh nhân
- Các nhóm bệnh nhân có đặc điểm tương đồng

Dự án được thực hiện dưới dạng **Jupyter Notebook** phục vụ mục đích học tập và nghiên cứu.

---

## 📂 Nội dung chính
Notebook `BT_Buoi4.ipynb` bao gồm các phần:

### 1️⃣ Tải và tiền xử lý dữ liệu
- Đọc tập dữ liệu bệnh tim
- Làm sạch dữ liệu
- Chuẩn hóa và chuyển đổi dữ liệu phù hợp cho khai phá luật và phân cụm

---

### 2️⃣ Khai phá Luật Kết hợp (Apriori)
- Áp dụng thuật toán **Apriori**
- Thiết lập các tham số:
  - `min_support`
  - `min_confidence`
  - `lift`
- Phân tích các **luật kết hợp** có ý nghĩa trong dữ liệu bệnh tim

📌 *Mục tiêu:* Tìm các đặc điểm thường xuất hiện cùng nhau ở bệnh nhân mắc bệnh tim.

---

### 3️⃣ Phân cụm dữ liệu với K-Means
- Chuẩn hóa dữ liệu
- Xác định số cụm phù hợp (Elbow Method)
- Thực hiện phân cụm bằng **K-Means**
- Phân tích đặc điểm của từng cụm

📌 *Mục tiêu:* Nhóm các bệnh nhân có đặc điểm tương đồng để hỗ trợ phân tích và dự đoán.

---

## 🛠️ Công nghệ & Thư viện sử dụng
- **Python 3**
- **Jupyter Notebook**
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `mlxtend` (Apriori)
- `scikit-learn` (K-Means)

---

## ▶️ Cách chạy dự án
1. Clone repository:
   ```bash
   git clone <link-github-cua-ban>

