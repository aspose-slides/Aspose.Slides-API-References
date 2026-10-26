---
title: IFillOverlay
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل تأثير Fill Overlay.
type: docs
url: /ar/com.aspose.slides/ifilloverlay/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

يمثل تأثير Fill Overlay. يمكن استخدام Fill Overlay لتحديد تعبئة إضافية لكائن ومزج التعبئتين معًا.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |

### getBlend() {#getBlend--}
```
public abstract int getBlend()
```

FillBlendMode. قابل للقراءة/الكتابة [FillBlendMode](../../com.aspose.slides/fillblendmode).

**القيمة المرتجعة:**
int

### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```

FillBlendMode. قابل للقراءة/الكتابة [FillBlendMode](../../com.aspose.slides/fillblendmode).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Fill format. للقراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**القيمة المرتجعة:**
[IFillFormat](../../com.aspose.slides/ifillformat)