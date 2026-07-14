---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 수학 구분자를 만들 수 있습니다
type: docs
url: /ko/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

수학 구분자를 만들 수 있습니다

--------------------

COM 호환성을 위해
## Methods

| Method | Description |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Create a math delimiter by applying to the element |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Create a math delimiter by applying to the element |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```


요소에 적용하여 수학 구분자를 생성합니다

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


요소에 적용하여 수학 구분자를 생성합니다

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | math elements to apply delimiter |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - new math delimiter