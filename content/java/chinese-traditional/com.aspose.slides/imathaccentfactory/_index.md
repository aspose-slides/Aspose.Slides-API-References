---
title: IMathAccentFactory
second_title: Aspose.Slides for Java API Reference
description: 允許建立數學變音
type: docs
url: /zh-hant/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

允許建立數學變音

--------------------

供 COM 相容性
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | 建立一個套用於指定數學元素的變音，使用預設的變音字元值 |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | 建立一個套用於指定數學元素的變音 |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```


建立一個套用於指定數學元素的變音，使用預設的變音字元值

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用變音的數學元素 |

**傳回值：**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新的數學變音
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


建立一個套用於指定數學元素的變音

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用變音的數學元素 |
| accentCharacter | char | 變音字元 |

**傳回值：**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新的數學變音