---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Tillåter att skapa ett matematiskt grupperingstecken
type: docs
url: /sv/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Tillåter att skapa ett matematiskt grupperingstecken

--------------------

För COM-kompatibilitet
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Skapar ett matematiskt grupperingstecken |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Skapar ett matematiskt grupperingstecken |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Skapar ett matematiskt grupperingstecken

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | mattelement att tillämpa grupperingstecken på |
| character | char | grupperingstecken |
| position | int | position för grupperingstecken |
| verticalJustification | int | vertikal justering |

**Returnerar:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nytt grupperingstecken-element
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


Skapar ett matematiskt grupperingstecken

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | mattelement att tillämpa grupperingstecken på |

**Returnerar:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nytt grupperingstecken-element