---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att skapa ett matematiskt grupperingstecken
type: docs
url: /sv/com.aspose.slides/mathgroupingcharacterfactory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

Tillåter att skapa ett matematiskt grupperingstecken

--------------------

För COM-kompatibilitet
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Skapar ett matematiskt grupperingstecken |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Skapar ett matematiskt grupperingstecken |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```

### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Skapar ett matematiskt grupperingstecken

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematiskt element för att applicera grupperingstecken |
| character | char | grupperingstecken |
| position | int | position för grupperingstecken |
| verticalJustification | int | vertikal justering |

**Returnerar:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nytt grupperingstecken-element
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Skapar ett matematiskt grupperingstecken

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematiskt element för att applicera grupperingstecken |

**Returnerar:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nytt grupperingstecken-element