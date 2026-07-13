---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides voor Android via Java API-referentie
description: Staat toe een wiskundig groepeerteken te maken
type: docs
url: /nl/com.aspose.slides/mathgroupingcharacterfactory/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

Staat toe een wiskundig groepeerteken te maken

--------------------

Voor COM-compatibiliteit
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Maakt een wiskundig groepeerteken |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Maakt een wiskundig groepeerteken |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```

### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Maakt een wiskundig groepeerteken

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskundig element om groepeerteken toe te passen |
| character | char | groepeerteken |
| position | int | positie van het groepeerteken |
| verticalJustification | int | verticale uitlijning |

**Retour:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nieuw groepeerkarakter-element
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Maakt een wiskundig groepeerteken

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskundig element om groepeerteken toe te passen |

**Retour:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nieuw groepeerkarakter-element