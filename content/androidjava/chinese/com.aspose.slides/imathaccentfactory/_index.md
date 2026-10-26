---
title: IMathAccentFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math accent
type: docs
url: /zh/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

允许创建数学重音

--------------------

用于 COM 兼容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | 创建一个应用于指定数学元素的数学重音，使用默认的重音字符值 |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | 创建一个应用于指定数学元素的数学重音 |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```


创建一个应用于指定数学元素的数学重音，使用默认的重音字符值

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要应用重音的数学元素 |

**返回：**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新的数学重音
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


创建一个应用于指定数学元素的数学重音

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要应用重音的数学元素 |
| accentCharacter | char | 重音字符 |

**返回：**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新的数学重音