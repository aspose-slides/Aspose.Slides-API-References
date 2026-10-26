---
title: MathAccentFactory
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 允許建立數學重音
type: docs
url: /zh-hant/com.aspose.slides/mathaccentfactory/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

允許建立數學重音

--------------------

用於 COM 相容性
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | 創建套用預設重音字元值於指定數學元素的數學重音 |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | 創建套用於指定數學元素的數學重音 |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


創建套用預設重音字元值於指定數學元素的數學重音

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用重音的數學元素 |

**傳回值：**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新的數學重音
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


創建套用於指定數學元素的數學重音

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用重音的數學元素 |
| accentCharacter | char | 重音字元 |

**傳回值：**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新的數學重音