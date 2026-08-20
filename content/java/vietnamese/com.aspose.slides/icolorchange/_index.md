---
title: IColorChange
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho hiệu ứng Thay đổi màu.
type: docs
url: /vi/com.aspose.slides/icolorchange/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Đại diện cho hiệu ứng Thay đổi màu. Các thể hiện của FromColor được thay thế bằng các thể hiện của ToColor.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFromColor()](#getFromColor--) | Color sẽ được thay thế. |
| [getToColor()](#getToColor--) | Color sẽ thay thế. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```

Color sẽ được thay thế. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```

Color sẽ thay thế. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)