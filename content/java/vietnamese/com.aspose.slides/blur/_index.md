---
title: Blur
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một hiệu ứng Blur được áp dụng cho toàn bộ hình dạng, bao gồm cả phần nền.
type: docs
url: /vi/com.aspose.slides/blur/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Biểu diễn một hiệu ứng Blur được áp dụng cho toàn bộ hình dạng, bao gồm cả phần nền. Tất cả các kênh màu, bao gồm cả alpha, đều bị ảnh hưởng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRadius()](#getRadius--) | Trả về hoặc đặt bán kính mờ. |
| [setRadius(double value)](#setRadius-double-) | Trả về hoặc đặt bán kính mờ. |
| [getGrow()](#getGrow--) | Xác định xem biên của đối tượng có nên mở rộng do hiệu ứng mờ không. |
| [setGrow(boolean value)](#setGrow-boolean-) | Xác định xem biên của đối tượng có nên mở rộng do hiệu ứng mờ không. |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng Blur hiệu quả với kế thừa đã được áp dụng. |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem [Blur](../../com.aspose.slides/blur) được chỉ định có bằng với [Blur](../../com.aspose.slides/blur) hiện tại hay không. |
| [hashCode()](#hashCode--) | Đóng vai trò như hàm băm cho một kiểu cụ thể. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Trả về hoặc đặt bán kính mờ. Đọc/ghi double.

**Trả về:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Trả về hoặc đặt bán kính mờ. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```


Xác định xem biên của đối tượng có nên mở rộng do hiệu ứng mờ không. True chỉ ra biên được mở rộng trong khi false chỉ ra chúng không được mở rộng. Đọc/ghi boolean.

**Trả về:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```


Xác định xem biên của đối tượng có nên mở rộng do hiệu ứng mờ không. True chỉ ra biên được mở rộng trong khi false chỉ ra chúng không được mở rộng. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```


Lấy dữ liệu hiệu ứng Blur hiệu quả với kế thừa đã được áp dụng.

**Trả về:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - A [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Xác định xem [Blur](../../com.aspose.slides/blur) được chỉ định có bằng với [Blur](../../com.aspose.slides/blur) hiện tại hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | The [Blur](../../com.aspose.slides/blur) to compare. |

**Trả về:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Đóng vai trò như hàm băm cho một kiểu cụ thể.

**Trả về:**
int - A hash code for the current object.