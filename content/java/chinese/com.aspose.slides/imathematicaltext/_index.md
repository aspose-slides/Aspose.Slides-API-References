---
title: IMathematicalText
second_title: Aspose.Slides for Java API 参考
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
## 方法

| 方法 | 描述 |
| --- | --- |
| [getValue()](#getValue--) | 文本值 |
| [setValue(String value)](#setValue-java.lang.String-) | 文本值 |
| [getFormat()](#getFormat--) | 文本格式属性 |
### getValue() {#getValue--}
```
public abstract String getValue()
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
public abstract void setValue(String value)
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
public abstract IPortionFormat getFormat()
```


文本格式属性

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**返回：**
[IPortionFormat](../../com.aspose.slides/iportionformat)