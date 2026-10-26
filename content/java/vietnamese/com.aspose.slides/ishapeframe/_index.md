---
title: IShapeFrame
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn các thuộc tính của khung hình dạng.
type: docs
url: /vi/com.aspose.slides/ishapeframe/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

Biểu diễn các thuộc tính của khung hình dạng.
## Methods

| Method | Description |
| --- | --- |
| [getX()](#getX--) | Trả về tọa độ X của góc trên-trái của một khung. |
| [getY()](#getY--) | Trả về tọa độ Y của góc trên-trái của một khung. |
| [getWidth()](#getWidth--) | Trả về chiều rộng của một khung. |
| [getHeight()](#getHeight--) | Trả về chiều cao của một khung. |
| [getRotation()](#getRotation--) | Trả về số độ mà khung được xoay quanh trục z. |
| [getCenterX()](#getCenterX--) | Trả về tọa độ X của trung tâm khung. |
| [getCenterY()](#getCenterY--) | Trả về tọa độ Y của trung tâm khung. |
| [getFlipH()](#getFlipH--) | Xác định xem khung có bị lật ngang không. |
| [getFlipV()](#getFlipV--) | Xác định xem khung có bị lật dọc không. |
| [getRectangle()](#getRectangle--) | Trả về tọa độ của một khung. |
### getX() {#getX--}
```
public abstract float getX()
```

Trả về tọa độ X của góc trên-trái của một khung. Chỉ-đọc float.

**Returns:**
float
### getY() {#getY--}
```
public abstract float getY()
```

Trả về tọa độ Y của góc trên-trái của một khung. Chỉ-đọc float.

**Returns:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Trả về chiều rộng của một khung. Chỉ-đọc float.

**Returns:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Trả về chiều cao của một khung. Chỉ-đọc float.

**Returns:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Trả về số độ mà khung được xoay quanh trục z. Giá trị dương cho biết phép quay theo chiều kim đồng hồ; giá trị âm cho biết phép quay ngược chiều kim đồng hồ. Chỉ-đọc float.

**Returns:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```

Trả về tọa độ X của trung tâm khung. Chỉ-đọc float.

**Returns:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```

Trả về tọa độ Y của trung tâm khung. Chỉ-đọc float.

**Returns:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```

Xác định xem khung có bị lật ngang không. Chỉ-đọc [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```

Xác định xem khung có bị lật dọc không. Chỉ-đọc [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### getRectangle() {#getRectangle--}
```
public abstract Rectangle2D.Float getRectangle()
```

Trả về tọa độ của một khung. Chỉ-đọc java.awt.geom.Rectangle2D.Float.

**Returns:**
java.awt.geom.Rectangle2D.Float