---
title: ShapeFrame
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho các thuộc tính của khung hình dạng.
type: docs
url: /vi/com.aspose.slides/shapeframe/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

Đại diện cho các thuộc tính của khung hình dạng.

## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Tạo thuộc tính khung hình dạng mới. |

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getX()](#getX--) | Trả về tọa độ X của góc trên-trái của khung. |
| [getY()](#getY--) | Trả về tọa độ Y của góc trên-trái của khung. |
| [getWidth()](#getWidth--) | Trả về chiều rộng của khung. |
| [getHeight()](#getHeight--) | Trả về chiều cao của khung. |
| [getRotation()](#getRotation--) | Trả về số độ khung được quay quanh trục z. |
| [getCenterX()](#getCenterX--) | Trả về tọa độ X của trung tâm khung. |
| [getCenterY()](#getCenterY--) | Trả về tọa độ Y của trung tâm khung. |
| [getFlipH()](#getFlipH--) | Xác định xem khung có được lật ngang hay không. |
| [getFlipV()](#getFlipV--) | Xác định xem khung có được lật dọc hay không. |
| [getRectangle()](#getRectangle--) | Trả về tọa độ của khung. |
| [deepClone()](#deepClone--) | Sao chép |
| [cloneT()](#cloneT--) | Sao chép. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Trả về giá trị cho biết liệu thực thể này có bằng với đối tượng được chỉ định hay không. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Trả về giá trị cho biết liệu thực thể này có bằng với đối tượng được chỉ định hay không. |

### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

Tạo thuộc tính khung hình dạng mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của một khung. |
| y | float | Tọa độ Y của một khung. |
| width | float | Chiều rộng của một khung. |
| height | float | Chiều cao của một khung. |
| flipH | byte | True nếu khung được lật ngang. |
| flipV | byte | True nếu khung được lật dọc. |
| rotationAngle | float | Số độ khung được quay. |

### getX() {#getX--}
```
public final float getX()
```

Trả về tọa độ X của góc trên-trái của khung. Chỉ đọc float.

**Trả về:**
float

### getY() {#getY--}
```
public final float getY()
```

Trả về tọa độ Y của góc trên-trái của khung. Chỉ đọc float.

**Trả về:**
float

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Trả về chiều rộng của khung. Chỉ đọc float.

**Trả về:**
float

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Trả về chiều cao của khung. Chỉ đọc float.

**Trả về:**
float

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Trả về số độ khung được quay quanh trục z. Giá trị dương cho biết quay theo chiều kim đồng hồ; giá trị âm cho biết quay ngược chiều kim đồng hồ. Chỉ đọc float.

**Trả về:**
float

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

Trả về tọa độ X của trung tâm khung. Chỉ đọc float.

**Trả về:**
float

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

Trả về tọa độ Y của trung tâm khung. Chỉ đọc float.

**Trả về:**
float

### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

Xác định xem khung có được lật ngang hay không. Chỉ đọc [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

Xác định xem khung có được lật dọc hay không. Chỉ đọc [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```

Trả về tọa độ của khung. Chỉ đọc android.graphics.RectF.

**Trả về:**
android.graphics.RectF

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Sao chép

**Trả về:**
java.lang.Object - Khung hình dạng đã sao chép.

### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

Sao chép.

**Trả về:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Khung hình dạng đã sao chép.

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

Trả về giá trị cho biết liệu thực thể này có bằng với đối tượng được chỉ định hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | Đối tượng để so sánh với thực thể này. |

**Trả về:**
boolean - **true** nếu obj là một ShapeFrame có cùng giá trị với thực thể này; nếu không, **false**.

### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

Trả về giá trị cho biết liệu thực thể này có bằng với đối tượng được chỉ định hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | ShapeFRameEx để so sánh với thực thể này. |

**Trả về:**
boolean - **true** nếu value là một ShapeFrame có cùng giá trị với thực thể này; nếu không, **false**.