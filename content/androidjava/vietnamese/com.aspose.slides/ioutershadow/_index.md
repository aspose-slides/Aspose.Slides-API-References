---
title: IOuterShadow
second_title: Aspose.Slides cho Android qua Tham khảo API Java
description: Biểu diễn hiệu ứng Đổ bóng bên ngoài.
type: docs
url: /vi/com.aspose.slides/ioutershadow/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Biểu diễn hiệu ứng Đổ bóng bên ngoài.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Bán kính mờ, tính bằng điểm. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Bán kính mờ, tính bằng điểm. |
| [getDirection()](#getDirection--) | Hướng của bóng, tính bằng độ. |
| [setDirection(float value)](#setDirection-float-) | Hướng của bóng, tính bằng độ. |
| [getDistance()](#getDistance--) | Khoảng cách của bóng từ đối tượng, tính bằng điểm. |
| [setDistance(double value)](#setDistance-double-) | Khoảng cách của bóng từ đối tượng, tính bằng điểm. |
| [getShadowColor()](#getShadowColor--) | Màu của bóng. |
| [getRectangleAlign()](#getRectangleAlign--) | Căn chỉnh hình chữ nhật. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Căn chỉnh hình chữ nhật. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Góc nghiêng ngang, tính bằng độ. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Góc nghiêng ngang, tính bằng độ. |
| [getSkewVertical()](#getSkewVertical--) | Góc nghiêng dọc, tính bằng độ. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Góc nghiêng dọc, tính bằng độ. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Cho biết liệu bóng có xoay cùng với hình dạng hay không. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Cho biết liệu bóng có xoay cùng với hình dạng hay không. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Hệ số co dọc ngang, tính bằng phần trăm kích thước gốc. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Hệ số co dọc ngang, tính bằng phần trăm kích thước gốc. |
| [getScaleVertical()](#getScaleVertical--) | Hệ số co dọc dọc, tính bằng phần trăm kích thước gốc. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Hệ số co dọc dọc, tính bằng phần trăm kích thước gốc. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Bán kính mờ, tính bằng điểm. Giá trị mặc định - 0 pt. Đọc/ghi double.

**Trả về:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Bán kính mờ, tính bằng điểm. Giá trị mặc định - 0 pt. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Hướng của bóng, tính bằng độ. Giá trị mặc định - 0 � (trái-sang). Đọc/ghi float.

**Trả về:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Hướng của bóng, tính bằng độ. Giá trị mặc định - 0 � (trái-sang). Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Khoảng cách của bóng từ đối tượng, tính bằng điểm. Giá trị mặc định - 0 pt. Đọc/ghi double.

**Trả về:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Khoảng cách của bóng từ đối tượng, tính bằng điểm. Giá trị mặc định - 0 pt. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Màu của bóng. Giá trị mặc định - tự động đen (phụ thuộc vào chủ đề). Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Căn chỉnh hình chữ nhật. Giá trị mặc định - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Đọc/ghi [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Trả về:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Căn chỉnh hình chữ nhật. Giá trị mặc định - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Đọc/ghi [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Góc nghiêng ngang, tính bằng độ. Giá trị mặc định - 0 �. Đọc/ghi double.

**Trả về:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Góc nghiêng ngang, tính bằng độ. Giá trị mặc định - 0 �. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Góc nghiêng dọc, tính bằng độ. Giá trị mặc định - 0 �. Đọc/ghi double.

**Trả về:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Góc nghiêng dọc, tính bằng độ. Giá trị mặc định - 0 �. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Cho biết liệu bóng có xoay cùng với hình dạng hay không. Giá trị mặc định - true. Đọc/ghi boolean.

**Trả về:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Cho biết liệu bóng có xoay cùng với hình dạng hay không. Giá trị mặc định - true. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Hệ số co dọc ngang, tính bằng phần trăm kích thước gốc. Co dọc âm gây lật. Giá trị mặc định - 100 %. Đọc/ghi double.

**Trả về:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Hệ số co dọc ngang, tính bằng phần trăm kích thước gốc. Co dọc âm gây lật. Giá trị mặc định - 100 %. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Hệ số co dọc dọc, tính bằng phần trăm kích thước gốc. Co dọc âm gây lật. Giá trị mặc định - 100 %. Đọc/ghi double.

**Trả về:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Hệ số co dọc dọc, tính bằng phần trăm kích thước gốc. Co dọc âm gây lật. Giá trị mặc định - 100 %. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |