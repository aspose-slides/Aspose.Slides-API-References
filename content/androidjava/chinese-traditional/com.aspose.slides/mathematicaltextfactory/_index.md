---
title: MathematicalTextFactory
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 允許建立 MathematicalText 元素
type: docs
url: /zh-hant/com.aspose.slides/mathematicaltextfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

允許建立 MathematicalText 元素

--------------------

用於 COM 相容性
## Constructors

| Constructor | Description |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | 建立空的數學文字元素 |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | 建立具有指定值的數學文字元素 |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | 建立具有指定值的空白數學文字元素 |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | 建立具有指定值和格式屬性的空白數學文字元素 |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```

### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```

建立空的數學文字元素

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```

建立具有指定值的數學文字元素

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char | 作為文字值的單一符號 |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```

建立具有指定值的空白數學文字元素

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | 文字值 |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

建立具有指定值和格式屬性的空白數學文字元素

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | 文字值 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | 文字格式設定 |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text