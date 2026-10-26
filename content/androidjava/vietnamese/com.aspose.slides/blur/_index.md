---
title: Blur
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho hiệu ứng Làm mờ được áp dụng cho toàn bộ hình dạng, bao gồm cả phần tô màu.
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

Đại diện cho hiệu ứng làm mờ được áp dụng cho toàn bộ hình dạng, bao gồm cả phần tô màu của nó. Tất cả các kênh màu, bao gồm cả alpha, đều bị ảnh hưởng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRadius()](#getRadius--) | Trả về hoặc đặt bán kính làm mờ. |
| [setRadius(double value)](#setRadius-double-) | Trả về hoặc đặt bán kính làm mờ. |
| [getGrow()](#getGrow--) | Xác định xem giới hạn của đối tượng có nên được mở rộng do hiệu ứng làm mờ hay không. |
| [setGrow(boolean value)](#setGrow-boolean-) | Xác định xem giới hạn của đối tượng có nên được mở rộng do hiệu ứng làm mờ hay không. |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng Blur thực tế với kế thừa đã được áp dụng. |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem [Blur](../../com.aspose.slides/blur) được chỉ định có bằng với [Blur](../../com.aspose.slides/blur) hiện tại hay không. |
| [hashCode()](#hashCode--) | Hoạt động như một hàm băm cho một kiểu cụ thể. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Trả về hoặc đặt bán kính làm mờ. Đọc/ghi double.

**Trả về:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Trả về hoặc đặt bán kính làm mờ. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```


Xác định xem giới hạn của đối tượng có nên được mở rộng do hiệu ứng làm mờ hay không. True cho biết giới hạn được mở rộng, trong khi false cho biết không được mở rộng. Đọc/ghi boolean.

**Trả về:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```


Xác định xem giới hạn của đối tượng có nên được mở rộng do hiệu ứng làm mờ hay không. True cho biết giới hạn được mở rộng, trong khi false cho biết không được mở rộng. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```


Lấy dữ liệu hiệu ứng Blur thực tế với kế thừa đã được áp dụng.

**Trả về:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - Một [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Xác định xem [Blur](../../com.aspose.slides/blur) được chỉ định có bằng với [Blur](../../com.aspose.slides/blur) hiện tại hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | Đối tượng [Blur](../../com.aspose.slides/blur) để so sánh. |

**Trả về:**
boolean - true nếu các đối tượng bằng nhau; ngược lại, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hoạt động như một hàm băm cho một kiểu cụ thể.

**Trả về:**
int - Một mã băm cho đối tượng hiện tại.