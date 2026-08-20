---
title: IColorChange
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للجاوا
description: يمثل تأثير تغيير اللون.
type: docs
url: /ar/com.aspose.slides/icolorchange/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

يمثل تأثير تغيير اللون. يتم استبدال كائنات FromColor بكائنات ToColor.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFromColor()](#getFromColor--) | اللون الذي سيستبدل. |
| [getToColor()](#getToColor--) | اللون الذي سيستبدل به. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```

اللون الذي سيستبدل. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```

اللون الذي سيستبدل به. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)