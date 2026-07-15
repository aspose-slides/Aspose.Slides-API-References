---
title: IShapeFrame
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Mô tả các thuộc tính của khung hình dạng.
type: docs
url: /vi/com.aspose.slides/ishapeframe/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

Mô tả các thuộc tính của khung hình dạng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getX()](#getX--) | Trả về tọa độ X của góc trên-trái của một khung hình. |
| [getY()](#getY--) | Trả về tọa độ Y của góc trên-trái của một khung hình. |
| [getWidth()](#getWidth--) | Trả về chiều rộng của một khung hình. |
| [getHeight()](#getHeight--) | Trả về chiều cao của một khung hình. |
| [getRotation()](#getRotation--) | Trả về số độ mà khung hình được quay quanh trục z. |
| [getCenterX()](#getCenterX--) | Trả về tọa độ X của tâm khung hình. |
| [getCenterY()](#getCenterY--) | Trả về tọa độ Y của tâm khung hình. |
| [getFlipH()](#getFlipH--) | Xác định liệu khung hình có bị lật theo chiều ngang hay không. |
| [getFlipV()](#getFlipV--) | Xác định liệu khung hình có bị lật theo chiều dọc hay không. |
| [getRectangle()](#getRectangle--) | Trả về các tọa độ của khung hình. |
### getX() {#getX--}
```
public abstract float getX()
```


Trả về tọa độ X của góc trên-trái của một khung hình. Chỉ đọc float.

**Returns:**
float
### getY() {#getY--}
```
public abstract float getY()
```


Trả về tọa độ Y của góc trên-trái của một khung hình. Chỉ đọc float.

**Returns:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```


Trả về chiều rộng của một khung hình. Chỉ đọc float.

**Returns:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Trả về chiều cao của một khung hình. Chỉ đọc float.

**Returns:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```


Trả về số độ mà khung hình được quay quanh trục z. Giá trị dương chỉ quay theo chiều kim đồng hồ; giá trị âm chỉ quay ngược chiều kim đồng hồ. Chỉ đọc float.

**Returns:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```


Trả về tọa độ X của tâm khung hình. Chỉ đọc float.

**Returns:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```


Trả về tọa độ Y của tâm khung hình. Chỉ đọc float.

**Returns:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```


Xác định liệu khung hình có bị lật theo chiều ngang hay không. Chỉ đọc [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```


Xác định liệu khung hình có bị lật theo chiều dọc hay không. Chỉ đọc [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### getRectangle() {#getRectangle--}
```
public abstract RectF getRectangle()
```


Trả về các tọa độ của khung hình. Chỉ đọc android.graphics.RectF.

**Returns:**
android.graphics.RectF