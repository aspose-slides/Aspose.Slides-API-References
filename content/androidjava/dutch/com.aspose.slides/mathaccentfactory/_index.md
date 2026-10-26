---
title: MathAccentFactory
second_title: Aspose.Slides voor Android via Java API-referentie
description: Staat het maken van een wiskundig accent toe
type: docs
url: /nl/com.aspose.slides/mathaccentfactory/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Staat het maken van een wiskundig accent toe

--------------------

Voor COM-compatibiliteit
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Methods

| Method | Beschrijving |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Maakt een wiskundig accent aan dat wordt toegepast op een opgegeven wiskundig element met de standaard accenttekenwaarde |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Maakt een wiskundig accent aan dat wordt toegepast op een opgegeven wiskundig element |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


Maakt een wiskundig accent aan dat wordt toegepast op een opgegeven wiskundig element met de standaard accenttekenwaarde

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskundig element waarop het accent wordt toegepast |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nieuw wiskundig accent
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Maakt een wiskundig accent aan dat wordt toegepast op een opgegeven wiskundig element

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskundig element waarop het accent wordt toegepast |
| accentCharacter | char | accentteken |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nieuw wiskundig accent