---
title: MathematicalTextFactory
second_title: Aspose.Slides for Java API 參考
description: 允許建立 MathematicalText 元素
type: docs
url: /zh-hant/com.aspose.slides/mathematicaltextfactory/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

允許建立 MathematicalText 元素

--------------------

供 COM 相容性使用
## 建構子

| 建構子 | 描述 |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Create empty mathematical text element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Create mathematical text element with the specified value |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Create empty mathematical text element with the specified value |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create empty mathematical text element with the specified value and formatting properties |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```


### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```


建立空的數學文字元素

**傳回值:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```


建立具有指定值的數學文字元素

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| mathSymbol | char | 要用作文字值的單一符號 |

**傳回值：**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```


建立具有指定值的空數學文字元素

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 文字值 |

**傳回值：**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


建立具有指定值與格式屬性的空數學文字元素

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 文字值 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | 文字格式設定 |

**傳回值：**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text