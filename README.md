# HR Headcount, Turnover & Staff Cost Dashboard

## Overview
Power BI dashboard phân tích **Headcount – Turnover – Staff Cost** ở cấp ngân hàng, phục vụ báo cáo quản trị và ra quyết định nhân sự.

**Tools:** Python (Google Colab), Power BI  
**Scope:** Bank-wide | 01–05/2022

---

## Data & Model
- **Fact:** Headcount Snapshot, Headcount (Actual + Forecast), Staff Cost  
- **Dimension:** Date, Division, Career Level (Career Tier)  
- **Summary:** Actual vs Plan (HC & Cost)

➡️ Star schema, dữ liệu chuẩn hóa trước khi load Power BI.

---

## Key Metrics
- Headcount, #In, #Out, Net Change  
- Voluntary Turnover (by Tenure, Division, Career Level)  
- Staff Cost & Budget Utilization

---

## Forecast
- **Method:** Trend-based Forecasting (Average Net Change)  
- Không dùng Power BI Forecast do chuỗi thời gian ngắn.

---

## Key Insights
- Headcount thực tế **-10.02% so với kế hoạch**, xu hướng giảm liên tục  
- New hires giảm mạnh → tuyển dụng không bù kịp nghỉ việc  
- IT vượt kế hoạch (Digital Banking), Retail Banking giảm ròng mạnh  
- Turnover cao ở nhóm tenure < 3 năm  
- Overtime vượt ngân sách → áp lực do thiếu hụt nhân sự

---

## Limitations
- Không có Employee ID → không phân tích transfer chi tiết  
- Dữ liệu ngắn hạn → giới hạn phương pháp forecast

---

**Author:** Phạm Thị Quỳnh Lâm

