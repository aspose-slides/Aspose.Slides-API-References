---
title: BasePortionFormat
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Gemeinsame Formatierungseigenschaften für Textabschnitte.
type: docs
url: /de/com.aspose.slides/baseportionformat/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Gemeinsame Formatierungseigenschaften für Textabschnitte.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Gibt die LineFormat-Eigenschaften für die Textumrandung zurück. |
| [getFillFormat()](#getFillFormat--) | Gibt die FillFormat-Eigenschaften des Textes zurück. |
| [getEffectFormat()](#getEffectFormat--) | Gibt die EffectFormat-Eigenschaften des Textes zurück. |
| [getHighlightColor()](#getHighlightColor--) | Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Gibt die LineFormat-Eigenschaften zurück, die zum Umranden der Unterstreichungslinie verwendet werden. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. |
| [getFontBold()](#getFontBold--) | Bestimmt, ob die Schrift fett ist. |
| [setFontBold(byte value)](#setFontBold-byte-) | Bestimmt, ob die Schrift fett ist. |
| [getFontItalic()](#getFontItalic--) | Bestimmt, ob die Schrift kursiv ist. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Bestimmt, ob die Schrift kursiv ist. |
| [getKumimoji()](#getKumimoji--) | Bestimmt, ob die Zahlen das vertikale Textlayout für ostasiatische Sprachen ignorieren sollen. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Bestimmt, ob die Zahlen das vertikale Textlayout für ostasiatische Sprachen ignorieren sollen. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. |
| [getProofDisabled()](#getProofDisabled--) | Bestimmt, ob der Text nicht korrigiert werden soll. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Bestimmt, ob der Text nicht korrigiert werden soll. |
| [getFontUnderline()](#getFontUnderline--) | Gibt den Textunterstreichungstyp zurück oder legt ihn fest. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Gibt den Textunterstreichungstyp zurück oder legt ihn fest. |
| [getTextCapType()](#getTextCapType--) | Gibt die Art der Textkapitalisierung zurück oder legt sie fest. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Gibt die Art der Textkapitalisierung zurück oder legt sie fest. |
| [getStrikethroughType()](#getStrikethroughType--) | Gibt den Durchstreichtyp eines Textes zurück oder legt ihn fest. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Gibt den Durchstreichtyp eines Textes zurück oder legt ihn fest. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften besitzt oder diese von den LineFormat-Eigenschaften des Textes erbt. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften besitzt oder diese von den LineFormat-Eigenschaften des Textes erbt. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften besitzt oder diese von den FillFormat-Eigenschaften des Textes erbt. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften besitzt oder diese von den FillFormat-Eigenschaften des Textes erbt. |
| [getFontHeight()](#getFontHeight--) | Gibt die Schriftgröße eines Abschnitts zurück oder legt sie fest. |
| [setFontHeight(float value)](#setFontHeight-float-) | Gibt die Schriftgröße eines Abschnitts zurück oder legt sie fest. |
| [getLatinFont()](#getLatinFont--) | Gibt die Informationen zur lateinischen Schrift zurück oder legt sie fest. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Gibt die Informationen zur lateinischen Schrift zurück oder legt sie fest. |
| [getEastAsianFont()](#getEastAsianFont--) | Gibt die Informationen zur ostasiatischen Schrift zurück oder legt sie fest. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Gibt die Informationen zur ostasiatischen Schrift zurück oder legt sie fest. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Gibt die Informationen zur komplexen Skript-Schrift zurück oder legt sie fest. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Gibt die Informationen zur komplexen Skript-Schrift zurück oder legt sie fest. |
| [getSymbolFont()](#getSymbolFont--) | Gibt die Informationen zur symbolischen Schrift zurück oder legt sie fest. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Gibt die Informationen zur symbolischen Schrift zurück oder legt sie fest. |
| [getEscapement()](#getEscapement--) | Gibt den hoch- oder tiefgestellten Text zurück oder legt ihn fest. |
| [setEscapement(float value)](#setEscapement-float-) | Gibt den hoch- oder tiefgestellten Text zurück oder legt ihn fest. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Gibt die minimale Schriftgröße zurück, für die Kerning aktiviert werden soll, oder legt sie fest. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Gibt die minimale Schriftgröße zurück, für die Kerning aktiviert werden soll, oder legt sie fest. |
| [getLanguageId()](#getLanguageId--) | Gibt die Id einer Korrektursprache zurück oder legt sie fest. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Gibt die Id einer Korrektursprache zurück oder legt sie fest. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Gibt die Id einer alternativen Sprache zurück oder legt sie fest. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Gibt die Id einer alternativen Sprache zurück oder legt sie fest. |
| [getSpacing()](#getSpacing--) | Gibt den Abstandszuwachs zwischen Zeichen zurück oder legt ihn fest. |
| [setSpacing(float value)](#setSpacing-float-) | Gibt den Abstandszuwachs zwischen Zeichen zurück oder legt ihn fest. |
| [getSpellCheck()](#getSpellCheck--) | Erhält oder legt einen Wert fest, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Erhält oder legt einen Wert fest, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur-Lese long.

**Rückgabe:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

Gibt die LineFormat-Eigenschaften für die Textumrandung zurück. Keine Vererbung angewendet. Nur-Lese [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Gibt die FillFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur-Lese [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Gibt die EffectFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur-Lese [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Rückgabe:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. Keine Vererbung angewendet. Nur-Lese [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Gibt die LineFormat-Eigenschaften zurück, die zum Umranden der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Nur-Lese [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Keine Vererbung angewendet. Nur-Lese [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Bestimmt, ob die Schrift fett ist. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Bestimmt, ob die Schrift fett ist. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Bestimmt, ob die Zahlen das vertikale Textlayout für ostasiatische Sprachen ignorieren sollen. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Bestimmt, ob die Zahlen das vertikale Textlayout für ostasiatische Sprachen ignorieren sollen. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Bestimmt, ob der Text nicht korrigiert werden soll. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Bestimmt, ob der Text nicht korrigiert werden soll. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Gibt den Textunterstreichungstyp zurück oder legt ihn fest. Keine Vererbung angewendet. Lesen/Schreiben [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Rückgabe:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Gibt den Textunterstreichungstyp zurück oder legt ihn fest. Keine Vererbung angewendet. Lesen/Schreiben [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Gibt die Art der Textkapitalisierung zurück oder legt sie fest. Keine Vererbung angewendet. Lesen/Schreiben [TextCapType](../../com.aspose.slides/textcaptype).

**Rückgabe:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Gibt die Art der Textkapitalisierung zurück oder legt sie fest. Keine Vererbung angewendet. Lesen/Schreiben [TextCapType](../../com.aspose.slides/textcaptype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Gibt den Durchstreichtyp eines Textes zurück oder legt ihn fest. Keine Vererbung angewendet. Lesen/Schreiben [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Rückgabe:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Gibt den Durchstreichtyp eines Textes zurück oder legt ihn fest. Keine Vererbung angewendet. Lesen/Schreiben [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften besitzt oder diese von den LineFormat-Eigenschaften des Textes erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften besitzt oder diese von den LineFormat-Eigenschaften des Textes erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften besitzt oder diese von den FillFormat-Eigenschaften des Textes erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften besitzt oder diese von den FillFormat-Eigenschaften des Textes erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Gibt die Schriftgröße eines Abschnitts zurück oder legt sie fest. **Float.NaN** bedeutet, dass die Größe nicht definiert ist und vom Master geerbt werden soll. Lesen/Schreiben  float .

**Rückgabe:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Gibt die Schriftgröße eines Abschnitts zurück oder legt sie fest. **Float.NaN** bedeutet, dass die Größe nicht definiert ist und vom Master geerbt werden soll. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Gibt die Informationen zur lateinischen Schrift zurück oder legt sie fest. Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Gibt die Informationen zur lateinischen Schrift zurück oder legt sie fest. Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Gibt die Informationen zur ostasiatischen Schrift zurück oder legt sie fest. Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Gibt die Informationen zur ostasiatischen Schrift zurück oder legt sie fest. Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Gibt die Informationen zur komplexen Skript-Schrift zurück oder legt sie fest. Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Gibt die Informationen zur komplexen Skript-Schrift zurück oder legt sie fest. Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Gibt die Informationen zur symbolischen Schrift zurück oder legt sie fest. Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Gibt die Informationen zur symbolischen Schrift zurück oder legt sie fest. Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Gibt den hoch- oder tiefgestellten Text zurück oder legt ihn fest. Werte von -100 % (tiefgestellt) bis 100 % (hochgestellt). **Float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden soll. Lesen/Schreiben  float .

**Rückgabe:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Gibt den hoch- oder tiefgestellten Text zurück oder legt ihn fest. Werte von -100 % (tiefgestellt) bis 100 % (hochgestellt). **Float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden soll. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Gibt die minimale Schriftgröße zurück, für die Kerning aktiviert werden soll, oder legt sie fest. **Float.NaN** bedeutet, dass die Größe nicht definiert ist und vom Master geerbt werden soll. Lesen/Schreiben  float .

**Rückgabe:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Gibt die minimale Schriftgröße zurück, für die Kerning aktiviert werden soll, oder legt sie fest. **Float.NaN** bedeutet, dass die Größe nicht definiert ist und vom Master geerbt werden soll. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Gibt die Id einer Korrektursprache zurück oder legt sie fest. Wird zur Rechtschreib- und Grammatikprüfung verwendet. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Gibt die Id einer Korrektursprache zurück oder legt sie fest. Wird zur Rechtschreib- und Grammatikprüfung verwendet. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Gibt die Id einer alternativen Sprache zurück oder legt sie fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Gibt die Id einer alternativen Sprache zurück oder legt sie fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Gibt den Abstandszuwachs zwischen Zeichen zurück oder legt ihn fest. **Float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden soll. Lesen/Schreiben  float .

**Rückgabe:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Gibt den Abstandszuwachs zwischen Zeichen zurück oder legt ihn fest. **Float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden soll. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Erhält oder legt einen Wert fest, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt wird, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt wird, ist die Rechtschreibprüfung erlaubt. Standardwert ist false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Access the first portion of text inside the first shape on the first slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Enable spell checking for this text portion
>      portion.getPortionFormat().setSpellCheck(true);
>      // Save the modified presentation
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

Erhält oder legt einen Wert fest, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt wird, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt wird, ist die Rechtschreibprüfung erlaubt. Standardwert ist false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Access the first portion of text inside the first shape on the first slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Enable spell checking for this text portion
>      portion.getPortionFormat().setSpellCheck(true);
>      // Save the modified presentation
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |