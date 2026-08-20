---
title: MathLimitFactory
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة Java
description: يسمح بإنشاء IMathLimit
type: docs
url: /ar/com.aspose.slides/mathlimitfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المطبقة:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

يسمح بإنشاء IMathLimit

--------------------

للتوافق مع COM
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | ينشئ IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ IMathLimit مع الحد في الأسفل |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


ينشئ IMathLimit

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | معامل أساسي لتطبيق الحد |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | عنصر الحد |
| upperLimit | boolean | يضبط موضع الحد في الأعلى |

**القيمة المرجعة:**
[IMathLimit](../../com.aspose.slides/imathlimit) - حد رياضي جديد
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


ينشئ IMathLimit مع الحد في الأسفل

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | معامل أساسي لتطبيق الحد |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | عنصر الحد |

**القيمة المرجعة:**
[IMathLimit](../../com.aspose.slides/imathlimit) - حد رياضي جديد