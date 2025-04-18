---
title: MathAccentFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math accent
type: docs
url: /com.aspose.slides/mathaccentfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Allows to create a math accent

--------------------

For COM comparibility
## Constructors

| Constructor | Description |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Methods

| Method | Description |
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


Creates a math accent applying to a specified math element with the default accent character value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply accent |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - new math accent
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Creates a math accent applying to a specified math element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply accent |
| accentCharacter | char | accent character |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - new math accent
