---
title: IBlur
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu thị hiệu ứng Làm mờ được áp dụng cho toàn bộ hình dạng, bao gồm cả phần tô.
type: docs
url: /vi/com.aspose.slides/iblur/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Biểu thị một hiệu ứng Làm mờ được áp dụng cho toàn bộ hình dạng, bao gồm cả phần tô. Tất cả các kênh màu, bao gồm cả alpha, đều bị ảnh hưởng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRadius()](#getRadius--) | Trả về hoặc đặt bán kính mờ. |
| [setRadius(double value)](#setRadius-double-) | Trả về hoặc đặt bán kính mờ. |
| [getGrow()](#getGrow--) | Xác định liệu giới hạn của đối tượng có nên mở rộng do hiệu ứng làm mờ hay không. |
| [setGrow(boolean value)](#setGrow-boolean-) | Xác định liệu giới hạn của đối tượng có nên mở rộng do hiệu ứng làm mờ hay không. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Trả về hoặc đặt bán kính mờ. Đọc/ghi double.

**Trả về:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Trả về hoặc đặt bán kính mờ. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Xác định liệu giới hạn của đối tượng có nên mở rộng do hiệu ứng làm mờ hay không. True chỉ ra rằng giới hạn được mở rộng trong khi false chỉ ra rằng chúng không được mở rộng. Đọc/ghi boolean.

**Trả về:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Xác định liệu giới hạn của đối tượng có nên mở rộng do hiệu ứng làm mờ hay không. True chỉ ra rằng giới hạn được mở rộng trong khi false chỉ ra rằng chúng không được mở rộng. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |