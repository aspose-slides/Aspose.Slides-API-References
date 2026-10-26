---
title: from_rgb method
second_title: Tham khảo API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/color/from_rgb/
weight: 50
---
## from_rgb(r, g, b) {#int-int-int}
Tạo một màu không trong suốt (alpha là 255) từ các giá trị đỏ, xanh lá và xanh dương được chỉ định.

### Trả về

Màu được tạo ra từ các giá trị đã chỉ định.



```python
@staticmethod
def from_rgb(r, g, b):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| r | **int** | Giá trị thành phần đỏ. Các giá trị hợp lệ là từ 0 đến 255. |
| g | **int** | Giá trị thành phần xanh lá. Các giá trị hợp lệ là từ 0 đến 255. |
| b | **int** | Giá trị thành phần xanh dương. Các giá trị hợp lệ là từ 0 đến 255. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **ValueError** | Giá trị thành phần nhỏ hơn 0 hoặc lớn hơn 255. |



### Xem thêm
* lớp [`Color`](/slides/python-net/vi/aspose.slides/color)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)