---
title: IFillOverlay
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل تأثير تعبئة تراكبي.
type: docs
url: /ar/com.aspose.slides/ifilloverlay/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

يمثل تأثير تعبئة تراكبي. يمكن استخدام تعبئة تراكبي لتحديد تعبئة إضافية لكائن ودمج التعبئتين معًا.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | تنسيق التعبئة. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```

FillBlendMode. قراءة/كتابة [FillBlendMode](../../com.aspose.slides/fillblendmode).

**القيمة المرجعة:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```

FillBlendMode. قراءة/كتابة [FillBlendMode](../../com.aspose.slides/fillblendmode).

**المعاملات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

تنسيق التعبئة. للقراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**القيمة المرجعة:**
[IFillFormat](../../com.aspose.slides/ifillformat)