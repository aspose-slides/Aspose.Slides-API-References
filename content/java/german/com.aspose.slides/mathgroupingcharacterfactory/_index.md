---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides für Java API Referenz
description: Ermöglicht das Erstellen eines mathematischen Gruppierungszeichens
type: docs
url: /de/com.aspose.slides/mathgroupingcharacterfactory/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

Ermöglicht das Erstellen eines mathematischen Gruppierungszeichens

--------------------

Für COM-Kompatibilität
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Erstellt ein mathematisches Gruppierungszeichen |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Erstellt ein mathematisches Gruppierungszeichen |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```


### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Erstellt ein mathematisches Gruppierungszeichen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathe-Element, auf das das Gruppierungszeichen angewendet wird |
| character | char | Gruppierungszeichen |
| position | int | Position des Gruppierungszeichens |
| verticalJustification | int | vertikale Ausrichtung |

**Rückgabewert:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - neues Gruppierungszeichenelement
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


Erstellt ein mathematisches Gruppierungszeichen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathe-Element, auf das das Gruppierungszeichen angewendet wird |

**Rückgabewert:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - neues Gruppierungszeichenelement