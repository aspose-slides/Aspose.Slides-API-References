---
title: from_known_color method
second_title: Tham khảo API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
Tạo một màu từ màu định trước được chỉ định.<br/>Đây là cách duy nhất để lấy một màu hệ thống (chẳng hạn `KnownColor.CONTROL`): các màu hệ thống không được hiển thị dưới dạng thuộc tính `Color` vì giá trị của chúng phụ thuộc vào giao diện bàn làm việc, nên chúng được đọc từ thời gian chạy của thư viện.

### Trả về

Màu mà phương thức này tạo.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| known_color | **KnownColor** | Một phần tử của kiểu liệt kê `KnownColor` (một `IntEnum` phản ánh .NET `System.Drawing.KnownColor`) hoặc giá trị nguyên của nó. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **ValueError** | Giá trị không phải là thành viên hợp lệ của `KnownColor`. |



### Xem thêm
* lớp [`Color`](/slides/python-net/vi/aspose.slides/color)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)