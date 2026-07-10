---
title: MathematicalText
second_title: Aspose.Slides for Android via Java API 参考
description: 数学文本
type: docs
url: /zh/com.aspose.slides/mathematicaltext/
---
**继承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有实现的接口：**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

数学文本

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
从文本和格式设置创建 MathematicalText

--------------------

> ```
> 示例：
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | 文本值 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | 文本格式设置 |
```
public final String getValue()
```

文本值

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**返回：**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```

文本值

--------------------

> ```
> 示例：
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```

文本格式属性

--------------------

> ```
> 示例：
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
>  ```

**返回：**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()

获取子元素

**返回：**
com.aspose.slides.IMathElement[]