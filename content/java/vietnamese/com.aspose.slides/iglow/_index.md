---
title: IGlow
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn hiệu ứng Glow trong đó một đường viền mờ màu được thêm bên ngoài các cạnh của đối tượng.
type: docs
url: /vi/com.aspose.slides/iglow/
---
**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Biểu diễn hiệu ứng Glow, trong đó một đường viền mờ màu được thêm bên ngoài các cạnh của đối tượng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Color format. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Radius. Đọc/ghi double.

**Trả về:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Radius. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Color format. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)