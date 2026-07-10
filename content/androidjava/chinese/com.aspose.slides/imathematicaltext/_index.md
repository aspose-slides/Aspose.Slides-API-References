---
title: IMathematicalText
second_title: Aspose.Slides for Android via Java API 参考
description: 数学文本
type: docs
url: /zh/com.aspose.slides/imathematicaltext/
---
**所有实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

数学文本
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


文本格式属性
--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
>  ```

**返回：**
[IPortionFormat](../../com.aspose.slides/iportionformat)