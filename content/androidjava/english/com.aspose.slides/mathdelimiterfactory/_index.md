---
title: MathDelimiterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math delimiter
type: docs
url: /com.aspose.slides/mathdelimiterfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathDelimiterFactory](../../com.aspose.slides/imathdelimiterfactory)
```
public class MathDelimiterFactory implements IMathDelimiterFactory
```

Allows to create a math delimiter

--------------------

For COM comparibility
## Constructors

| Constructor | Description |
| --- | --- |
| [MathDelimiterFactory()](#MathDelimiterFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Create a math delimiter by applying to the element |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Create a math delimiter by applying to the element |
### MathDelimiterFactory() {#MathDelimiterFactory--}
```
public MathDelimiterFactory()
```


### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public final IMathDelimiter createMathDelimiter(IMathElement element)
```


Create a math delimiter by applying to the element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply delimiter |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - new math delimiter
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public final IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```


Create a math delimiter by applying to the element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | math elements to apply delimiter |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - new math delimiter
