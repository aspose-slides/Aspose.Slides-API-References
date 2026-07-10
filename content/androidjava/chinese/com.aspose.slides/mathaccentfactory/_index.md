---
title: MathAccentFactory
second_title: Aspose.Slides for Android via Java API 参考
description: 允许创建数学重音
type: docs
url: /zh/com.aspose.slides/mathaccentfactory/
---
**继承:**  
java.lang.Object

**全部实现的接口:**  
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)  
```
public class MathAccentFactory implements IMathAccentFactory
```

允许创建数学重音

--------------------

用于 COM 兼容性  
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Creates a math accent applying to a specified math element with the default accent character value |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Creates a math accent applying to a specified math element |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```

### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```

创建一个应用于指定数学元素的数学重音，使用默认的重音字符值

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要应用重音的数学元素 |

**返回值:**  
[IMathAccent](../../com.aspose.slides/imathaccent) - 新的数学重音
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

创建一个应用于指定数学元素的数学重音

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要应用重音的数学元素 |
| accentCharacter | char | 重音字符 |

**返回值:**  
[IMathAccent](../../com.aspose.slides/imathaccent) - 新的数学重音