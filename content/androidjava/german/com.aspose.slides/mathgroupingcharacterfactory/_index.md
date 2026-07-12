---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides für Android über die Java-API-Referenz
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

Ermöglicht das Erzeugen eines mathematischen Gruppierungszeichens

--------------------

Für COM-Kompatibilität
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Erzeugt ein mathematisches Gruppierungszeichen |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Erzeugt ein mathematisches Gruppierungszeichen |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```

### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Erzeugt ein mathematisches Gruppierungszeichen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathe-Element, dem das Gruppierungszeichen zugewiesen wird |
| character | char | Gruppierungszeichen |
| position | int | Position des Gruppierungszeichens |
| verticalJustification | int | Vertikale Ausrichtung |

**Rückgabewert:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - neues Gruppierungszeichen-Element
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Erzeugt ein mathematisches Gruppierungszeichen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathe-Element, dem das Gruppierungszeichen zugewiesen wird |

**Rückgabewert:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - neues Gruppierungszeichen-Element