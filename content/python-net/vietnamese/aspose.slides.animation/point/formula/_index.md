---
title: formula property
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.animation/point/formula/
weight: 20
---
## thuộc tính formula
Công thức trong các giá trị, thuộc tính from, to, by có thể bao gồm các thành phần sau:
            Standard arithmetic operators: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Constants: ‘pi’ ‘e’
            Conditional operators: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            Comparison operators: '==', '>=', '', '!=', '!'
            Trigonometric operators: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Natural logarithm ‘ln()’
            Property references (host supported properties)
            
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
* lớp [`Point`](/slides/python-net/vi/aspose.slides.animation/point)
* mô-đun [`aspose.slides.animation`](/slides/python-net/vi/aspose.slides.animation)
* thư viện [`Aspose.Slides`](/slides/python-net)