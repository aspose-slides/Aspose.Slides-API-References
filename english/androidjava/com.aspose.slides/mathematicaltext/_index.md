---
title: MathematicalText
second_title: Aspose.Slides for Android via Java API Reference
description:  Mathematical text
type: docs
weight: 357
url: /androidjava/com.aspose.slides/mathematicaltext/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Mathematical text

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Default constructor (create String.Empty Value) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | Create MathText with single symbol |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | Create MathematicalText from text |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create MathematicalText from text and format settings |
## Methods

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | Text value |
| [setValue(String value)](#setValue-java.lang.String-) | Text value |
| [getFormat()](#getFormat--) | Text formatting properties |
| [getChildren()](#getChildren--) | Get children elements |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


Default constructor (create String.Empty Value)

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText();
> ```

### MathematicalText(char mathSymbol) {#MathematicalText-char-}
```
public MathematicalText(char mathSymbol)
```


Create MathText with single symbol

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char | single symbol |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


Create MathematicalText from text

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | text value |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


Create MathematicalText from text and format settings

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | text value |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | text format settings |

### getValue() {#getValue--}
```
public final String getValue()
```


Text value

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Text value

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


Text formatting properties

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Get children elements

**Returns:**
com.aspose.slides.IMathElement[]
