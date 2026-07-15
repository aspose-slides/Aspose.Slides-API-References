---
title: IMathAccentFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math accent
type: docs
url: /zh-hant/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

允許建立數學重音

--------------------

供 COM 相容性
## Methods

| Method | Description |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | 建立一個使用預設重音字元值並套用於指定數學元素的數學重音 |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | 建立一個套用於指定數學元素的數學重音 |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

建立一個使用預設重音字元值並套用於指定數學元素的數學重音

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用重音的數學元素 |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新的數學重音
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

建立一個套用於指定數學元素的數學重音

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用重音的數學元素 |
| accentCharacter | char | 重音字元 |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新的數學重音