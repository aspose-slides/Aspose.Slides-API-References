---
title: from_name method
second_title: Aspose.Slides cho Python qua Tham chiếu API .NET
description: 
type: docs
url: /vi/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
Tạo một màu từ tên đã chỉ định của màu được định trước.<br/>Việc tra cứu không phân biệt chữ hoa chữ thường và bỏ qua dấu gạch dưới và khoảng trắng: `"LightBlue"`, `"lightblue"` và `"light_blue"` đều trả về `Color.light_blue`. Xem trang lớp [`Color`](/slides/python-net/vi/aspose.slides/color) để biết danh sách các màu được định trước.

### Trả về

Màu đã đặt tên.



```python
@staticmethod
def from_name(name):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| name | **str** | Một chuỗi là tên của một màu được định trước. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **ValueError** | Tên không phải là tên của một màu được định trước. |
| **TypeError** | Tên không phải là một chuỗi. |



### Xem thêm
* lớp [`Color`](/slides/python-net/vi/aspose.slides/color)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)