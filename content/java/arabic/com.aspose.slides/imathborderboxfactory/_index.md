---
title: IMathBorderBoxFactory
second_title: Aspose.Slides لواجهة برمجة تطبيقات Java
description: يسمح بإنشاء مربع حد رياضي
type: docs
url: /ar/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

يسمح بإنشاء مربع حد رياضي

--------------------

للتوافق مع COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | إنشاء مربع حد رياضي عن طريق تطبيقه على العنصر |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | إنشاء مربع حد رياضي عن طريق تطبيقه على العنصر |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```


إنشاء مربع حد رياضي عن طريق تطبيقه على العنصر

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element رياضي لتطبيق مربع الحد |

**القيمة المرجعة:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - new border box element
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


إنشاء مربع حد رياضي عن طريق تطبيقه على العنصر

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element رياضي لتطبيق مربع الحد |
| hideTop | boolean | إخفاء الحافة العلوية |
| hideBottom | boolean | إخفاء الحافة السفلية |
| hideLeft | boolean | إخفاء الحافة اليسرى |
| hideRight | boolean | إخفاء الحافة اليمنى |
| strikethroughHorizontal | boolean | شريط عرضي أفقي لمربع الحد |
| strikethroughVertical | boolean | شريط عرضي عمودي لمربع الحد |
| strikethroughBottomLeftToTopRight | boolean | شريط عرضي من الزاوية السفلية اليسرى إلى العليا اليمنى |
| strikethroughTopLeftToBottomRight | boolean | شريط عرضي من الزاوية العلوية اليسرى إلى السفلية اليمنى |

**القيمة المرجعة:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - new border box element