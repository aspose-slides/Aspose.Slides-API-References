---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math border box
type: docs
url: /ar/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

يسمح بإنشاء صندوق حد رياضي

--------------------

لتوافق COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | إنشاء صندوق حد رياضي بتطبيقه على العنصر |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | إنشاء صندوق حد رياضي بتطبيقه على العنصر |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```


إنشاء صندوق حد رياضي بتطبيقه على العنصر

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي لتطبيق صندوق الحد |

**القيمة المرجعة:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - عنصر صندوق حد جديد
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


إنشاء صندوق حد رياضي بتطبيقه على العنصر

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي لتطبيق صندوق الحد |
| hideTop | boolean | إخفاء الحافة العليا |
| hideBottom | boolean | إخفاء الحافة السفلية |
| hideLeft | boolean | إخفاء الحافة اليسرى |
| hideRight | boolean | إخفاء الحافة اليمنى |
| strikethroughHorizontal | boolean | خط أفقي لصندوق الحد |
| strikethroughVertical | boolean | خط عمودي لصندوق الحد |
| strikethroughBottomLeftToTopRight | boolean | خط لصندوق الحد من أسفل اليسار إلى أعلى اليمين |
| strikethroughTopLeftToBottomRight | boolean | خط لصندوق الحد من أعلى اليسار إلى أسفل اليمين |

**القيمة المرجعة:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - عنصر صندوق حد جديد