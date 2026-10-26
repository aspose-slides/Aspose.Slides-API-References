---
title: MathematicalText
second_title: Aspose.Slides for Java API 参考
description: 数学文本
type: docs
url: /zh/com.aspose.slides/mathematicaltext/
---
**继承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**实现的所有接口：**
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
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | 默认构造函数（创建 String.Empty 值） |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | 使用单个符号创建 MathText |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | 从文本创建 MathematicalText |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | 从文本和格式设置创建 MathematicalText |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getValue()](#getValue--) | 文本值 |
| [setValue(String value)](#setValue-java.lang.String-) | 文本值 |
| [getFormat()](#getFormat--) | 文本格式属性 |
| [getChildren()](#getChildren--) | 获取子元素 |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


默认构造函数（创建 String.Empty 值）

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


使用单个符号创建 MathText

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathSymbol | char | 单个符号 |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


从文本创建 MathematicalText

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 文本值 |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


从文本和格式设置创建 MathematicalText

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 文本值 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | 文本格式设置 |

### getValue() {#getValue--}
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

**返回值：**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


文本值

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


文本格式属性

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**返回值：**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


获取子元素

**返回值：**
com.aspose.slides.IMathElement[]