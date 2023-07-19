---
title: MathLimitFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create IMathLimit
type: docs
weight: 341
url: /java/com.aspose.slides/mathlimitfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

Allows to create IMathLimit

--------------------

For COM comparibility
## Constructors

| Constructor | Description |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Creates IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathLimit with limit at the bottom |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Creates IMathLimit

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Base argument to apply the limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit element |
| upperLimit | boolean | Sets the placement of the limit on top |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - new math limit
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Creates IMathLimit with limit at the bottom

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Base argument to apply the limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit element |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - new math limit
