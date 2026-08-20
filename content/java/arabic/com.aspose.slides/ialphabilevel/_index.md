---
title: IAlphaBiLevel
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل تأثير Alpha Bi-Level.
type: docs
url: /ar/com.aspose.slides/ialphabilevel/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

يمثل تأثير Alpha Bi-Level. قيم Alpha (Opacity) الأقل من الحد تُغيّر إلى 0 (شفاف تمامًا) وقيم Alpha الأكبر من أو المساوية للحد تُغيّر إلى 100٪ (معتم تمامًا).

--------------------

استخدم ImageTransformOperationFactory لإنشاء النسخ في COM.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getThreshold()](#getThreshold--) | يرجع حد التأثير. |
| [setThreshold(float value)](#setThreshold-float-) | يرجع حد التأثير. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

يرجع حد التأثير. قراءة/كتابة float.

**الإرجاع:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

يرجع حد التأثير. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |