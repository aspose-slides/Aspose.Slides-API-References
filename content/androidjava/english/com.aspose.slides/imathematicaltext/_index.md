---
title: IMathematicalText
second_title: Aspose.Slides for Android via Java API Reference
description: Mathematical text
type: docs
url: /com.aspose.slides/imathematicaltext/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

Mathematical text

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## Methods

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | Text value |
| [setValue(String value)](#setValue-java.lang.String-) | Text value |
| [getFormat()](#getFormat--) | Text formatting properties |
### getValue() {#getValue--}
```
public abstract String getValue()
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
public abstract void setValue(String value)
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
public abstract IPortionFormat getFormat()
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
