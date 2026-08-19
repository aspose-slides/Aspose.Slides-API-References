---
title: IMathAccentFactory
second_title: Aspose.Slides for Java API Reference
description: Stelt toe een wiskundig accent te maken
type: docs
url: /nl/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Stelt toe een wiskundig accent te maken

--------------------

Voor COM-compatibiliteit
## Methods

| Method | Description |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Creates a math accent applying to a specified math element with the default accent character value |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Creates a math accent applying to a specified math element |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```


Creates a math accent applying to a specified math element with the default accent character value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskundig element om accent toe te passen |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nieuw wiskundig accent
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Creates a math accent applying to a specified math element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskundig element om accent toe te passen |
| accentCharacter | char | accentteken |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nieuw wiskundig accent