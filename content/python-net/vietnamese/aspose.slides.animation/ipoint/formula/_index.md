---
title: formula property
second_title: Tham khảo API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.animation/ipoint/formula/
weight: 10
---
## thuộc tính công thức
Các công thức trong các thuộc tính values, from, to, by có thể được tạo thành từ những thành phần sau:
            Các toán tử số học chuẩn: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Hằng số: ‘pi’ ‘e’
            Các toán tử điều kiện: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            Các toán tử so sánh: '==', '>=', '', '!=', '!'
            Các toán tử lượng giác: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Logarit tự nhiên ‘ln()’
            Tham chiếu thuộc tính (các thuộc tính được host hỗ trợ)
            
            ví dụ: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Đọc/ghi **str**.

### Định nghĩa:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```


### Xem thêm
* lớp [`IPoint`](/slides/python-net/vi/aspose.slides.animation/ipoint)
* module [`aspose.slides.animation`](/slides/python-net/vi/aspose.slides.animation)
* thư viện [`Aspose.Slides`](/slides/python-net)