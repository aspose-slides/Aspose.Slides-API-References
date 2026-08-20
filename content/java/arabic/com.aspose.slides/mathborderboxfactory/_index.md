---
title: MathBorderBoxFactory
second_title: مرجع API لـ Aspose.Slides لجافا
description: يسمح بإنشاء صندوق حد رياضي
type: docs
url: /ar/com.aspose.slides/mathborderboxfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

يسمح بإنشاء صندوق حد رياضي

--------------------

لتوافق COM
## المنشئات

| Constructor | Description |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## الطرق

| Method | Description |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | إنشاء صندوق حد رياضي بتطبيقه على العنصر |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | إنشاء صندوق حد رياضي بتطبيقه على العنصر |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


إنشاء صندوق حد رياضي بتطبيقه على العنصر

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي لتطبيق صندوق الحد |

**الإرجاع:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - عنصر صندوق حد جديد
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


إنشاء صندوق حد رياضي بتطبيقه على العنصر

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي لتطبيق صندوق الحد |
| hideTop | boolean | إخفاء الحافة العلوية |
| hideBottom | boolean | إخفاء الحافة السفلية |
| hideLeft | boolean | إخفاء الحافة اليسرى |
| hideRight | boolean | إخفاء الحافة اليمنى |
| strikethroughHorizontal | boolean | شطب أفقي لصندوق الحد |
| strikethroughVertical | boolean | شطب عمودي لصندوق الحد |
| strikethroughBottomLeftToTopRight | boolean | شطب من أسفل اليسار إلى أعلى اليمين لصندوق الحد |
| strikethroughTopLeftToBottomRight | boolean | شطب من أعلى اليسار إلى أسفل اليمين لصندوق الحد |

**الإرجاع:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - عنصر صندوق حد جديد