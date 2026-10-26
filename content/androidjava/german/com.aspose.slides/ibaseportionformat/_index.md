---
title: IBasePortionFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Diese Klasse enthält die Formatierungseigenschaften des Textabschnitts.
type: docs
url: /de/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Diese Klasse enthält die Formatierungseigenschaften des Textabschnitts. Im Gegensatz zu [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

--------------------

Diese Klasse wird verwendet, um die für einen bestimmten Abschnitt definierten Formatierungseigenschaften des Textabschnitts zurückzugeben und zu verändern. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich geerbter Werte zu erhalten, müssen Sie die Methode [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) verwenden, die eine Instanz von [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) zurückgibt.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Gibt die LineFormat-Eigenschaften für die Textkontur zurück. |
| [getFillFormat()](#getFillFormat--) | Gibt die FillFormat-Eigenschaften des Textes zurück. |
| [getEffectFormat()](#getEffectFormat--) | Gibt die EffectFormat-Eigenschaften des Textes zurück. |
| [getHighlightColor()](#getHighlightColor--) | Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Gibt die LineFormat-Eigenschaften zurück, die zum Umranden der Unterstreichungslinie verwendet werden. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. |
| [getFontBold()](#getFontBold--) | Ermittelt, ob die Schrift fett ist. |
| [setFontBold(byte value)](#setFontBold-byte-) | Ermittelt, ob die Schrift fett ist. |
| [getFontItalic()](#getFontItalic--) | Ermittelt, ob die Schrift kursiv ist. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Ermittelt, ob die Schrift kursiv ist. |
| [getKumimoji()](#getKumimoji--) | Ermittelt, ob die Zahlen das bei ostasiatischem Text spezifische vertikale Layout ignorieren sollen. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Ermittelt, ob die Zahlen das bei ostasiatischem Text spezifische vertikale Layout ignorieren sollen. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Ermittelt, ob die Höhe eines Textes normalisiert werden soll. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Ermittelt, ob die Höhe eines Textes normalisiert werden soll. |
| [getProofDisabled()](#getProofDisabled--) | Ermittelt, ob der Text nicht geprüft werden soll. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Ermittelt, ob der Text nicht geprüft werden soll. |
| [getFontUnderline()](#getFontUnderline--) | Gibt den Unterstreichungstyp des Textes zurück oder setzt ihn. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Gibt den Unterstreichungstyp des Textes zurück oder setzt ihn. |
| [getTextCapType()](#getTextCapType--) | Gibt den Typ der Textgroßschreibung zurück oder setzt ihn. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Gibt den Typ der Textgroßschreibung zurück oder setzt ihn. |
| [getStrikethroughType()](#getStrikethroughType--) | Gibt den Durchstreichungstyp eines Textes zurück oder setzt ihn. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Gibt den Durchstreichungstyp eines Textes zurück oder setzt ihn. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Ermittelt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder diese von den LineFormat-Eigenschaften des Textes erbt. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Ermittelt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder diese von den LineFormat-Eigenschaften des Textes erbt. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Ermittelt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder diese von den FillFormat-Eigenschaften des Textes erbt. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Ermittelt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder diese von den FillFormat-Eigenschaften des Textes erbt. |
| [getFontHeight()](#getFontHeight--) | Gibt die Schriftgröße eines Abschnitts zurück oder setzt sie. |
| [setFontHeight(float value)](#setFontHeight-float-) | Gibt die Schriftgröße eines Abschnitts zurück oder setzt sie. |
| [getLatinFont()](#getLatinFont--) | Gibt die Latin-Schriftinformationen zurück oder setzt sie. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Gibt die Latin-Schriftinformationen zurück oder setzt sie. |
| [getEastAsianFont()](#getEastAsianFont--) | Gibt die East Asian-Schriftinformationen zurück oder setzt sie. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Gibt die East Asian-Schriftinformationen zurück oder setzt sie. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Gibt die Complex Script-Schriftinformationen zurück oder setzt sie. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Gibt die Complex Script-Schriftinformationen zurück oder setzt sie. |
| [getSymbolFont()](#getSymbolFont--) | Gibt die symbolischen Schriftinformationen zurück oder setzt sie. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Gibt die symbolischen Schriftinformationen zurück oder setzt sie. |
| [getEscapement()](#getEscapement--) | Gibt den Hoch- oder Tiefstellungstext zurück oder setzt ihn. |
| [setEscapement(float value)](#setEscapement-float-) | Gibt den Hoch- oder Tiefstellungstext zurück oder setzt ihn. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Gibt die minimale Schriftgröße zurück, für die Kerning aktiviert sein soll, oder setzt sie. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Gibt die minimale Schriftgröße zurück, für die Kerning aktiviert sein soll, oder setzt sie. |
| [getLanguageId()](#getLanguageId--) | Gibt die Id einer Korrektursprache zurück oder setzt sie. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Gibt die Id einer Korrektursprache zurück oder setzt sie. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Gibt die Id einer alternativen Sprache zurück oder setzt sie. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Gibt die Id einer alternativen Sprache zurück oder setzt sie. |
| [getSpacing()](#getSpacing--) | Gibt die Erhöhung des Zeichenabstands zurück oder setzt sie. |
| [setSpacing(float value)](#setSpacing-float-) | Gibt die Erhöhung des Zeichenabstands zurück oder setzt sie. |
| [getSpellCheck()](#getSpellCheck--) | Ermittelt oder setzt einen Wert, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Ermittelt oder setzt einen Wert, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Gibt die LineFormat-Eigenschaften für die Textkontur zurück. Keine Vererbung angewendet. Nur-Lesen [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Gibt die FillFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur-Lesen [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Gibt die EffectFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur-Lesen [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Rückgabe:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. Keine Vererbung angewendet. Nur-Lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Gibt die LineFormat-Eigenschaften zurück, die zum Umranden der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Nur-Lesen [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Keine Vererbung angewendet. Nur-Lesen [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Ermittelt, ob die Schrift fett ist. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Ermittelt, ob die Schrift fett ist. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Ermittelt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Ermittelt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Ermittelt, ob die Zahlen das bei ostasiatischem Text spezifische vertikale Layout ignorieren sollen. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Ermittelt, ob die Zahlen das bei ostasiatischem Text spezifische vertikale Layout ignorieren sollen. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Ermittelt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Ermittelt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Ermittelt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Ermittelt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Gibt den Unterstreichungstyp des Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lesen/Schreiben [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Rückgabe:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Gibt den Unterstreichungstyp des Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lesen/Schreiben [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Gibt den Typ der Textgroßschreibung zurück oder setzt ihn. Keine Vererbung angewendet. Lesen/Schreiben [TextCapType](../../com.aspose.slides/textcaptype).

**Rückgabe:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Gibt den Typ der Textgroßschreibung zurück oder setzt ihn. Keine Vererbung angewendet. Lesen/Schreiben [TextCapType](../../com.aspose.slides/textcaptype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Gibt den Durchstreichungstyp eines Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lesen/Schreiben [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Rückgabe:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Gibt den Durchstreichungstyp eines Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lesen/Schreiben [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Ermittelt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder diese von den LineFormat-Eigenschaften des Textes erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Ermittelt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder diese von den LineFormat-Eigenschaften des Textes erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Ermittelt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder diese von den FillFormat-Eigenschaften des Textes erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Ermittelt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder diese von den FillFormat-Eigenschaften des Textes erbt. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Gibt die Schriftgröße eines Abschnitts zurück oder setzt sie. **Float.NaN** bedeutet, dass die Größe undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben float.

**Rückgabe:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Gibt die Schriftgröße eines Abschnitts zurück oder setzt sie. **Float.NaN** bedeutet, dass die Größe undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Gibt die Latin-Schriftinformationen zurück oder setzt sie. Null bedeutet, dass die Schrift undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Gibt die Latin-Schriftinformationen zurück oder setzt sie. Null bedeutet, dass die Schrift undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Gibt die East Asian-Schriftinformationen zurück oder setzt sie. Null bedeutet, dass die Schrift undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Gibt die East Asian-Schriftinformationen zurück oder setzt sie. Null bedeutet, dass die Schrift undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Gibt die Complex Script-Schriftinformationen zurück oder setzt sie. Null bedeutet, dass die Schrift undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Gibt die Complex Script-Schriftinformationen zurück oder setzt sie. Null bedeutet, dass die Schrift undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Gibt die symbolischen Schriftinformationen zurück oder setzt sie. Null bedeutet, dass die Schrift undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Gibt die symbolischen Schriftinformationen zurück oder setzt sie. Null bedeutet, dass die Schrift undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Gibt den Hoch- oder Tiefstellungstext zurück oder setzt ihn. Wert von -100 % (Tiefstellung) bis 100 % (Hochstellung). **Float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben float.

**Rückgabe:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Gibt den Hoch- oder Tiefstellungstext zurück oder setzt ihn. Wert von -100 % (Tiefstellung) bis 100 % (Hochstellung). **Float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Gibt die minimale Schriftgröße zurück, für die Kerning aktiviert sein soll. **Float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben float.

**Rückgabe:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Gibt die minimale Schriftgröße zurück, für die Kerning aktiviert sein soll. **Float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Gibt die Id einer Korrektursprache zurück oder setzt sie. Wird für Rechtschreib- und Grammatikprüfung verwendet. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Gibt die Id einer Korrektursprache zurück oder setzt sie. Wird für Rechtschreib- und Grammatikprüfung verwendet. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Gibt die Id einer alternativen Sprache zurück oder setzt sie. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Gibt die Id einer alternativen Sprache zurück oder setzt sie. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Gibt die Erhöhung des Zeichenabstands zurück oder setzt sie. **Float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben float.

**Rückgabe:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Gibt die Erhöhung des Zeichenabstands zurück oder setzt sie. **Float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Ermittelt oder setzt einen Wert, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung erlaubt. Der Standardwert ist false.

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

**Rückgabe:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

Ermittelt oder setzt einen Wert, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung erlaubt. Der Standardwert ist false.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |