---
title: OuterShadow
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đại diện cho hiệu ứng Outer Shadow.
type: docs
url: /vi/com.aspose.slides/outershadow/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IOuterShadow](../../com.aspose.slides/ioutershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class OuterShadow implements IOuterShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Đại diện cho hiệu ứng Outer Shadow.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Bán kính làm mờ, tính bằng điểm. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Bán kính làm mờ, tính bằng điểm. |
| [getDirection()](#getDirection--) | Hướng của bóng, tính bằng độ. |
| [setDirection(float value)](#setDirection-float-) | Hướng của bóng, tính bằng độ. |
| [getDistance()](#getDistance--) | Khoảng cách của bóng từ đối tượng, tính bằng điểm. |
| [setDistance(double value)](#setDistance-double-) | Khoảng cách của bóng từ đối tượng, tính bằng điểm. |
| [getShadowColor()](#getShadowColor--) | Màu của bóng. |
| [getRectangleAlign()](#getRectangleAlign--) | Căn hình chữ nhật. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Căn hình chữ nhật. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Góc nghiêng ngang, tính bằng độ. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Góc nghiêng ngang, tính bằng độ. |
| [getSkewVertical()](#getSkewVertical--) | Góc nghiêng dọc, tính bằng độ. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Góc nghiêng dọc, tính bằng độ. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Cho biết liệu bóng có quay cùng với hình dạng hay không. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Cho biết liệu bóng có quay cùng với hình dạng hay không. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Hệ số co dọc chiều ngang, tính bằng phần trăm kích thước gốc. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Hệ số co dọc chiều ngang, tính bằng phần trăm kích thước gốc. |
| [getScaleVertical()](#getScaleVertical--) | Hệ số co dọc chiều dọc, tính bằng phần trăm kích thước gốc. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Hệ số co dọc chiều dọc, tính bằng phần trăm kích thước gốc. |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng Outer Shadow hiệu quả khi đã áp dụng tính kế thừa. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem [OuterShadow](../../com.aspose.slides/outershadow) được chỉ định có bằng với [OuterShadow](../../com.aspose.slides/outershadow) hiện tại hay không. |
| [hashCode()](#hashCode--) | Đóng vai trò như một hàm băm cho một kiểu cụ thể. |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

Bán kính làm mờ, tính bằng điểm. Giá trị mặc định - 0 pt. Đọc/ghi double.

**Trả về:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

Bán kính làm mờ, tính bằng điểm. Giá trị mặc định - 0 pt. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

Hướng của bóng, tính bằng độ. Giá trị mặc định - 0 � (trái sang phải). Đọc/ghi float.

**Trả về:**
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Hướng của bóng, tính bằng độ. Giá trị mặc định - 0 � (trái sang phải). Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

Khoảng cách của bóng từ đối tượng, tính bằng điểm. Giá trị mặc định - 0 pt. Đọc/ghi double.

**Trả về:**
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Khoảng cách của bóng từ đối tượng, tính bằng điểm. Giá trị mặc định - 0 pt. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Màu của bóng. Giá trị mặc định - automatic black (theme-dependent). Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

Căn hình chữ nhật. Giá trị mặc định - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Đọc/ghi [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Trả về:**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

Căn hình chữ nhật. Giá trị mặc định - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Đọc/ghi [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

Góc nghiêng ngang, tính bằng độ. Giá trị mặc định - 0 �. Đọc/ghi double.

**Trả về:**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

Góc nghiêng ngang, tính bằng độ. Giá trị mặc định - 0 �. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

Góc nghiêng dọc, tính bằng độ. Giá trị mặc định - 0 �. Đọc/ghi double.

**Trả về:**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

Góc nghiêng dọc, tính bằng độ. Giá trị mặc định - 0 �. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

Cho biết liệu bóng có quay cùng với hình dạng hay không. Giá trị mặc định - true. Đọc/ghi boolean.

**Trả về:**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

Cho biết liệu bóng có quay cùng với hình dạng hay không. Giá trị mặc định - true. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

Hệ số co dọc chiều ngang, tính bằng phần trăm kích thước gốc. Negative scaling causes a flip. Giá trị mặc định - 100 %. Đọc/ghi double.

**Trả về:**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

Hệ số co dọc chiều ngang, tính bằng phần trăm kích thước gốc. Negative scaling causes a flip. Giá trị mặc định - 100 %. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

Hệ số co dọc chiều dọc, tính bằng phần trăm kích thước gốc. Negative scaling causes a flip. Giá trị mặc định - 100 %. Đọc/ghi double.

**Trả về:**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

Hệ số co dọc chiều dọc, tính bằng phần trăm kích thước gốc. Negative scaling causes a flip. Giá trị mặc định - 100 %. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IOuterShadowEffectiveData getEffective()
```

Lấy dữ liệu hiệu ứng Outer Shadow hiệu quả khi đã áp dụng tính kế thừa.

**Trả về:**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata) - A [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

Phiên bản. Chỉ đọc long.

**Trả về:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Trả về IPresentationComponent cha. Chỉ đọc [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Trả về:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Xác định xem [OuterShadow](../../com.aspose.slides/outershadow) được chỉ định có bằng với [OuterShadow](../../com.aspose.slides/outershadow) hiện tại hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | [OuterShadow](../../com.aspose.slides/outershadow) để so sánh. |

**Trả về:**
boolean - true nếu các đối tượng bằng nhau; ngược lại, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Đóng vai trò như một hàm băm cho một kiểu cụ thể.

**Trả về:**
int - Một mã băm cho đối tượng hiện tại.