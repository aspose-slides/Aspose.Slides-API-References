---
title: ShapeFrame
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn các thuộc tính của khung hình dạng.
type: docs
url: /vi/com.aspose.slides/shapeframe/
---
**Kế thừa:**
java.lang.Object

**Tất cả giao diện được thực hiện:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

Biểu diễn các thuộc tính của khung hình dạng.
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Tạo các thuộc tính khung hình dạng mới. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getX()](#getX--) | Trả về tọa độ X của góc trên-trái của một khung. |
| [getY()](#getY--) | Trả về tọa độ Y của góc trên-trái của một khung. |
| [getWidth()](#getWidth--) | Trả về chiều rộng của một khung. |
| [getHeight()](#getHeight--) | Trả về chiều cao của một khung. |
| [getRotation()](#getRotation--) | Trả về số độ mà khung được xoay quanh trục z. |
| [getCenterX()](#getCenterX--) | Trả về tọa độ X của trung tâm khung. |
| [getCenterY()](#getCenterY--) | Trả về tọa độ Y của trung tâm khung. |
| [getFlipH()](#getFlipH--) | Xác định xem khung có bị lật theo chiều ngang hay không. |
| [getFlipV()](#getFlipV--) | Xác định xem khung có bị lật theo chiều dọc hay không. |
| [getRectangle()](#getRectangle--) | Trả về tọa độ của một khung. |
| [deepClone()](#deepClone--) | Nhân bản |
| [cloneT()](#cloneT--) | Nhân bản. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Trả về giá trị cho biết liệu thể hiện này có bằng một đối tượng được chỉ định hay không. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Trả về giá trị cho biết liệu thể hiện này có bằng một đối tượng được chỉ định hay không. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

Tạo các thuộc tính khung hình dạng mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của một khung. |
| y | float | Tọa độ Y của một khung. |
| width | float | Chiều rộng của một khung. |
| height | float | Chiều cao của một khung. |
| flipH | byte | True nếu khung được lật theo chiều ngang. |
| flipV | byte | True nếu khung được lật theo chiều dọc. |
| rotationAngle | float | Số độ mà khung được xoay. |

### getX() {#getX--}
```
public final float getX()
```

Trả về tọa độ X của góc trên-trái của một khung. float chỉ đọc.

**Trả về:**
float
### getY() {#getY--}
```
public final float getY()
```

Trả về tọa độ Y của góc trên-trái của một khung. float chỉ đọc.

**Trả về:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Trả về chiều rộng của một khung. float chỉ đọc.

**Trả về:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Trả về chiều cao của một khung. float chỉ đọc.

**Trả về:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

Trả về số độ mà khung được xoay quanh trục z. Giá trị dương cho biết xoay theo chiều kim đồng hồ; giá trị âm cho biết xoay ngược chiều kim đồng hồ. float chỉ đọc.

**Trả về:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

Trả về tọa độ X của trung tâm khung. float chỉ đọc.

**Trả về:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

Trả về tọa độ Y của trung tâm khung. float chỉ đọc.

**Trả về:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

Xác định xem khung có bị lật theo chiều ngang hay không. [NullableBool](../../com.aspose.slides/nullablebool) chỉ đọc.

**Trả về:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

Xác định xem khung có bị lật theo chiều dọc hay không. [NullableBool](../../com.aspose.slides/nullablebool) chỉ đọc.

**Trả về:**
byte
### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

Trả về tọa độ của một khung. java.awt.geom.Rectangle2D.Float chỉ đọc.

**Trả về:**
java.awt.geom.Rectangle2D.Float
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Sao chép

**Trả về:**
java.lang.Object - Khung hình dạng đã được sao chép.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

Sao chép.

**Trả về:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Khung hình dạng đã được sao chép.
### hashCode() {#hashCode--}
```
public int hashCode()
```

**Trả về:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Trả về giá trị cho biết liệu thể hiện này có bằng một đối tượng được chỉ định hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | Đối tượng để so sánh với thể hiện này. |

**Trả về:**
boolean - **true** nếu obj là một ShapeFrame có cùng giá trị với thể hiện này; ngược lại, **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

Trả về giá trị cho biết liệu thể hiện này có bằng một đối tượng được chỉ định hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | ShapeFRameEx để so sánh với thể hiện này. |

**Trả về:**
boolean - **true** nếu value là một ShapeFrame có cùng giá trị với thể hiện này; ngược lại, **false**.