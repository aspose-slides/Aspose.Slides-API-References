---
title: IGeometryPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represents geometry path of GeometryShape
type: docs
url: /vi/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

Biểu diễn đường hình học của GeometryShape
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPathData()](#getPathData--) | Trả về đường hình học của GeometryShape dưới dạng một mảng các đoạn đường. |
| [removeAt(int index)](#removeAt-int-) | Xóa đoạn tại chỉ mục được chỉ định của đường hình học. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Thêm đường thẳng vào cuối đường. |
| [lineTo(float x, float y)](#lineTo-float-float-) | Thêm đường thẳng vào cuối đường. |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Thêm đường thẳng vào vị trí được chỉ định của đường. |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Thêm đường thẳng vào vị trí được chỉ định của đường. |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Thêm đường cong Bezier bậc ba vào cuối đường. |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Thêm đường cong Bezier bậc ba vào cuối đường. |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Thêm đường cong Bezier bậc ba vào vị trí được chỉ định của đường. |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Thêm đường cong Bezier bậc ba vào vị trí được chỉ định của đường. |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Thêm đường cong Bezier bậc hai vào cuối đường. |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Thêm đường cong Bezier bậc hai vào cuối đường. |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Thêm đường cong Bezier bậc hai vào vị trí được chỉ định của đường. |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Thêm đường cong Bezier bậc hai vào vị trí được chỉ định của đường. |
| [closeFigure()](#closeFigure--) | Đóng hình hiện tại của đường này. |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Đặt vị trí điểm tiếp theo. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Đặt vị trí điểm tiếp theo. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Thêm cung được chỉ định vào đường. |
| [getFillMode()](#getFillMode--) | Đặt chế độ tô màu |
| [setFillMode(byte value)](#setFillMode-byte-) | Đặt chế độ tô màu |
| [getStroke()](#getStroke--) | Đặt kiểu nét vẽ |
| [setStroke(boolean value)](#setStroke-boolean-) | Đặt kiểu nét vẽ |
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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của đường hình học cần xóa. |
### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```


Thêm đường thẳng vào cuối đường

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point | android.graphics.PointF | Điểm cuối của đường |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```


Thêm đường thẳng vào cuối đường

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của điểm cuối của đường |
| y | float | Tọa độ Y của điểm cuối của đường |
### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```


Thêm đường thẳng vào vị trí được chỉ định của đường

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point | android.graphics.PointF | Điểm cuối |
| index | long | Chỉ mục của đoạn trong PathData |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
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
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```


Thêm đường cong Bezier bậc ba vào cuối đường

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point1 | android.graphics.PointF | Điểm hướng đầu tiên |
| point2 | android.graphics.PointF | Điểm hướng thứ hai |
| point3 | android.graphics.PointF | Điểm cuối |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Thêm đường cong Bezier bậc ba vào cuối đường

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
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```


Thêm đường cong Bezier bậc ba vào vị trí được chỉ định của đường

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point1 | android.graphics.PointF | Điểm hướng đầu tiên |
| point2 | android.graphics.PointF | Điểm hướng thứ hai |
| point3 | android.graphics.PointF | Điểm cuối |
| index | long | Chỉ mục của đoạn trong PathData |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Thêm đường cong Bezier bậc ba vào vị trí được chỉ định của đường

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
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```


Thêm đường cong Bezier bậc hai vào cuối đường

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point1 | android.graphics.PointF | Điểm hướng |
| point2 | android.graphics.PointF | Điểm cuối |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Thêm đường cong Bezier bậc hai vào cuối đường

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x1 | float | Tọa độ X của điểm hướng |
| y1 | float | Tọa độ Y của điểm hướng |
| x2 | float | Tọa độ X của điểm cuối |
| y2 | float | Tọa độ Y của điểm cuối |
### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```


Thêm đường cong Bezier bậc hai vào vị trí được chỉ định của đường

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point1 | android.graphics.PointF | Điểm hướng |
| point2 | android.graphics.PointF | Điểm cuối |
| index | long | Chỉ mục của đoạn trong PathData |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Thêm đường cong Bezier bậc hai vào vị trí được chỉ định của đường

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
public abstract void closeFigure()
```


Đóng hình hiện tại của đường này
### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```


Đặt vị trí điểm tiếp theo.

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| point | android.graphics.PointF | Vị trí điểm |
### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```


Đặt vị trí điểm tiếp theo.

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của điểm |
| y | float | Tọa độ Y của điểm |
### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


Thêm cung được chỉ định vào đường.

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| width | float | Chiều rộng của hình chữ nhật |
| heigth | float | Chiều cao của hình chữ nhật |
| startAngle | float | Góc bắt đầu. |
| sweepAngle | float | Góc quét |
### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```


Đặt chế độ tô màu

**Trả về:**  
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```


Đặt chế độ tô màu

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```


Đặt kiểu nét vẽ

**Trả về:**  
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```


Đặt kiểu nét vẽ

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |