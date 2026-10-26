---
title: IAlphaBiLevel
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثّل تأثير ألفا ذو مستويين.
type: docs
url: /ar/com.aspose.slides/ialphabilevel/
---
**كل الواجهات المنفذة:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

يمثل تأثير ألفا ذو مستويين. يتم تغيير قيم ألفا (العتامة) الأقل من العتبة إلى 0 (شفاف تمامًا) وقيم ألفا الأكبر من أو مساوية للعتبة إلى 100٪ (معتم تمامًا).

--------------------

استخدم ImageTransformOperationFactory لإنشاء مثيلات في COM.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getThreshold()](#getThreshold--) | إرجاع عتبة التأثير. |
| [setThreshold(float value)](#setThreshold-float-) | إرجاع عتبة التأثير. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

إرجاع عتبة التأثير. قراءة/كتابة float.

**الإرجاع:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

إرجاع عتبة التأثير. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |