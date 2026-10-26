---
title: BasePortionFormat
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Wspólne właściwości formatowania fragmentu tekstu.
type: docs
url: /pl/com.aspose.slides/baseportionformat/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Wspólne właściwości formatowania fragmentu tekstu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Zwraca właściwości LineFormat dla obramowania tekstu. |
| [getFillFormat()](#getFillFormat--) | Zwraca właściwości FillFormat tekstu. |
| [getEffectFormat()](#getEffectFormat--) | Zwraca właściwości EffectFormat tekstu. |
| [getHighlightColor()](#getHighlightColor--) | Zwraca kolor używany do podświetlenia tekstu. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Zwraca właściwości LineFormat używane do obramowania linii podkreślenia. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Zwraca właściwości FillFormat linii podkreślenia. |
| [getFontBold()](#getFontBold--) | Określa, czy czcionka jest pogrubiona. |
| [setFontBold(byte value)](#setFontBold-byte-) | Określa, czy czcionka jest pogrubiona. |
| [getFontItalic()](#getFontItalic--) | Określa, czy czcionka jest kursywą. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Określa, czy czcionka jest kursywą. |
| [getKumimoji()](#getKumimoji--) | Określa, czy liczby powinny ignorować specyficzny dla wschodnich języków pionowy układ tekstu. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Określa, czy liczby powinny ignorować specyficzny dla wschodnich języków pionowy układ tekstu. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Określa, czy wysokość tekstu powinna być znormalizowana. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Określa, czy wysokość tekstu powinna być znormalizowana. |
| [getProofDisabled()](#getProofDisabled--) | Określa, czy tekst nie powinien być sprawdzany. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Określa, czy tekst nie powinien być sprawdzany. |
| [getFontUnderline()](#getFontUnderline--) | Zwraca lub ustawia typ podkreślenia tekstu. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Zwraca lub ustawia typ podkreślenia tekstu. |
| [getTextCapType()](#getTextCapType--) | Zwraca lub ustawia typ kapitalizacji tekstu. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Zwraca lub ustawia typ kapitalizacji tekstu. |
| [getStrikethroughType()](#getStrikethroughType--) | Zwraca lub ustawia typ przekreślenia tekstu. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Zwraca lub ustawia typ przekreślenia tekstu. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Określa, czy styl podkreślenia ma własne właściwości LineFormat lub dziedziczy je z właściwości LineFormat tekstu. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Określa, czy styl podkreślenia ma własne właściwości LineFormat lub dziedziczy je z właściwości LineFormat tekstu. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Określa, czy styl podkreślenia ma własne właściwości FillFormat lub dziedziczy je z właściwości FillFormat tekstu. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Określa, czy styl podkreślenia ma własne właściwości FillFormat lub dziedziczy je z właściwości FillFormat tekstu. |
| [getFontHeight()](#getFontHeight--) | Zwraca lub ustawia wysokość czcionki fragmentu. |
| [setFontHeight(float value)](#setFontHeight-float-) | Zwraca lub ustawia wysokość czcionki fragmentu. |
| [getLatinFont()](#getLatinFont--) | Zwraca lub ustawia informacje o czcionce łacińskiej. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Zwraca lub ustawia informacje o czcionce łacińskiej. |
| [getEastAsianFont()](#getEastAsianFont--) | Zwraca lub ustawia informacje o czcionce wschodnioazjatyckiej. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Zwraca lub ustawia informacje o czcionce wschodnioazjatyckiej. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Zwraca lub ustawia informacje o czcionce skryptu złożonego. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Zwraca lub ustawia informacje o czcionce skryptu złożonego. |
| [getSymbolFont()](#getSymbolFont--) | Zwraca lub ustawia informacje o czcionce symbolicznej. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Zwraca lub ustawia informacje o czcionce symbolicznej. |
| [getEscapement()](#getEscapement--) | Zwraca lub ustawia tekst w indeksie górnym lub dolnym. |
| [setEscapement(float value)](#setEscapement-float-) | Zwraca lub ustawia tekst w indeksie górnym lub dolnym. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Zwraca lub ustawia minimalny rozmiar czcionki, przy którym kerning powinien być włączony. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Zwraca lub ustawia minimalny rozmiar czcionki, przy którym kerning powinien być włączony. |
| [getLanguageId()](#getLanguageId--) | Zwraca lub ustawia identyfikator języka korekty. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Zwraca lub ustawia identyfikator języka korekty. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Zwraca lub ustawia identyfikator języka alternatywnego. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Zwraca lub ustawia identyfikator języka alternatywnego. |
| [getSpacing()](#getSpacing--) | Zwraca lub ustawia przyrost odstępu między znakami. |
| [setSpacing(float value)](#setSpacing-float-) | Zwraca lub ustawia przyrost odstępu między znakami. |
| [getSpellCheck()](#getSpellCheck--) | Pobiera lub ustawia wartość wskazującą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Pobiera lub ustawia wartość wskazującą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

Zwraca właściwości LineFormat dla obramowania tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Zwraca właściwości FillFormat tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Zwraca właściwości EffectFormat tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Zwraca:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Zwraca kolor używany do podświetlenia tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Zwraca właściwości LineFormat używane do obramowania linii podkreślenia. Nie zastosowano dziedziczenia. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Zwraca właściwości FillFormat linii podkreślenia. Nie zastosowano dziedziczenia. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Określa, czy czcionka jest pogrubiona. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Określa, czy czcionka jest pogrubiona. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Określa, czy czcionka jest kursywą. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Określa, czy czcionka jest kursywą. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Określa, czy liczby powinny ignorować specyficzny dla wschodnich języków pionowy układ tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Określa, czy liczby powinny ignorować specyficzny dla wschodnich języków pionowy układ tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Określa, czy wysokość tekstu powinna być znormalizowana. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Określa, czy wysokość tekstu powinna być znormalizowana. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Określa, czy tekst nie powinien być sprawdzany. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Określa, czy tekst nie powinien być sprawdzany. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Zwraca lub ustawia typ podkreślenia tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Zwraca:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Zwraca lub ustawia typ podkreślenia tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Zwraca lub ustawia typ kapitalizacji tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [TextCapType](../../com.aspose.slides/textcaptype).

**Zwraca:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Zwraca lub ustawia typ kapitalizacji tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [TextCapType](../../com.aspose.slides/textcaptype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Zwraca lub ustawia typ przekreślenia tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Zwraca:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Zwraca lub ustawia typ przekreślenia tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Określa, czy styl podkreślenia ma własne właściwości LineFormat lub dziedziczy je z właściwości LineFormat tekstu. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Określa, czy styl podkreślenia ma własne właściwości LineFormat lub dziedziczy je z właściwości LineFormat tekstu. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Określa, czy styl podkreślenia ma własne właściwości FillFormat lub dziedziczy je z właściwości FillFormat tekstu. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Określa, czy styl podkreślenia ma własne właściwości FillFormat lub dziedziczy je z właściwości FillFormat tekstu. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Zwraca lub ustawia wysokość czcionki fragmentu. **Float.NaN** oznacza, że wysokość jest nieokreślona i powinna być dziedziczona z Mastera. Odczyt/zapis  float .

**Zwraca:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Zwraca lub ustawia wysokość czcionki fragmentu. **Float.NaN** oznacza, że wysokość jest nieokreślona i powinna być dziedziczona z Mastera. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Zwraca lub ustawia informacje o czcionce łacińskiej. Null oznacza, że czcionka jest nieokreślona i powinna być dziedziczona z Mastera. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Zwraca lub ustawia informacje o czcionce łacińskiej. Null oznacza, że czcionka jest nieokreślona i powinna być dziedziczona z Mastera. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Zwraca lub ustawia informacje o czcionce wschodnioazjatyckiej. Null oznacza, że czcionka jest nieokreślona i powinna być dziedziczona z Mastera. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Zwraca lub ustawia informacje o czcionce wschodnioazjatyckiej. Null oznacza, że czcionka jest nieokreślona i powinna być dziedziczona z Mastera. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Zwraca lub ustawia informacje o czcionce skryptu złożonego. Null oznacza, że czcionka jest nieokreślona i powinna być dziedziczona z Mastera. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Zwraca lub ustawia informacje o czcionce skryptu złożonego. Null oznacza, że czcionka jest nieokreślona i powinna być dziedziczona z Mastera. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Zwraca lub ustawia informacje o czcionce symbolicznej. Null oznacza, że czcionka jest nieokreślona i powinna być dziedziczona z Mastera. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Zwraca lub ustawia informacje o czcionce symbolicznej. Null oznacza, że czcionka jest nieokreślona i powinna być dziedziczona z Mastera. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Zwraca lub ustawia tekst w indeksie górnym lub dolnym. Wartość od -100% (indeks dolny) do 100% (indeks górny). **Float.NaN** oznacza, że wartość jest nieokreślona i powinna być dziedziczona z Mastera. Odczyt/zapis  float .

**Zwraca:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Zwraca lub ustawia tekst w indeksie górnym lub dolnym. Wartość od -100% (indeks dolny) do 100% (indeks górny). **Float.NaN** oznacza, że wartość jest nieokreślona i powinna być dziedziczona z Mastera. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Zwraca lub ustawia minimalny rozmiar czcionki, przy którym kerning powinien być włączony. **Float.NaN** oznacza, że wartość jest nieokreślona i powinna być dziedziczona z Mastera. Odczyt/zapis  float .

**Zwraca:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Zwraca lub ustawia minimalny rozmiar czcionki, przy którym kerning powinien być włączony. **Float.NaN** oznacza, że wartość jest nieokreślona i powinna być dziedziczona z Mastera. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Zwraca lub ustawia identyfikator języka korekty. Używany do sprawdzania pisowni i gramatyki. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Zwraca lub ustawia identyfikator języka korekty. Używany do sprawdzania pisowni i gramatyki. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Zwraca lub ustawia identyfikator języka alternatywnego. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Zwraca lub ustawia identyfikator języka alternatywnego. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Zwraca lub ustawia przyrost odstępu między znakami. **Float.NaN** oznacza, że wartość jest nieokreślona i powinna być dziedziczona z Mastera. Odczyt/zapis  float .

**Zwraca:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Zwraca lub ustawia przyrost odstępu między znakami. **Float.NaN** oznacza, że wartość jest nieokreślona i powinna być dziedziczona z Mastera. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Pobiera lub ustawia wartość wskazującą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. Gdy własność jest ustawiona na false, sprawdzanie pisowni elementów tekstu jest pomijane. Gdy ustawiona na true, sprawdzanie pisowni jest dozwolone. Domyślna wartość to false.

**Zwraca:**
boolean
--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Uzyskaj dostęp do pierwszego fragmentu tekstu wewnątrz pierwszego kształtu na pierwszym slajdzie
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Włącz sprawdzanie pisowni dla tego fragmentu tekstu
>      portion.getPortionFormat().setSpellCheck(true);
>      // Zapisz zmodyfikowaną prezentację
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
boolean
### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

Pobiera lub ustawia wartość wskazującą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. Gdy własność jest ustawiona na false, sprawdzanie pisowni elementów tekstu jest pomijane. Gdy ustawiona na true, sprawdzanie pisowni jest dozwolone. Domyślna wartość to false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Uzyskaj dostęp do pierwszego fragmentu tekstu wewnątrz pierwszego kształtu na pierwszym slajdzie
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Włącz sprawdzanie pisowni dla tego fragmentu tekstu
>      portion.getPortionFormat().setSpellCheck(true);
>      // Zapisz zmodyfikowaną prezentację
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |