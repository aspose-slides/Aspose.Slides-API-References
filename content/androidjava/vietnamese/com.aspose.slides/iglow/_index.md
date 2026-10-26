---
title: IGlow
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn hiệu ứng Glow trong đó một viền mờ màu được thêm ra ngoài các cạnh của đối tượng.
type: docs
url: /vi/com.aspose.slides/iglow/
---
**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Biểu diễn hiệu ứng Glow, trong đó một viền mờ màu được thêm ra ngoài các cạnh của đối tượng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRadius()](#getRadius--) | Bán kính. |
| [setRadius(double value)](#setRadius-double-) | Bán kính. |
| [getColor()](#getColor--) | Định dạng màu. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Bán kính. Đọc/ghi double.

**Trả về:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Bán kính. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Định dạng màu. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)