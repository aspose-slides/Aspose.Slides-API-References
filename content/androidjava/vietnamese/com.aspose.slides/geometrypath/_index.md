---
title: GeometryPath
second_title: Tham chiếu API Java Aspose.Slides cho Android
description: Biểu diễn đường hình học của GeometryShape
type: docs
url: /vi/com.aspose.slides/geometrypath/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Biểu diễn đường hình học của GeometryShape
## Các hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Tạo một instance của GeometryPath |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPathData()](#getPathData--) | Trả về đường hình học của GeometryShape dưới dạng mảng các đoạn đường. |
| [removeAt(int index)](#removeAt-int-) | Xóa đoạn tại chỉ mục được chỉ định của đường hình học. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Thêm đường thẳng vào cuối đường |
| [lineTo(float x, float y)](#lineTo-float-float-) | Thêm đường thẳng vào cuối đường |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Thêm đường thẳng vào vị trí được chỉ định của đường |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Thêm đường thẳng vào vị trí được chỉ định của đường |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Thêm cubic Bezier curve vào cuối đường |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Thêm cubic Bezier curve vào cuối đường |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Thêm cubic Bezier curve vào vị trí được chỉ định của đường |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Thêm cubic Bezier curve vào vị trí được chỉ định của đường |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Thêm quadratic Bezier curve vào cuối đường |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Thêm quadratic Bezier curve vào cuối đường |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Thêm quadratic Bezier curve vào vị trí được chỉ định của đường |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Thêm quadratic Bezier curve vào vị trí được chỉ định của đường |
| [closeFigure()](#closeFigure--) | Đóng hình hiện tại của đường này |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Đặt vị trí điểm tiếp theo. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Đặt vị trí điểm tiếp theo. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Thêm vòng cung được chỉ định vào đường. |
| [getFillMode()](#getFillMode--) | Đặt chế độ fill |
| [setFillMode(byte value)](#setFillMode-byte-) | Đặt chế độ fill |
| [getStroke()](#getStroke--) | Đặt kiểu hiển thị stroke |
| [setStroke(boolean value)](#setStroke-boolean-) | Đặt kiểu hiển thị stroke |

### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

Tạo một instance của GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

Trả về đường hình học của GeometryShape dưới dạng mảng các đoạn đường.

**Trả về:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa đoạn tại chỉ mục được chỉ định của đường hình học.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của đoạn đường hình học cần xóa. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```

Thêm đường thẳng vào cuối đường

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point | android.graphics.PointF | Điểm cuối của đường thẳng |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

Thêm đường thẳng vào cuối đường

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của điểm cuối của đường thẳng |
| y | float | Tọa độ Y của điểm cuối của đường thẳng |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```

Thêm đường thẳng vào vị trí được chỉ định của đường

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point | android.graphics.PointF | Điểm cuối |
| index | long | Chỉ mục của đoạn trong PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

Thêm đường thẳng vào vị trí được chỉ định của đường

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của điểm |
| y | float | Tọa độ Y của điểm |
| index | long | Chỉ mục của đoạn trong PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

Thêm cubic Bezier curve vào cuối đường

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point1 | android.graphics.PointF | Điểm hướng đầu tiên |
| point2 | android.graphics.PointF | Điểm hướng thứ hai |
| point3 | android.graphics.PointF | Điểm cuối |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Thêm cubic Bezier curve vào cuối đường

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x1 | float | Tọa độ X của điểm hướng đầu tiên |
| y1 | float | Tọa độ Y của điểm hướng đầu tiên |
| x2 | float | Tọa độ X của điểm hướng thứ hai |
| y2 | float | Tọa độ Y của điểm hướng thứ hai |
| x3 | float | Tọa độ X của điểm cuối |
| y3 | float | Tọa độ Y của điểm cuối |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

Thêm cubic Bezier curve vào vị trí được chỉ định của đường

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point1 | android.graphics.PointF | Điểm hướng đầu tiên |
| point2 | android.graphics.PointF | Điểm hướng thứ hai |
| point3 | android.graphics.PointF | Điểm cuối |
| index | long | Chỉ mục của đoạn trong PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Thêm cubic Bezier curve vào vị trí được chỉ định của đường

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x1 | float | Tọa độ X của điểm hướng đầu tiên |
| y1 | float | Tọa độ Y của điểm hướng đầu tiên |
| x2 | float | Tọa độ X của điểm hướng thứ hai |
| y2 | float | Tọa độ Y của điểm hướng thứ hai |
| x3 | float | Tọa độ X của điểm cuối |
| y3 | float | Tọa độ Y của điểm cuối |
| index | long | Chỉ mục của đoạn trong PathData |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```

Thêm quadratic Bezier curve vào cuối đường

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point1 | android.graphics.PointF | Điểm hướng |
| point2 | android.graphics.PointF | Điểm cuối |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Thêm quadratic Bezier curve vào cuối đường

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x1 | float | Tọa độ X của điểm hướng |
| y1 | float | Tọa độ Y của điểm hướng |
| x2 | float | Tọa độ X của điểm cuối |
| y2 | float | Tọa độ Y của điểm cuối |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```

Thêm quadratic Bezier curve vào vị trí được chỉ định của đường

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point1 | android.graphics.PointF | Điểm hướng |
| point2 | android.graphics.PointF | Điểm cuối |
| index | long | Chỉ mục của đoạn trong PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Thêm quadratic Bezier curve vào vị trí được chỉ định của đường

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x1 | float | Tọa độ X của điểm hướng |
| y1 | float | Tọa độ Y của điểm hướng |
| x2 | float | Tọa độ X của điểm cuối |
| y2 | float | Tọa độ Y của điểm cuối |
| index | long | Chỉ mục của đoạn trong PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

Đóng hình hiện tại của đường này

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```

Đặt vị trí điểm tiếp theo.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point | android.graphics.PointF | Vị trí điểm |

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

Thêm vòng cung được chỉ định vào đường.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| width | float | Chiều rộng của hình chữ nhật |
| heigth | float | Chiều cao của hình chữ nhật |
| startAngle | float | Góc bắt đầu. |
| sweepAngle | float | Góc quét. |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

Đặt chế độ fill

**Trả về:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

Đặt chế độ fill

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

Đặt kiểu hiển thị stroke

**Trả về:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

Đặt kiểu hiển thị stroke

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |