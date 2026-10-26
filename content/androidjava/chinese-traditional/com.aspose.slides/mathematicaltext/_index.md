---
title: MathematicalText
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 數學文字
type: docs
url: /zh-hant/com.aspose.slides/mathematicaltext/
---
**繼承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有已實作的介面:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

數學文字

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## 建構式

| 建構子 | 描述 |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | 預設建構式（建立 String.Empty 值） |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | 建立具有單一符號的 MathText |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | 從文字建立 MathematicalText |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | 從文字與格式設定建立 MathematicalText |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getValue()](#getValue--) | 文字值 |
| [setValue(String value)](#setValue-java.lang.String-) | 文字值 |
| [getFormat()](#getFormat--) | 文字格式屬性 |
| [getChildren()](#getChildren--) | 取得子元素 |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```

預設建構式（建立 String.Empty 值）

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

建立具有單一符號的 MathText

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| mathSymbol | char | 單一符號 |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```

從文字建立 MathematicalText

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 文字值 |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```

從文字與格式設定建立 MathematicalText

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 文字值 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | 文字格式設定 |

### getValue() {#getValue--}
```
public final String getValue()
```

文字值

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**傳回:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```

文字值

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```

文字格式屬性

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**傳回:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

取得子元素

**傳回:**
com.aspose.slides.IMathElement[]