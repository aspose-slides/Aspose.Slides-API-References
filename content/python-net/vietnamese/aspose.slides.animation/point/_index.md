---
title: Point class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.animation/point/
---
## Lớp Point

Biểu diễn điểm hoạt hình.

Kiểu Point cung cấp các thành viên sau:

## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides.animation/point/__init__/#) | Hàm khởi tạo mặc định. |
| [`__init__(self, time, value, formula)`](/slides/python-net/vi/aspose.slides.animation/point/__init__/#float-any-str) | Tạo điểm hoạt hình với thời gian, giá trị và công thức. |

## Các thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`time`](/slides/python-net/vi/aspose.slides.animation/point/time/) | Biểu diễn giá trị thời gian.<br/>            Đọc/ghi **float**. |
| [`value`](/slides/python-net/vi/aspose.slides.animation/point/value/) | Biểu diễn giá trị điểm.<br/>            Chỉ: bool, ColorFormat, float, int, string.<br/>            Đọc/ghi **any**. |
| [`formula`](/slides/python-net/vi/aspose.slides.animation/point/formula/) | Công thức trong các giá trị, thuộc tính from, to, by có thể được tạo thành từ các yếu tố sau:<br/>            Các toán tử số học chuẩn: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Hằng số: ‘pi’ ‘e’<br/>            Toán tử điều kiện: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            Toán tử so sánh: '==', '>=', '', '!=', '!'<br/>            Các toán tử lượng giác: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Logarit tự nhiên ‘ln()’<br/>            Tham chiếu thuộc tính (các thuộc tính được máy chủ hỗ trợ)<br/>            <br/>            ví dụ: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Đọc/ghi **str**. |


### Xem thêm
* module [`aspose.slides.animation`](/slides/python-net/vi/aspose.slides.animation)
* thư viện [`Aspose.Slides`](/slides/python-net)