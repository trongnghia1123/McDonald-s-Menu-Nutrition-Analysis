# 🍔 McDonald’s Menu Nutrition Analysis – Power BI Project

## 📌 Giới thiệu

Dự án này tập trung vào **phân tích dữ liệu dinh dưỡng của các món ăn trong menu McDonald’s** dựa trên bộ dữ liệu `menu.csv`.  
Mục tiêu là xác định **các chỉ số dinh dưỡng quan trọng** (đặc biệt là calo và chất béo), từ đó **đánh giá mức độ “healthy” của món ăn** và **đề xuất lựa chọn phù hợp cho ba bữa: sáng, trưa và chiều**.

Toàn bộ quá trình phân tích và trực quan hóa được thực hiện bằng **Power BI**.

---

## 🎯 Mục tiêu phân tích

- Xác định các **chỉ số dinh dưỡng quan trọng** cần xem xét khi lựa chọn món ăn
- Phân tích và so sánh:
  - Lượng **calo**
  - Các **loại chất béo** (Total Fat, Saturated Fat, Trans Fat)
  - Các thành phần liên quan khác (protein, carbohydrate, sodium, sugar)
- So sánh mức độ dinh dưỡng giữa các nhóm món ăn
- Đề xuất **các lựa chọn món ăn tương đối healthy** cho:
  - Bữa sáng
  - Bữa trưa
  - Bữa chiều / tối

---

## 🗂 Dữ liệu sử dụng

### 📄 menu.csv
Bộ dữ liệu chứa thông tin dinh dưỡng của các món ăn trong menu McDonald’s.

**Một số cột chính:**
- `Item`: Tên món ăn
- `Calories`: Tổng lượng calo
- `Total Fat`: Tổng chất béo
- `Saturated Fat`: Chất béo bão hòa
- `Trans Fat`: Chất béo chuyển hóa
- `Protein`
- `Carbohydrates`
- `Sugars`
- `Sodium`
- `Category`: Nhóm món ăn

📌 Dữ liệu được sử dụng để phân tích, không chỉnh sửa nội dung gốc.

---

## 🛠 Công cụ và công nghệ

- **Power BI**
  - Power Query: làm sạch và xử lý dữ liệu
  - DAX: tạo các chỉ số và measure phục vụ phân tích
- **CSV**: nguồn dữ liệu đầu vào

---

## 📊 Nội dung phân tích chính

- Kiểm tra và làm sạch dữ liệu (missing values, kiểu dữ liệu)
- Phân tích phân bố **calo và chất béo** theo từng nhóm món ăn
- So sánh các loại chất béo:
  - Total Fat
  - Saturated Fat
  - Trans Fat
- Xác định các món:
  - Ít calo
  - Ít chất béo bão hòa
  - Có mức protein tương đối cao
- Phân tích và đề xuất **menu healthy cho từng bữa trong ngày**

---

## 🥗 Gợi ý menu healthy

Dựa trên các tiêu chí:
- Calo ở mức vừa phải
- Hạn chế chất béo bão hòa và trans fat
- Ưu tiên món có protein cao hơn

Dashboard Power BI đưa ra **gợi ý món ăn phù hợp cho:**
- Bữa sáng
- Bữa trưa
- Bữa chiều / tối

📌 Các gợi ý mang tính **tham khảo dựa trên dữ liệu**, không thay thế tư vấn dinh dưỡng chuyên môn.

---

## 📁 Cấu trúc thư mục

```text
mcdonald-menu-nutrition/
│
├── Mcdonald menu.pbix   # File Power BI dashboard
├── menu.csv             # Dữ liệu dinh dưỡng menu
└── README.md            # Mô tả dự án
