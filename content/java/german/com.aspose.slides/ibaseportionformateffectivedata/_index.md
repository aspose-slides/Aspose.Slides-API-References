---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Base interface for immutable objects which contain effective text portion formatting properties.
type: docs
url: /de/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Basisschnittstelle für unveränderliche Objekte, die effektive Textabschnitt-Formatierungseigenschaften enthalten.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Gibt die LineFormat-Eigenschaften für die Textumrandung zurück. |
| [getFillFormat()](#getFillFormat--) | Gibt die FillFormat-Eigenschaften des Textes zurück. |
| [getEffectFormat()](#getEffectFormat--) | Gibt die EffectFormat-Eigenschaften des Textes zurück. |
| [getHighlightColor()](#getHighlightColor--) | Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Gibt die LineFormat-Eigenschaften zurück, die zum Umranden der Unterstreichungslinie verwendet werden. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. |
| [getFontBold()](#getFontBold--) | Bestimmt, ob die Schrift fett ist. |
| [getFontItalic()](#getFontItalic--) | Bestimmt, ob die Schrift kursiv ist. |
| [getKumimoji()](#getKumimoji--) | Bestimmt, ob die Zahlen das östliche, sprachspezifische vertikale Textlayout ignorieren sollten. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. |
| [getProofDisabled()](#getProofDisabled--) | Bestimmt, ob der Text nicht geprüft werden soll. |
| [getFontUnderline()](#getFontUnderline--) | Gibt den Unterstreichungstyp des Textes zurück. |
| [getTextCapType()](#getTextCapType--) | Gibt den Typ der Textkapitalisierung zurück. |
| [getStrikethroughType()](#getStrikethroughType--) | Gibt den Durchstreichtyp eines Textes zurück. |
| [getSmartTagClean()](#getSmartTagClean--) | Bestimmt, ob das Smart-Tag bereinigt werden soll. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder sie von den LineFormat-Eigenschaften des Textes erbt. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder sie von den FillFormat-Eigenschaften des Textes erbt. |
| [getFontHeight()](#getFontHeight--) | Gibt die Schriftgröße des Textabschnitts in Punkten zurück. |
| [getLatinFont()](#getLatinFont--) | Gibt die Informationen zur lateinischen Schrift zurück. |
| [getEastAsianFont()](#getEastAsianFont--) | Gibt die Informationen zur ostasiatischen Schrift zurück. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Gibt die Informationen zur komplexen Skript-Schrift zurück. |
| [getSymbolFont()](#getSymbolFont--) | Gibt die Informationen zur symbolischen Schrift zurück. |
| [getEscapement()](#getEscapement--) | Gibt den hoch- oder tiefgestellten Text zurück. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Gibt die minimale Schriftgröße zurück, ab der Kerning aktiviert werden soll. |
| [getLanguageId()](#getLanguageId--) | Gibt die ID einer Sprache zurück. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Gibt die ID einer alternativen Sprache zurück. |
| [getSpacing()](#getSpacing--) | Gibt die Zwischensatzabstandszunahme in Punkten zurück. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

Gibt die LineFormat-Eigenschaften für die Textumrandung zurück. Nur lesbar [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Rückgabe:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Gibt die FillFormat-Eigenschaften des Textes zurück. Nur lesbar [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Rückgabe:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

Gibt die EffectFormat-Eigenschaften des Textes zurück. Nur lesbar [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Rückgabe:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)

### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```

Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. Nur lesbar java.awt.Color.

**Rückgabe:**
java.awt.Color

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

Gibt die LineFormat-Eigenschaften zurück, die zum Umranden der Unterstreichungslinie verwendet werden. Nur lesbar [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Rückgabe:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Nur lesbar [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Rückgabe:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)

### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

Bestimmt, ob die Schrift fett ist. Nur lesbar boolean.

**Rückgabe:**
boolean

### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

Bestimmt, ob die Schrift kursiv ist. Nur lesbar boolean.

**Rückgabe:**
boolean

### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

Bestimmt, ob die Zahlen das östliche, sprachspezifische vertikale Textlayout ignorieren sollten. Nur lesbar boolean.

**Rückgabe:**
boolean

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Nur lesbar boolean.

**Rückgabe:**
boolean

### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

Bestimmt, ob der Text nicht geprüft werden soll. Nur lesbar boolean.

**Rückgabe:**
boolean

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Gibt den Unterstreichungstyp des Textes zurück. Nur lesbar [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Rückgabe:**
byte

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Gibt den Typ der Textkapitalisierung zurück. Nur lesbar [TextCapType](../../com.aspose.slides/textcaptype).

**Rückgabe:**
byte

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Gibt den Durchstreichtyp eines Textes zurück. Nur lesbar [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Rückgabe:**
byte

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Bestimmt, ob das Smart-Tag bereinigt werden soll. Nur lesbar boolean.

**Rückgabe:**
boolean

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder sie von den LineFormat-Eigenschaften des Textes erbt. Nur lesbar boolean.

**Rückgabe:**
boolean

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder sie von den FillFormat-Eigenschaften des Textes erbt. Nur lesbar boolean.

**Rückgabe:**
boolean

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Gibt die Schriftgröße des Textabschnitts in Punkten zurück. Nur lesbar float.

**Rückgabe:**
float

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Gibt die Informationen zur lateinischen Schrift zurück. Nur lesbar [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Gibt die Informationen zur ostasiatischen Schrift zurück. Nur lesbar [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Gibt die Informationen zur komplexen Skript-Schrift zurück. Nur lesbar [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Gibt die Informationen zur symbolischen Schrift zurück. Nur lesbar [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Gibt den hoch- oder tiefgestellten Text zurück. Werte von -100 % (tiefgestellt) bis 100 % (hochgestellt). Nur lesbar float.

**Rückgabe:**
float

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Gibt die minimale Schriftgröße zurück, ab der Kerning aktiviert werden soll. Nur lesbar float.

**Rückgabe:**
float

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Gibt die ID einer Sprache zurück. Nur lesbar String.

**Rückgabe:**
java.lang.String

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Gibt die ID einer alternativen Sprache zurück. Nur lesbar String.

**Rückgabe:**
java.lang.String

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Gibt die Zwischensatzabstandszunahme in Punkten zurück. Nur lesbar float.

**Rückgabe:**
float