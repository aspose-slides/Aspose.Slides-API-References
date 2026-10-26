---
title: IMathematicalText
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 數學文字
type: docs
url: /zh-hant/com.aspose.slides/imathematicaltext/
---
**所有已實作的介面：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

數學文字

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## 方法

| 方法 | 說明 |
| --- | --- |
| [getValue()](#getValue--) | 文字值 |
| [setValue(String value)](#setValue-java.lang.String-) | 文字值 |
| [getFormat()](#getFormat--) | 文字格式屬性 |
### getValue() {#getValue--}
```
public abstract String getValue()
```


文字值

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**傳回值：**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public abstract void setValue(String value)
```


文字值

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IPortionFormat getFormat()
```


文字格式屬性

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
>  ```

**傳回值：**
[IPortionFormat](../../com.aspose.slides/iportionformat)