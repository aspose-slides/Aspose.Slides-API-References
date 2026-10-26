---
title: BasePortionFormat
second_title: Aspose.Slides für Java API Referenz
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
| [getLineFormat()](#getLineFormat--) | Gibt die LineFormat-Eigenschaften für die Kontur des Textes zurück. |
| [getFillFormat()](#getFillFormat--) | Gibt die FillFormat-Eigenschaften des Textes zurück. |
| [getEffectFormat()](#getEffectFormat--) | Gibt die EffectFormat-Eigenschaften des Textes zurück. |
| [getHighlightColor()](#getHighlightColor--) | Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Gibt die LineFormat-Eigenschaften zurück, die zum Umranden der Unterstreichungslinie verwendet werden. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. |
| [getFontBold()](#getFontBold--) | Bestimmt, ob die Schrift fett ist. |
| [setFontBold(byte value)](#setFontBold-byte-) | Bestimmt, ob die Schrift fett ist. |
| [getFontItalic()](#getFontItalic--) | Bestimmt, ob die Schrift kursiv ist. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Bestimmt, ob die Schrift kursiv ist. |
| [getKumimoji()](#getKumimoji--) | Bestimmt, ob die Zahlen das vertikale Textlayout ostasiatischer Sprachen ignorieren sollen. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Bestimmt, ob die Zahlen das vertikale Textlayout ostasiatischer Sprachen ignorieren sollen. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. |
| [getProofDisabled()](#getProofDisabled--) | Bestimmt, ob der Text nicht geprüft werden soll. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Bestimmt, ob der Text nicht geprüft werden soll. |
| [getFontUnderline()](#getFontUnderline--) | Gibt den Unterstreichungstyp des Textes zurück oder setzt ihn. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Gibt den Unterstreichungstyp des Textes zurück oder setzt ihn. |
| [getTextCapType()](#getTextCapType--) | Gibt die Art der Textkapitalisierung zurück oder setzt sie. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Gibt die Art der Textkapitalisierung zurück oder setzt sie. |
| [getStrikethroughType()](#getStrikethroughType--) | Gibt den Durchstreichungstyp eines Textes zurück oder setzt ihn. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Gibt den Durchstreichungstyp eines Textes zurück oder setzt ihn. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder sie von den LineFormat-Eigenschaften des Textes erbt. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder sie von den LineFormat-Eigenschaften des Textes erbt. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder sie von den FillFormat-Eigenschaften des Textes erbt. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder sie von den FillFormat-Eigenschaften des Textes erbt. |
| [getFontHeight()](#getFontHeight--) | Gibt die Schriftgröße eines Abschnitts zurück oder setzt sie. |
| [setFontHeight(float value)](#setFontHeight-float-) | Gibt die Schriftgröße eines Abschnitts zurück oder setzt sie. |
| [getLatinFont()](#getLatinFont--) | Gibt die Latin-Schriftinformationen zurück oder setzt sie. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Gibt die Latin-Schriftinformationen zurück oder setzt sie. |
| [getEastAsianFont()](#getEastAsianFont--) | Gibt die Ostasiatische-Schriftinformationen zurück oder setzt sie. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Gibt die Ostasiatische-Schriftinformationen zurück oder setzt sie. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Gibt die Informationen zur komplexen Schrift zurück oder setzt sie. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Gibt die Informationen zur komplexen Schrift zurück oder setzt sie. |
| [getSymbolFont()](#getSymbolFont--) | Gibt die symbolischen Schriftinformationen zurück oder setzt sie. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Gibt die symbolischen Schriftinformationen zurück oder setzt sie. |
| [getEscapement()](#getEscapement--) | Gibt den Hoch- oder Tiefstellungstext zurück oder setzt ihn. |
| [setEscapement(float value)](#setEscapement-float-) | Gibt den Hoch- oder Tiefstellungstext zurück oder setzt ihn. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Gibt die minimale Schriftgröße zurück, bei der Kerning aktiviert werden soll, oder setzt sie. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Gibt die minimale Schriftgröße zurück, bei der Kerning aktiviert werden soll, oder setzt sie. |
| [getLanguageId()](#getLanguageId--) | Gibt die Id einer Rechtschreibprüfungssprache zurück oder setzt sie. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Gibt die Id einer Rechtschreibprüfungssprache zurück oder setzt sie. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Gibt die Id einer alternativen Sprache zurück oder setzt sie. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Gibt die Id einer alternativen Sprache zurück oder setzt sie. |
| [getSpacing()](#getSpacing--) | Gibt die Erhöhung des Zeichenabstands zurück oder setzt sie. |
| [setSpacing(float value)](#setSpacing-float-) | Gibt die Erhöhung des Zeichenabstands zurück oder setzt sie. |
| [getSpellCheck()](#getSpellCheck--) | Ermittelt oder legt einen Wert fest, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Ermittelt oder legt einen Wert fest, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesbar long.

**Returns:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

Gibt die LineFormat-Eigenschaften für die Kontur des Textes zurück. Keine Vererbung angewendet. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Gibt die FillFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur lesbar [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Gibt die EffectFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur lesbar [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Returns:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. Keine Vererbung angewendet. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Gibt die LineFormat-Eigenschaften zurück, die zum Umranden der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Keine Vererbung angewendet. Nur lesbar [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Bestimmt, ob die Schrift fett ist. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Bestimmt, ob die Schrift fett ist. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Bestimmt, ob die Zahlen das vertikale Textlayout ostasiatischer Sprachen ignorieren sollen. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Bestimmt, ob die Zahlen das vertikale Textlayout ostasiatischer Sprachen ignorieren sollen. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Bestimmt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Bestimmt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Gibt den Unterstreichungstyp des Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lesen/Schreiben [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Returns:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Gibt den Unterstreichungstyp des Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lesen/Schreiben [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Gibt die Art der Textkapitalisierung zurück oder setzt sie. Keine Vererbung angewendet. Lesen/Schreiben [TextCapType](../../com.aspose.slides/textcaptype).

**Returns:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Gibt die Art der Textkapitalisierung zurück oder setzt sie. Keine Vererbung angewendet. Lesen/Schreiben [TextCapType](../../com.aspose.slides/textcaptype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Gibt den Durchstreichungstyp eines Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lesen/Schreiben [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Returns:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Gibt den Durchstreichungstyp eines Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lesen/Schreiben [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder sie von den LineFormat-Eigenschaften des Textes erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder sie von den LineFormat-Eigenschaften des Textes erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder sie von den FillFormat-Eigenschaften des Textes erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder sie von den FillFormat-Eigenschaften des Textes erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Gibt die Schriftgröße eines Abschnitts zurück oder setzt sie. **Float.NaN** bedeutet, dass die Höhe undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben  float .

**Returns:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Gibt die Schriftgröße eines Abschnitts zurück oder setzt sie. **Float.NaN** bedeutet, dass die Höhe undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Gibt die Latin-Schriftinformationen zurück oder setzt sie. Null bedeutet, dass die Schrift undefined ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Gibt die Latin-Schriftinformationen zurück oder setzt sie. Null bedeutet, dass die Schrift undefined ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Gibt die Ostasiatische-Schriftinformationen zurück oder setzt sie. Null bedeutet, dass die Schrift undefined ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Gibt die Ostasiatische-Schriftinformationen zurück oder setzt sie. Null bedeutet, dass die Schrift undefined ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Gibt die Informationen zur komplexen Schrift zurück oder setzt sie. Null bedeutet, dass die Schrift undefined ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Gibt die Informationen zur komplexen Schrift zurück oder setzt sie. Null bedeutet, dass die Schrift undefined ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Gibt die symbolischen Schriftinformationen zurück oder setzt sie. Null bedeutet, dass die Schrift undefined ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Gibt die symbolischen Schriftinformationen zurück oder setzt sie. Null bedeutet, dass die Schrift undefined ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Gibt den Hoch- oder Tiefstellungstext zurück oder setzt ihn. Wert von -100 % (Tiefstellung) bis 100 % (Hochstellung). **Float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben  float .

**Returns:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Gibt den Hoch- oder Tiefstellungstext zurück oder setzt ihn. Wert von -100 % (Tiefstellung) bis 100 % (Hochstellung). **Float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Gibt die minimale Schriftgröße zurück, bei der Kerning aktiviert werden soll, oder setzt sie. **Float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben  float .

**Returns:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Gibt die minimale Schriftgröße zurück, bei der Kerning aktiviert werden soll, oder setzt sie. **Float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Gibt die Id einer Rechtschreibprüfungssprache zurück oder setzt sie. Wird zur Rechtschreib- und Grammatikprüfung verwendet. Lesen/Schreiben String.

**Returns:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Gibt die Id einer Rechtschreibprüfungssprache zurück oder setzt sie. Wird zur Rechtschreib- und Grammatikprüfung verwendet. Lesen/Schreiben String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Gibt die Id einer alternativen Sprache zurück oder setzt sie. Lesen/Schreiben String.

**Returns:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Gibt die Id einer alternativen Sprache zurück oder setzt sie. Lesen/Schreiben String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Gibt die Erhöhung des Zeichenabstands zurück oder setzt sie. **Float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben  float .

**Returns:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Gibt die Erhöhung des Zeichenabstands zurück oder setzt sie. **Float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Ermittelt oder legt einen Wert fest, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt wird, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt wird, ist die Rechtschreibprüfung erlaubt. Der Standardwert ist false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Greift auf den ersten Textabschnitt innerhalb der ersten Form auf der ersten Folie zu
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Aktiviert die Rechtschreibprüfung für diesen Textabschnitt
>      portion.getPortionFormat().setSpellCheck(true);
>      // Speichert die geänderte Präsentation
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value



```

Ermittelt oder legt einen Wert fest, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt wird, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt wird, ist die Rechtschreibprüfung erlaubt. Der Standardwert ist false.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |