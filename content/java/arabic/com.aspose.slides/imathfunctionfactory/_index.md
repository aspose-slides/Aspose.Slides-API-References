---
title: IMathFunctionFactory
second_title: Aspose.Slides for Java مرجع API
description: يسمح بإنشاء دالة رياضية
type: docs
url: /ar/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

يسمح بإنشاء دالة رياضية

--------------------

لتوافق COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ دالة رياضية |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | ينشئ دالة رياضية |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```

ينشئ دالة رياضية

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | العنصر المستخدم كاسم للوظيفة |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | العنصر المستخدم كمعامل للوظيفة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - دالة رياضية جديدة
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```

ينشئ دالة رياضية

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| funcName | java.lang.String | اسم الدالة |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | العنصر المستخدم كمعامل للوظيفة |

**الإرجاع:**
[IMathFunction](../../com.aspose.slides/imathfunction) - دالة رياضية جديدة