---
title: IMathLimitFactory
second_title: Aspose.Slides for Android عبر مرجع API لجافا
description: يسمح بإنشاء IMathLimit
type: docs
url: /ar/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

يسمح بإنشاء IMathLimit

--------------------

لتوافق COM
## طرق

| الطريقة | الوصف |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | ينشئ IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ IMathLimit مع حد في الأسفل |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


ينشئ IMathLimit

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | المعامل الأساسي لتطبيق الحد |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | عنصر الحد |
| upperLimit | boolean | يحدد موضع الحد في الأعلى |

**القيمة المرجعة:**
[IMathLimit](../../com.aspose.slides/imathlimit) - حد رياضي جديد
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


ينشئ IMathLimit مع حد في الأسفل

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | المعامل الأساسي لتطبيق الحد |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | عنصر الحد |

**القيمة المرجعة:**
[IMathLimit](../../com.aspose.slides/imathlimit) - حد رياضي جديد