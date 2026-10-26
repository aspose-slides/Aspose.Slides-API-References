---
title: contains method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
Xác định xem điểm đã cho có nằm trong hình chữ nhật này hay không.

### Trả về

`True` nếu điểm nằm trong hình chữ nhật này; nếu không, `False`.



```python
def contains(self, point):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/vi/aspose.slides/point) | Điểm cần kiểm tra. Bất kỳ đối tượng nào có thuộc tính `x` và `y` đều được chấp nhận. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **TypeError** | Sai số lượng đối số. |


## contains(self, rect) {#rectangle}
Xác định xem vùng hình chữ nhật được biểu diễn bằng `rect` có hoàn toàn nằm trong hình chữ nhật này hay không.

### Trả về

`True` nếu vùng hình chữ nhật được biểu diễn bằng `rect` hoàn toàn nằm trong hình chữ nhật này; nếu không, `False`.



```python
def contains(self, rect):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/vi/aspose.slides/rectangle) | Hình chữ nhật cần kiểm tra. Bất kỳ đối tượng nào có thuộc tính `x`, `y`, `width` và `height` đều được chấp nhận. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **TypeError** | Sai số lượng đối số. |


## contains(self, x, y) {#int-int}
Xác định xem điểm đã cho có nằm trong hình chữ nhật này hay không.

### Trả về

`True` nếu điểm được xác định bởi `x` và `y` nằm trong hình chữ nhật này; nếu không, `False`.



```python
def contains(self, x, y):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x | **int** | Tọa độ x của điểm cần kiểm tra. |
| y | **int** | Tọa độ y của điểm cần kiểm tra. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **TypeError** | Sai số lượng đối số. |



### Xem thêm
* lớp [`Point`](/slides/python-net/vi/aspose.slides/point)
* lớp [`Rectangle`](/slides/python-net/vi/aspose.slides/rectangle)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)