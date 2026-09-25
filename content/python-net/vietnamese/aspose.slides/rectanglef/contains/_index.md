---
title: contains method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
Xác định xem điểm đã cho có nằm trong hình chữ nhật này hay không.

### Returns
`True` if the point is contained within this rectangle; otherwise, `False`.

```python
def contains(self, point):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm để kiểm tra. Bất kỳ đối tượng nào có thuộc tính `x` và `y` đều được chấp nhận. |

### Exceptions
| Ngoại lệ | Mô tả |
| :- | :- |
| **TypeError** | Số lượng đối số không đúng. |

## contains(self, rect) {#rectanglef}
Xác định xem vùng hình chữ nhật được biểu diễn bởi `rect` có hoàn toàn nằm trong hình chữ nhật này hay không.

### Returns
`True` if the rectangular region represented by `rect` is entirely contained within this rectangle; otherwise, `False`.

```python
def contains(self, rect):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef) | Hình chữ nhật để kiểm tra. Bất kỳ đối tượng nào có các thuộc tính `x`, `y`, `width` và `height` đều được chấp nhận. |

### Exceptions
| Ngoại lệ | Mô tả |
| :- | :- |
| **TypeError** | Số lượng đối số không đúng. |

## contains(self, x, y) {#float-float}
Xác định xem điểm đã cho có nằm trong hình chữ nhật này hay không.

### Returns
`True` if the point defined by `x` and `y` is contained within this rectangle; otherwise, `False`.

```python
def contains(self, x, y):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x | **float** | Tọa độ x của điểm cần kiểm tra. |
| y | **float** | Tọa độ y của điểm cần kiểm tra. |

### Exceptions
| Ngoại lệ | Mô tả |
| :- | :- |
| **TypeError** | Số lượng đối số không đúng. |

### Xem thêm
* lớp [`PointF`](/slides/python-net/vi/aspose.slides/pointf)
* lớp [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)