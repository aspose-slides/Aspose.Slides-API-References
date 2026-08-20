---
title: IMathLimitFactory
second_title: Aspose.Slides for Java API Reference
description: يتيح إنشاء IMathLimit
type: docs
url: /ar/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

يتيح إنشاء IMathLimit

--------------------

للتوافق مع COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Creates IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathLimit with limit at the bottom |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


ينشئ IMathLimit

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Base argument to apply the limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit element |
| upperLimit | boolean | يحدد وضع الحد في الأعلى |

**القيمة المرجعة:**
[IMathLimit](../../com.aspose.slides/imathlimit) - حد رياضي جديد
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


ينشئ IMathLimit مع الحد في الأسفل

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Base argument to apply the limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit element |

**القيمة المرجعة:**
[IMathLimit](../../com.aspose.slides/imathlimit) - حد رياضي جديد