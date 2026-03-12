# Các bug trong web php
## Syntax
### pages/reports.php
- dòng 15 thiếu dấu ) 

### pages/customers.php
- dòng 3 thiếu dấu ;

### pages/settings.php 
- dòng 5 thiếu dấu ,

## Logic
### pages/checkout.php
- dòng 14 giá trị discountPercent là 10/100 thay vì 10 
- dòng 16 sửa shippingFee để phù hợp với yêu cầu (free cho những đơn hàng lớn) 

### includes/orders.php
- dòng 6 chỉnh điều kiện là === 'pending' thay vì != 'completed'
- dòng 12 thay vì sort tăng dần theo id thì sort đơn giảm dần theo id (newest first) 

### pages/dashboard.php 
- dòng 12 chỉnh lại giá trị của biến totalRevenue = qty * price (thay vì = qty) 
- dòng 19 chỉnh lại điều kiện của stock là <= 5 thay vì > 5 
