---
title: IMathFunctionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math function
type: docs
weight: 901
url: /com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Allows to create a math function

--------------------

For COM comparibility
## Methods

| Method | Description |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates math function |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Creates math function |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Creates math function

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Element used as a function name |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Element used as a function argument |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - new math function
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Creates math function

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| funcName | java.lang.String | Function name |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Element used as a function argument |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - new math function
