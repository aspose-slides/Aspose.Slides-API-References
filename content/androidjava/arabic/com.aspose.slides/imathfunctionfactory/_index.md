---
title: IMathFunctionFactory
second_title: Aspose.Slides لـ Android عبر مرجع API لجافا
description: يسمح بإنشاء دالة رياضية
type: docs
url: /ar/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

يسمح بإنشاء دالة رياضية

--------------------

للتوافق مع COM
## Methods

| Method | Description |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ دالة رياضية |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | ينشئ دالة رياضية |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```

ينشئ دالة رياضية

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | العنصر المستخدم كاسم الدالة |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | العنصر المستخدم كمعامل للدالة |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - دالة رياضية جديدة
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```

ينشئ دالة رياضية

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| funcName | java.lang.String | اسم الدالة |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | العنصر المستخدم كمعامل للدالة |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - دالة رياضية جديدة