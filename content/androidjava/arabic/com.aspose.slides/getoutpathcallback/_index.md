---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /ar/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | ستتم استدعاء رد النداء لكل [Slide](../../com.aspose.slides/slide)، من المتوقع إرجاع مسار الإخراج. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```


ستتم استدعاء رد النداء لكل [Slide](../../com.aspose.slides/slide)، من المتوقع إرجاع مسار الإخراج.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | الشريحة الحالية المتكررة |
| index | int | فهرس الشريحة الحالية |

**القيمة المرجعة:**
java.lang.String