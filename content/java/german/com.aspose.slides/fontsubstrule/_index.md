---
title: FontSubstRule
second_title: Aspose.Slides für Java API-Referenz
description: Stellt Informationen zur Schriftartsubstitution dar
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

Stellt Informationen zur Schriftartsubstitution dar
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Erstellt eine neue Instanz. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Erstellt eine neue Instanz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Zu ersetzende Schriftart. |
| [getDestFont()](#getDestFont--) | Für die Substitution zu verwendende Schriftart. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Für die Substitution anzuwendende Regel. |
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


Zu ersetzende Schriftart. Nur lesbar [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


Für die Substitution zu verwendende Schriftart. Nur lesbar [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


Für die Substitution anzuwendende Regel. Nur lesbar [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Rückgabe:**
int