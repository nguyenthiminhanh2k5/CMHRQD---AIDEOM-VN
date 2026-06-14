# 🇻🇳 AIDEOM-VN

## Artificial Intelligence Driven Economic Optimization Model for Vietnam

> **Mô hình ra quyết định phát triển kinh tế Việt Nam trong kỷ nguyên AI**
> Integrated AI – Digital Economy – Optimization Framework for Policy Simulation (2026–2030)

---

## 📌 Overview

**AIDEOM-VN** là một hệ thống mô hình phân tích và hỗ trợ ra quyết định chính sách kinh tế được xây dựng nhằm đánh giá tác động của **AI, chuyển đổi số, vốn nhân lực và đầu tư công nghệ** tới quá trình phát triển kinh tế Việt Nam.

Dự án kết hợp các phương pháp:

* Kinh tế lượng (Econometric Modeling)
* Hàm sản xuất Cobb-Douglas mở rộng
* Tối ưu hóa toán học (Linear Programming, Mixed Integer Programming)
* TOPSIS đánh giá đa tiêu chí
* Quy hoạch động (Dynamic Programming)
* Mô hình lao động dưới tác động AI
* Phân tích rủi ro và mô phỏng kịch bản
* Dashboard trực quan hóa chính sách

Mục tiêu của dự án là xây dựng một **Decision Support System (DSS)** giúp nhà hoạch định chính sách đánh giá các chiến lược phát triển kinh tế số và AI tại Việt Nam giai đoạn **2026–2030**.

---

# 🎯 Research Questions

AIDEOM-VN tập trung trả lời các câu hỏi chính:

### 1. AI và chuyển đổi số đóng góp như thế nào vào tăng trưởng kinh tế?

Mô hình mở rộng hàm sản xuất Cobb-Douglas để phân tích:

* TFP (Total Factor Productivity)
* Digital Economy (D)
* Artificial Intelligence (AI)
* Human Capital (H)

Kết quả mô hình được sử dụng để đánh giá chất lượng tăng trưởng và khả năng đạt mục tiêu kinh tế số.

---

### 2. Ngân sách đầu tư số nên được phân bổ như thế nào?

Hệ thống tối ưu hóa phân bổ nguồn lực giữa:

* Hạ tầng số
* AI & dữ liệu
* Nhân lực số
* R&D công nghệ

bằng các mô hình LP/MIP nhằm tối đa hóa tác động kinh tế.

---

### 3. Chính sách AI ảnh hưởng tới thị trường lao động ra sao?

Mô hình đánh giá:

* Việc làm tạo mới bởi AI
* Việc làm bị thay thế
* Nhu cầu đào tạo lại
* Ngưỡng cân bằng lao động

---

### 4. Kịch bản phát triển nào phù hợp nhất cho Việt Nam?

Hệ thống xây dựng và xếp hạng 5 kịch bản chính sách:

| Scenario | Description  |
| -------- | ------------ |
| S1       | Truyền thống |
| S2       | Số hóa nhanh |
| S3       | AI dẫn dắt   |
| S4       | Bao trùm số  |
| S5       | Tối ưu LP    |

Kết quả đánh giá tổng hợp lựa chọn **S4 – Bao trùm số** là phương án cân bằng nhất giữa tăng trưởng kinh tế, việc làm, chuyển đổi số và kiểm soát rủi ro.

---

# 🏗️ System Architecture

```
AIDEOM-VN
│
├── M1: Extended Cobb-Douglas Growth Model
│       ├── GDP Forecasting
│       ├── TFP Estimation
│       └── Growth Decomposition
│
├── M2: Digital & AI Readiness Assessment
│       ├── TOPSIS Ranking
│       └── Regional Comparison
│
├── M3: Investment Optimization
│       ├── Linear Programming
│       ├── Mixed Integer Programming
│       └── Budget Allocation
│
├── M4: AI Labor Impact Model
│       ├── Job Creation
│       ├── Job Displacement
│       └── Retraining Analysis
│
├── M5: Risk Analysis
│       ├── Scenario Simulation
│       └── Policy Risk Evaluation
│
└── M6: Interactive Dashboard
        └── Streamlit Application
```

---

# 🧩 Core Modules

## M1 — Extended Cobb-Douglas Production Function

Phân tích tăng trưởng kinh tế Việt Nam 2020–2025 dựa trên:

* Capital (K)
* Labor (L)
* Digital Economy (D)
* AI Adoption
* Human Capital (H)

