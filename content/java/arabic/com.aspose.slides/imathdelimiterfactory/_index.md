---
title: IMathDelimiterFactory
second_title: Aspose.Slides لمرجع API الخاص بجافا
description: السماح بإنشاء فاصل رياضي
type: docs
url: /ar/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

السماح بإنشاء فاصل رياضي

--------------------

للتوافق مع COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | إنشاء فاصل رياضي بتطبيقه على العنصر |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | إنشاء فاصل رياضي بتطبيقه على العنصر |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

إنشاء فاصل رياضي بتطبيقه على العنصر

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي لتطبيق الفاصل |

**القيمة المرجعة:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - فاصل رياضي جديد
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

إنشاء فاصل رياضي بتطبيقه على العنصر

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | عناصر رياضية لتطبيق الفاصل |

**القيمة المرجعة:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - فاصل رياضي جديد