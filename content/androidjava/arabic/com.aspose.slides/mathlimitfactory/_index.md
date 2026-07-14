---
title: MathLimitFactory
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يسمح بإنشاء IMathLimit
type: docs
url: /ar/com.aspose.slides/mathlimitfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

السماح بإنشاء IMathLimit

--------------------

للتوافق مع COM
## المنشئون

| المنشئ | الوصف |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | يُنشئ IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | يُنشئ IMathLimit بالحد في الأسفل |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


يُنشئ IMathLimit

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | الوسيط الأساسي لتطبيق الحد |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | عنصر الحد |
| upperLimit | boolean | يحدد وضعية الحد في الأعلى |

**الإرجاع:**
[IMathLimit](../../com.aspose.slides/imathlimit) - حد رياضي جديد
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


يُنشئ IMathLimit بالحد في الأسفل

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | الوسيط الأساسي لتطبيق الحد |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | عنصر الحد |

**الإرجاع:**
[IMathLimit](../../com.aspose.slides/imathlimit) - حد رياضي جديد