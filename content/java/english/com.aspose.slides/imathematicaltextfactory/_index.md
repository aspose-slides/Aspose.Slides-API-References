---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a MathematicalText element
type: docs
weight: 924
url: /com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Allows to create a MathematicalText element

--------------------

For COM comparibility
## Methods

| Method | Description |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Create empty mathematical text element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Create mathematical text element with the specified value |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Create empty mathematical text element with the specified value |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create empty mathematical text element with the specified value and formatting properties |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


Create empty mathematical text element

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


Create mathematical text element with the specified value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char | single symbol to use as text value |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


Create empty mathematical text element with the specified value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | text value |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Create empty mathematical text element with the specified value and formatting properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | text value |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | text format settings |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
