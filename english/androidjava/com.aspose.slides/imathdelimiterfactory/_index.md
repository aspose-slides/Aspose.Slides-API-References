---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Android via Java API Reference
description:  Allows to create a math delimiter
type: docs
weight: 891
url: /androidjava/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Allows to create a math delimiter

--------------------

For COM comparibility
## Methods

| Method | Description |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Create a math delimiter by applying to the element |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Create a math delimiter by applying to the element |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
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
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```


Create a math delimiter by applying to the element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | math elements to apply delimiter |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - new math delimiter
