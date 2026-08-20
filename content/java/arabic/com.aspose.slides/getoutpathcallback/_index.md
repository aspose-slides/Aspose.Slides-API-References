---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /ar/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | سيتم استدعاء رد النداء لكل [Slide](../../com.aspose.slides/slide)، من المتوقع إرجاع مسار الإخراج. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```

سيتم استدعاء رد النداء لكل [Slide](../../com.aspose.slides/slide)، من المتوقع إرجاع مسار الإخراج.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | الشريحة الحالية المتكررة |
| index | int | فهرس الشريحة الحالية |

**القيمة المرجعة:**
java.lang.String