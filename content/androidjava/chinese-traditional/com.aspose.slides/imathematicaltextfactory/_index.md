---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 允許建立 MathematicalText 元素
type: docs
url: /zh-hant/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

允許建立 MathematicalText 元素

--------------------

用於 COM 相容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | 建立空的 MathematicalText 元素 |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | 建立具有指定值的 MathematicalText 元素 |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | 建立具有指定值的空的 MathematicalText 元素 |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | 建立具有指定值和格式屬性的空的 MathematicalText 元素 |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


建立空的 MathematicalText 元素

**返回:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


建立具有指定值的 MathematicalText 元素

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| mathSymbol | char | 單一符號作為文字值 |

**返回:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


建立具有指定值的空的 MathematicalText 元素

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 文字值 |

**返回:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


建立具有指定值和格式屬性的空的 MathematicalText 元素

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 文字值 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | 文字格式設定 |

**返回:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text