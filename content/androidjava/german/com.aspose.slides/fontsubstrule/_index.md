---
title: FontSubstRule
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Stellt Informationen zur Schriftart-Substitution dar
type: docs
url: /de/com.aspose.slides/fontsubstrule/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Stellt Informationen zur Schriftart-Substitution dar
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Erstellt eine neue Instanz. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Erstellt eine neue Instanz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Schriftart zum Ersetzen. |
| [getDestFont()](#getDestFont--) | Schriftart, die für die Substitution verwendet wird. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Regel, die für die Substitution angewendet wird. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```

Erstellt eine neue Instanz.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Quellschriftart. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Zielschriftart. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```

Erstellt eine neue Instanz.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Quellschriftart. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Zielschriftart. |
| fontSubstRule | int | Schriftart-Substitutionsregel. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```

Schriftart zum Ersetzen. Nur lesbar [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabewert:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```

Schriftart, die für die Substitution verwendet wird. Nur lesbar [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabewert:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```

Regel, die für die Substitution angewendet wird. Nur lesbar [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Rückgabewert:**
int