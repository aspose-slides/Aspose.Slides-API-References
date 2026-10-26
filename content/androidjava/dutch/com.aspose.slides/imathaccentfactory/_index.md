---
title: IMathAccentFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Staat toe een wiskundig accent te maken
type: docs
url: /nl/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Staat toe een wiskundig accent te maken

--------------------

Voor COM-compatibiliteit
## Methoden

| Method | Description |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Maakt een wiskundig accent aan die wordt toegepast op een opgegeven wiskunde-element met de standaardaccent-tekenwaarde |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Maakt een wiskundig accent aan die wordt toegepast op een opgegeven wiskunde-element |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```


Maakt een wiskundig accent aan die wordt toegepast op een opgegeven wiskunde-element met de standaardaccent-tekenwaarde

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskunde-element om accent toe te passen |

**Retourwaarde:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nieuw wiskundig accent
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Maakt een wiskundig accent aan die wordt toegepast op een opgegeven wiskunde-element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskunde-element om accent toe te passen |
| accentCharacter | char | accent-teken |

**Retourwaarde:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nieuw wiskundig accent