---
title: IGeometryPath
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho đường hình học của GeometryShape
type: docs
url: /vi/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

Đại diện cho đường hình học của GeometryShape
## Phương thức

| Method | Mô tả |
| --- | --- |
| [getPathData()](#getPathData--) | Trả về đường hình học của GeometryShape dưới dạng một mảng các đoạn đường. |
| [removeAt(int index)](#removeAt-int-) | Xóa đoạn tại chỉ mục được chỉ định của đường hình học. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Thêm đoạn thẳng vào cuối đường |
| [lineTo(float x, float y)](#lineTo-float-float-) | Thêm đoạn thẳng vào cuối đường |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Thêm đoạn thẳng vào vị trí được chỉ định của đường |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Thêm đoạn thẳng vào vị trí được chỉ định của đường |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Thêm đường cong Bezier bậc ba vào cuối đường |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Thêm đường cong Bezier bậc ba vào cuối đường |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Thêm đường cong Bezier bậc ba vào vị trí được chỉ định của đường |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Thêm đường cong Bezier bậc ba vào vị trí được chỉ định của đường |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Thêm đường cong Bezier bậc hai vào cuối đường |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Thêm đường cong Bezier bậc hai vào cuối đường |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Thêm đường cong Bezier bậc hai vào vị trí được chỉ định của đường |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Thêm đường cong Bezier bậc hai vào vị trí được chỉ định của đường |
| [closeFigure()](#closeFigure--) | Đóng hình hiện tại của đường này |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Đặt vị trí điểm tiếp theo. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Đặt vị trí điểm tiếp theo. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Thêm cung được chỉ định vào đường. |
| [getFillMode()](#getFillMode--) | Đặt chế độ tô |
| [setFillMode(byte value)](#setFillMode-byte-) | Đặt chế độ tô |
| [getStroke()](#getStroke--) | Đặt kiểu viền |
| [setStroke(boolean value)](#setStroke-boolean-) | Đặt kiểu viền |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

Trả về đường hình học của GeometryShape dưới dạng một mảng các đoạn đường.

**Trả về:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa đoạn tại chỉ mục được chỉ định của đường hình học.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục của đoạn trong đường hình học cần xóa. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public abstract void lineTo(Point2D.Float point)
```

Thêm đoạn thẳng vào cuối đường

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Điểm cuối của đoạn thẳng |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```

Thêm đoạn thẳng vào cuối đường

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Tọa độ X của điểm cuối đoạn thẳng |
| y | float | Tọa độ Y của điểm cuối đoạn thẳng |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public abstract void lineTo(Point2D.Float point, long index)
```

Thêm đoạn thẳng vào vị trí được chỉ định của đường

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Điểm cuối |
| index | long | Chỉ mục của đoạn trong PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

Thêm đoạn thẳng vào vị trí được chỉ định của đường

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Tọa độ X của điểm |
| y | float | Tọa độ Y của điểm |
| index | long | Chỉ mục của đoạn trong PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

Thêm đường cong Bezier bậc ba vào cuối đường

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Điểm hướng đầu tiên |
| point2 | java.awt.geom.Point2D.Float | Điểm hướng thứ hai |
| point3 | java.awt.geom.Point2D.Float | Điểm cuối |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Thêm đường cong Bezier bậc ba vào cuối đường

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | Tọa độ X của điểm hướng đầu tiên |
| y1 | float | Tọa độ Y của điểm hướng đầu tiên |
| x2 | float | Tọa độ X của điểm hướng thứ hai |
| y2 | float | Tọa độ Y của điểm hướng thứ hai |
| x3 | float | Tọa độ X của điểm cuối |
| y3 | float | Tọa độ Y của điểm cuối |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

Thêm đường cong Bezier bậc ba vào vị trí được chỉ định của đường

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Điểm hướng đầu tiên |
| point2 | java.awt.geom.Point2D.Float | Điểm hướng thứ hai |
| point3 | java.awt.geom.Point2D.Float | Điểm cuối |
| index | long | Chỉ mục của đoạn trong PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Thêm đường cong Bezier bậc ba vào vị trí được chỉ định của đường

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | Tọa độ X của điểm hướng đầu tiên |
| y1 | float | Tọa độ Y của điểm hướng đầu tiên |
| x2 | float | Tọa độ X của điểm hướng thứ hai |
| y2 | float | Tọa độ Y của điểm hướng thứ hai |
| x3 | float | Tọa độ X của điểm cuối |
| y3 | float | Tọa độ Y của điểm cuối |
| index | long | Chỉ mục của đoạn trong PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

Thêm đường cong Bezier bậc hai vào cuối đường

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Điểm hướng |
| point2 | java.awt.geom.Point2D.Float | Điểm cuối |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Thêm đường cong Bezier bậc hai vào cuối đường

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | Tọa độ X của điểm hướng |
| y1 | float | Tọa độ Y của điểm hướng |
| x2 | float | Tọa độ X của điểm cuối |
| y2 | float | Tọa độ Y của điểm cuối |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

Thêm đường cong Bezier bậc hai vào vị trí được chỉ định của đường

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Điểm hướng |
| point2 | java.awt.geom.Point2D.Float | Điểm cuối |
| index | long | Chỉ mục của đoạn trong PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Thêm đường cong Bezier bậc hai vào vị trí được chỉ định của đường

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | Tọa độ X của điểm hướng |
| y1 | float | Tọa độ Y của điểm hướng |
| x2 | float | Tọa độ X của điểm cuối |
| y2 | float | Tọa độ Y của điểm cuối |
| index | long | Chỉ mục của đoạn trong PathData |

### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```

Đóng hình hiện tại của đường này

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public abstract void moveTo(Point2D.Float point)
```

Đặt vị trí điểm tiếp theo.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Vị trí điểm |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

Đặt vị trí điểm tiếp theo.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Tọa độ X của điểm |
| y | float | Tọa độ Y của điểm |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Thêm cung được chỉ định vào đường.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | Chiều rộng của hình chữ nhật |
| heigth | float | Chiều cao của hình chữ nhật |
| startAngle | float | Góc bắt đầu. |
| sweepAngle | float | Góc quét |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```

Đặt chế độ tô

**Trả về:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```

Đặt chế độ tô

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```

Đặt kiểu viền

**Trả về:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

Đặt kiểu viền

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |