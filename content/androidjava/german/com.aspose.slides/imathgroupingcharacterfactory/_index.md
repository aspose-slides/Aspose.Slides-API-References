---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math grouping character
type: docs
url: /de/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Ermöglicht das Erstellen eines mathematischen Gruppierungszeichens

--------------------

Für COM-Kompatibilität
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Erstellt ein mathematisches Gruppierungszeichen |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Erstellt ein mathematisches Gruppierungszeichen |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Erstellt ein mathematisches Gruppierungszeichen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathematisches Element, dem das Gruppierungszeichen zugewiesen wird |
| character | char | Gruppierungszeichen |
| position | int | Position des Gruppierungszeichens |
| verticalJustification | int | Vertikale Ausrichtung |

**Rückgabewert:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - neues Gruppierungszeichenelement
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Erstellt ein mathematisches Gruppierungszeichen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathematisches Element, dem das Gruppierungszeichen zugewiesen wird |

**Rückgabewert:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - neues Gruppierungszeichenelement