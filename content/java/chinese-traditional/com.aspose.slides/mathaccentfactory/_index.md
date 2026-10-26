---
title: MathAccentFactory
second_title: Aspose.Slides 的 Java API 參考
description: 允許建立數學重音
type: docs
url: /zh-hant/com.aspose.slides/mathaccentfactory/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)  
```
public class MathAccentFactory implements IMathAccentFactory
```

允許建立數學重音

--------------------

供 COM 相容性使用  
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | 建立一個套用於指定數學元素且使用預設重音字元的數學重音 |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | 建立一個套用於指定數學元素的數學重音 |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```

### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```

建立一個套用於指定數學元素且使用預設重音字元的數學重音

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用重音的數學元素 |

**返回：**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新的數學重音
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

建立一個套用於指定數學元素的數學重音

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用重音的數學元素 |
| accentCharacter | char | 重音字元 |

**返回：**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新的數學重音