Một số kết quả:

* TFP tăng từ 27.75 (2020) lên 34.91 (2025)
* MAPE dự báo GDP đạt khoảng 6.42%

---

## M2 — Digital & AI Readiness Ranking

Đánh giá mức độ sẵn sàng AI và chuyển đổi số của 6 vùng kinh tế:

* Trung du miền núi Bắc Bộ
* Đồng bằng sông Hồng
* Bắc Trung Bộ & Duyên hải miền Trung
* Tây Nguyên
* Đông Nam Bộ
* Đồng bằng sông Cửu Long

Sử dụng:

* Expert Weighting
* Entropy Weight
* TOPSIS Ranking

---

## M3 — Policy Optimization Engine

Tối ưu hóa đầu tư:

* Digital Infrastructure
* AI/Data
* Digital Human Capital
* Technology R&D

Công cụ:

* PuLP
* CBC Solver
* Mixed Integer Programming

Ví dụ ứng dụng:

* Chọn danh mục dự án số quốc gia
* Tối đa hóa GDP tăng thêm
* Phân tích shadow price ngân sách

---

## M4 — AI Labor Transformation Model

Phân tích:

* AI tạo việc làm mới
* AI thay thế lao động
* Nhu cầu reskilling/upskilling

Mục tiêu:

Đánh giá khả năng thích ứng của thị trường lao động Việt Nam trong giai đoạn AI.

---

## M5 — Multi-Scenario Policy Simulation

Mô phỏng các chiến lược phát triển:

* Digital-first
* AI-driven
* Inclusive digital growth
* Traditional growth

Đánh giá dựa trên:

* GDP Growth
* Employment
* Digital Adoption
* Risk Level

---

## M6 — Interactive Dashboard

Dashboard được phát triển bằng **Streamlit**, cho phép:

* Chạy mô hình
* Điều chỉnh tham số
* So sánh kịch bản
* Trực quan hóa kết quả

---

# 🛠️ Technology Stack

## Programming

* Python 3.x

## Data Science

* NumPy
* Pandas
* SciPy
* Scikit-learn

## Optimization

* PuLP
* CBC Solver
* Pyomo

## Visualization

* Plotly
* Matplotlib
* Streamlit

## Mathematical Modeling

* Cobb-Douglas Production Function
* TOPSIS
* Linear Programming
* Dynamic Programming
* Reinforcement Learning

---

# 📂 Project Structure

```
AIDEOM-VN/
│
├── app.py                  # Streamlit Dashboard
│
├── models/
│   ├── cobb_douglas.py     # M1 Growth Model
│   ├── topsis.py            # M2 Ranking Model
│   ├── optimization.py      # M3 LP/MIP Model
│   ├── labor_ai.py          # M4 Labor Model
│   └── risk.py              # M5 Risk Model
│
├── data/
│   ├── vietnam_data.csv
│   └── scenarios.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── report/
│   └── policy_analysis.pdf
│
├── requirements.txt
│
└── README.md
```

---

# 🚀 Installation

Clone repository:

```bash
git clone https://github.com/yourusername/AIDEOM-VN.git

cd AIDEOM-VN
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run dashboard:

```bash
streamlit run app.py
```

---

# 📊 Main Results

Một số kết quả nổi bật:

✅ Xây dựng mô hình tăng trưởng kinh tế Việt Nam có tích hợp AI và chuyển đổi số

✅ Đánh giá mức độ sẵn sàng AI của 6 vùng kinh tế

✅ Tối ưu hóa phân bổ ngân sách đầu tư số

✅ Xây dựng 5 kịch bản phát triển 2026–2030

✅ Xác định kịch bản ưu tiên:

**S4 – Digital Inclusive Growth**

---

# 🔬 Academic Contribution

Dự án đóng góp một framework tích hợp giữa:

```
Economic Growth Theory
        +
Artificial Intelligence
        +
Optimization Mathematics
        +
Policy Simulation
```

Framework này có thể mở rộng cho:

* Phân tích chính sách quốc gia
* Quy hoạch phát triển vùng
* Đánh giá tác động AI
* Chiến lược chuyển đổi số

---

# 👨‍💻 Author

**Nguyen Thi Minh Anh**

Research Project:

> "Mô hình ra quyết định phát triển kinh tế Việt Nam trong kỷ nguyên AI"

---

# 📄 License

This project is developed for academic research and educational purposes.
