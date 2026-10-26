---
title: GeometryPath
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho đường dẫn hình học của GeometryShape
type: docs
url: /vi/com.aspose.slides/geometrypath/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Đại diện cho đường dẫn hình học của GeometryShape
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Tạo một thể hiện của GeometryPath |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPathData()](#getPathData--) | Trả về đường dẫn hình học của GeometryShape dưới dạng một mảng các đoạn đường. |
| [removeAt(int index)](#removeAt-int-) | Xóa đoạn tại chỉ số được chỉ định của đường dẫn hình học. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Thêm đường thẳng vào cuối đường dẫn |
| [lineTo(float x, float y)](#lineTo-float-float-) | Thêm đường thẳng vào cuối đường dẫn |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Thêm đường thẳng vào vị trí được chỉ định trên đường dẫn |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Thêm đường thẳng vào vị trí được chỉ định trên đường dẫn |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Thêm đường cong Bezier bậc ba vào cuối đường dẫn |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Thêm đường cong Bezier bậc ba vào cuối đường dẫn |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Thêm đường cong Bezier bậc ba vào vị trí được chỉ định trên đường dẫn |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Thêm đường cong Bezier bậc ba vào vị trí được chỉ định trên đường dẫn |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Thêm đường cong Bezier bậc hai vào cuối đường dẫn |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Thêm đường cong Bezier bậc hai vào cuối đường dẫn |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Thêm đường cong Bezier bậc hai vào vị trí được chỉ định trên đường dẫn |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Thêm đường cong Bezier bậc hai vào vị trí được chỉ định trên đường dẫn |
| [closeFigure()](#closeFigure--) | Đóng hình hiện tại của đường dẫn này |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Đặt vị trí điểm tiếp theo. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Đặt vị trí điểm tiếp theo. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Thêm cung đã chỉ định vào đường dẫn. |
| [getFillMode()](#getFillMode--) | Thiết lập chế độ tô |
| [setFillMode(byte value)](#setFillMode-byte-) | Thiết lập chế độ tô |
| [getStroke()](#getStroke--) | Thiết lập giao diện nét |
| [setStroke(boolean value)](#setStroke-boolean-) | Thiết lập giao diện nét |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```


Tạo một thể hiện của GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```


Trả về đường dẫn hình học của GeometryShape dưới dạng một mảng các đoạn đường.

**Trả về:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Xóa đoạn tại chỉ số được chỉ định của đường dẫn hình học.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của đoạn đường hình học cần được xoá. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```


Thêm đường thẳng vào cuối đường dẫn

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Điểm cuối của đoạn thẳng |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```


Thêm đường thẳng vào cuối đường dẫn

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của điểm cuối của đoạn thẳng |
| y | float | Tọa độ Y của điểm cuối của đoạn thẳng |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```


Thêm đường thẳng vào vị trí được chỉ định trên đường dẫn

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Điểm cuối |
| index | long | Chỉ số của đoạn trong PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```


Thêm đường thẳng vào vị trí được chỉ định trên đường dẫn

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của điểm |
| y | float | Tọa độ Y của điểm |
| index | long | Chỉ số của đoạn trong PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```


Thêm đường cong Bezier bậc ba vào cuối đường dẫn

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Điểm hướng đầu tiên |
| point2 | java.awt.geom.Point2D.Float | Điểm hướng thứ hai |
| point3 | java.awt.geom.Point2D.Float | Điểm cuối |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Thêm đường cong Bezier bậc ba vào cuối đường dẫn

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x1 | float | Tọa độ X của điểm hướng đầu tiên |
| y1 | float | Tọa độ Y của điểm hướng đầu tiên |
| x2 | float | Tọa độ X của điểm hướng thứ hai |
| y2 | float | Tọa độ Y của điểm hướng thứ hai |
| x3 | float | Tọa độ X của điểm cuối |
| y3 | float | Tọa độ Y của điểm cuối |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```


Thêm đường cong Bezier bậc ba vào vị trí được chỉ định trên đường dẫn

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Điểm hướng đầu tiên |
| point2 | java.awt.geom.Point2D.Float | Điểm hướng thứ hai |
| point3 | java.awt.geom.Point2D.Float | Điểm cuối |
| index | long | Chỉ số của đoạn trong PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Thêm đường cong Bezier bậc ba vào vị trí được chỉ định trên đường dẫn

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x1 | float | Tọa độ X của điểm hướng đầu tiên |
| y1 | float | Tọa độ Y của điểm hướng đầu tiên |
| x2 | float | Tọa độ X của điểm hướng thứ hai |
| y2 | float | Tọa độ Y của điểm hướng thứ hai |
| x3 | float | Tọa độ X của điểm cuối |
| y3 | float | Tọa độ Y của điểm cuối |
| index | long | Chỉ số của đoạn trong PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```


Thêm đường cong Bezier bậc hai vào cuối đường dẫn

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Điểm hướng |
| point2 | java.awt.geom.Point2D.Float | Điểm cuối |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Thêm đường cong Bezier bậc hai vào cuối đường dẫn

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x1 | float | Tọa độ X của điểm hướng |
| y1 | float | Tọa độ Y của điểm hướng |
| x2 | float | Tọa độ X của điểm cuối |
| y2 | float | Tọa độ Y của điểm cuối |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```


Thêm đường cong Bezier bậc hai vào vị trí được chỉ định trên đường dẫn

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Điểm hướng |
| point2 | java.awt.geom.Point2D.Float | Điểm cuối |
| index | long | Chỉ số của đoạn trong PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Thêm đường cong Bezier bậc hai vào vị trí được chỉ định trên đường dẫn

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x1 | float | Tọa độ X của điểm hướng |
| y1 | float | Tọa độ Y của điểm hướng |
| x2 | float | Tọa độ X của điểm cuối |
| y2 | float | Tọa độ Y của điểm cuối |
| index | long | Chỉ số của đoạn trong PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```


Đóng hình hiện tại của đường dẫn này

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```


Đặt vị trí điểm tiếp theo.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Vị trí điểm |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```


Đặt vị trí điểm tiếp theo.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của điểm |
| y | float | Tọa độ Y của điểm |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


Thêm cung đã chỉ định vào đường dẫn.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| width | float | Chiều rộng của hình chữ nhật |
| heigth | float | Chiều cao của hình chữ nhật |
| startAngle | float | Góc bắt đầu. |
| sweepAngle | float | Góc quét |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```


Thiết lập chế độ tô

**Trả về:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```


Thiết lập chế độ tô

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```


Thiết lập giao diện nét

**Trả về:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```


Thiết lập giao diện nét

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |