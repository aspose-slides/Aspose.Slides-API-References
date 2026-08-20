---
title: IMathematicalTextFactory
second_title: Aspose.Slides 的 Java API 參考
description: 允許建立一個 MathematicalText 元素
type: docs
url: /zh-hant/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

允許建立一個 MathematicalText 元素

--------------------

用於 COM 相容性
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | 建立空的 MathematicalText 元素 |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | 建立具有指定值的 MathematicalText 元素 |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | 建立具有指定值的空的 MathematicalText 元素 |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | 建立具有指定值與格式屬性的空的 MathematicalText 元素 |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

建立空的 MathematicalText 元素

**返回：**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 新的 Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

建立具有指定值的 MathematicalText 元素

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathSymbol | char | 用作文字值的單一符號 |

**返回：**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 新的 Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

建立具有指定值的空的 MathematicalText 元素

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathText | java.lang.String | 文字值 |

**返回：**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 新的 Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

建立具有指定值與格式屬性的空的 MathematicalText 元素

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathText | java.lang.String | 文字值 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | 文字格式設定 |

**返回：**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 新的 Mathematical Text