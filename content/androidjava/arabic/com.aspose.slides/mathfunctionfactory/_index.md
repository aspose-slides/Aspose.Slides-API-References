---
title: MathFunctionFactory
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: يسمح بإنشاء دالة رياضية
type: docs
url: /ar/com.aspose.slides/mathfunctionfactory/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)  
```
public class MathFunctionFactory implements IMathFunctionFactory
```

يسمح بإنشاء دالة رياضية

--------------------

للتوافق مع COM
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ دالة رياضية |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | ينشئ دالة رياضية |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```

### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```

ينشئ دالة رياضية

**المعلمات:**
| المعامِل | النوع | الوصف |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | العنصر المستخدم كاسم للدالة |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | العنصر المستخدم كمعامل للدالة |

**القيمة المرجعة:**
[IMathFunction](../../com.aspose.slides/imathfunction) - دالة رياضية جديدة
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```

ينشئ دالة رياضية

**المعلمات:**
| المعامِل | النوع | الوصف |
| --- | --- | --- |
| funcName | java.lang.String | اسم الدالة |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | العنصر المستخدم كمعامل للدالة |

**القيمة المرجعة:**
[IMathFunction](../../com.aspose.slides/imathfunction) - دالة رياضية جديدة