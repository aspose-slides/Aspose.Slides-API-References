---
title: IBlur
second_title: Tham khảo API Aspose.Slides cho Java
description: Biểu diễn một hiệu ứng Blur được áp dụng cho toàn bộ hình dạng, bao gồm cả phần nền.
type: docs
url: /vi/com.aspose.slides/iblur/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Biểu diễn một hiệu ứng Blur được áp dụng cho toàn bộ hình dạng, bao gồm cả phần nền. Tất cả các kênh màu, bao gồm cả alpha, đều bị ảnh hưởng.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRadius()](#getRadius--) | Trả về hoặc đặt bán kính mờ. |
| [setRadius(double value)](#setRadius-double-) | Trả về hoặc đặt bán kính mờ. |
| [getGrow()](#getGrow--) | Xác định liệu giới hạn của đối tượng có nên được mở rộng do hiệu ứng mờ hay không. |
| [setGrow(boolean value)](#setGrow-boolean-) | Xác định liệu giới hạn của đối tượng có nên được mở rộng do hiệu ứng mờ hay không. |

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

Xác định liệu giới hạn của đối tượng có nên được mở rộng do hiệu ứng mờ hay không. True cho thấy giới hạn được mở rộng trong khi false cho thấy chúng không được mở rộng. Đọc/ghi boolean.

**Trả về:**
boolean

### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Xác định liệu giới hạn của đối tượng có nên được mở rộng do hiệu ứng mờ hay không. True cho thấy giới hạn được mở rộng trong khi false cho thấy chúng không được mở rộng. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |