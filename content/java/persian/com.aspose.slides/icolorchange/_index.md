---
title: IColorChange
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر یک افکت تغییر رنگ است.
type: docs
url: /fa/com.aspose.slides/icolorchange/
---
**تمامی اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

نمایانگر افکت تغییر رنگ است. نمونه‌های FromColor با نمونه‌های ToColor جایگزین می‌شوند.
## متدها

| متد | توضیح |
| --- | --- |
| [getFromColor()](#getFromColor--) | رنگی که جایگزین خواهد شد. |
| [getToColor()](#getToColor--) | رنگی که جایگزین می‌شود. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```

رنگی که جایگزین خواهد شد. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```

رنگی که جایگزین می‌شود. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)