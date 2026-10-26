---
title: IColorChange
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn hiệu ứng Thay đổi màu.
type: docs
url: /vi/com.aspose.slides/icolorchange/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Biểu diễn hiệu ứng Thay đổi màu. Các thể hiện của FromColor được thay thế bằng các thể hiện của ToColor.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFromColor()](#getFromColor--) | Màu sẽ được thay thế. |
| [getToColor()](#getToColor--) | Màu sẽ thay thế. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```


Màu sẽ được thay thế. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


Màu sẽ thay thế. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)