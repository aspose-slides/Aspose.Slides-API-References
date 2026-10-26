---
title: IBasePortionFormat
second_title: Aspose.Slides for Java API Reference
description: This class contains the text portion formatting properties.
type: docs
url: /pl/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Ta klasa zawiera właściwości formatowania fragmentu tekstu. W przeciwieństwie do [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), wszystkie właściwości tej klasy są zapisywalne.

--------------------

Ta klasa służy do zwracania i manipulowania właściwościami formatowania fragmentu tekstu zdefiniowanymi dla konkretnego fragmentu. Oznacza to, że przy pobieraniu wartości nie jest stosowane dziedziczenie, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać skuteczne wartości parametrów formatowania, w tym odziedziczone, należy użyć metody [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective), która zwraca instancję [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Metody

| Metoda | Opis |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Zwraca właściwości LineFormat dla obramowania tekstu. |
| [getFillFormat()](#getFillFormat--) | Zwraca właściwości FillFormat tekstu. |
| [getEffectFormat()](#getEffectFormat--) | Zwraca właściwości EffectFormat tekstu. |
| [getHighlightColor()](#getHighlightColor--) | Zwraca kolor używany do podświetlania tekstu. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Zwraca właściwości LineFormat używane do obramowania podkreślonej linii. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Zwraca właściwości FillFormat podkreślonej linii. |
| [getFontBold()](#getFontBold--) | Określa, czy czcionka jest pogrubiona. |
| [setFontBold(byte value)](#setFontBold-byte-) | Określa, czy czcionka jest pogrubiona. |
| [getFontItalic()](#getFontItalic--) | Określa, czy czcionka jest kursywą. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Określa, czy czcionka jest kursywą. |
| [getKumimoji()](#getKumimoji--) | Określa, czy liczby powinny ignorować specyficzny dla wschodnich języków pionowy układ tekstu. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Określa, czy liczby powinny ignorować specyficzny dla wschodnich języków pionowy układ tekstu. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Określa, czy wysokość tekstu powinna być normalizowana. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Określa, czy wysokość tekstu powinna być normalizowana. |
| [getProofDisabled()](#getProofDisabled--) | Określa, czy tekst nie powinien być sprawdzany pod kątem korekty. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Określa, czy tekst nie powinien być sprawdzany pod kątem korekty. |
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
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Zwraca lub ustawia minimalny rozmiar czcionki, dla którego powinno być włączone kerning. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Zwraca lub ustawia minimalny rozmiar czcionki, dla którego powinno być włączone kerning. |
| [getLanguageId()](#getLanguageId--) | Zwraca lub ustawia identyfikator języka korekty. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Zwraca lub ustawia identyfikator języka korekty. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Zwraca lub ustawia identyfikator języka alternatywnego. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Zwraca lub ustawia identyfikator języka alternatywnego. |
| [getSpacing()](#getSpacing--) | Zwraca lub ustawia przyrost odstępu między znakami. |
| [setSpacing(float value)](#setSpacing-float-) | Zwraca lub ustawia przyrost odstępu między znakami. |
| [getSpellCheck()](#getSpellCheck--) | Pobiera lub ustawia wartość wskazującą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Pobiera lub ustawia wartość wskazującą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Zwraca właściwości LineFormat dla obramowania tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Zwraca właściwości FillFormat tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Zwraca właściwości EffectFormat tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Zwraca:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Zwraca kolor używany do podświetlania tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Zwraca właściwości LineFormat używane do obramowania podkreślonej linii. Nie zastosowano dziedziczenia. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Zwraca właściwości FillFormat podkreślonej linii. Nie zastosowano dziedziczenia. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Określa, czy czcionka jest pogrubiona. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Określa, czy czcionka jest pogrubiona. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Określa, czy czcionka jest kursywą. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Określa, czy czcionka jest kursywą. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Określa, czy liczby powinny ignorować specyficzny dla wschodnich języków pionowy układ tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Określa, czy liczby powinny ignorować specyficzny dla wschodnich języków pionowy układ tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Określa, czy wysokość tekstu powinna być normalizowana. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Określa, czy wysokość tekstu powinna być normalizowana. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Określa, czy tekst nie powinien być sprawdzany pod kątem korekty. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Określa, czy tekst nie powinien być sprawdzany pod kątem korekty. Nie zastosowano dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Zwraca lub ustawia typ podkreślenia tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Zwraca:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Zwraca lub ustawia typ podkreślenia tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Zwraca lub ustawia typ kapitalizacji tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [TextCapType](../../com.aspose.slides/textcaptype).

**Zwraca:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Zwraca lub ustawia typ kapitalizacji tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [TextCapType](../../com.aspose.slides/textcaptype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Zwraca lub ustawia typ przekreślenia tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Zwraca:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Zwraca lub ustawia typ przekreślenia tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Określa, czy styl podkreślenia ma własne właściwości LineFormat lub dziedziczy je z właściwości LineFormat tekstu. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Określa, czy styl podkreślenia ma własne właściwości LineFormat lub dziedziczy je z właściwości LineFormat tekstu. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Określa, czy styl podkreślenia ma własne właściwości FillFormat lub dziedziczy je z właściwości FillFormat tekstu. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Określa, czy styl podkreślenia ma własne właściwości FillFormat lub dziedziczy je z właściwości FillFormat tekstu. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Zwraca lub ustawia wysokość czcionki fragmentu. **Float.NaN** oznacza, że wysokość jest niezdefiniowana i powinna być dziedziczona po Masterze. Odczyt/zapis float.

**Zwraca:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Zwraca lub ustawia wysokość czcionki fragmentu. **Float.NaN** oznacza, że wysokość jest niezdefiniowana i powinna być dziedziczona po Masterze. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Zwraca lub ustawia informacje o czcionce łacińskiej. Null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona po Masterze. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Zwraca lub ustawia informacje o czcionce łacińskiej. Null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona po Masterze. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Zwraca lub ustawia informacje o czcionce wschodnioazjatyckiej. Null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona po Masterze. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Zwraca lub ustawia informacje o czcionce wschodnioazjatyckiej. Null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona po Masterze. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Zwraca lub ustawia informacje o czcionce skryptu złożonego. Null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona po Masterze. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Zwraca lub ustawia informacje o czcionce skryptu złożonego. Null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona po Masterze. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Zwraca lub ustawia informacje o czcionce symbolicznej. Null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona po Masterze. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Zwraca lub ustawia informacje o czcionce symbolicznej. Null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona po Masterze. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Zwraca lub ustawia tekst w indeksie górnym lub dolnym. Wartość od -100 % (indeks dolny) do 100 % (indeks górny). **Float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być dziedziczona po Masterze. Odczyt/zapis float.

**Zwraca:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Zwraca lub ustawia tekst w indeksie górnym lub dolnym. Wartość od -100 % (indeks dolny) do 100 % (indeks górny). **Float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być dziedziczona po Masterze. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Zwraca lub ustawia minimalny rozmiar czcionki, dla którego powinno być włączone kerning. **Float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być dziedziczona po Masterze. Odczyt/zapis float.

**Zwraca:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Zwraca lub ustawia minimalny rozmiar czcionki, dla którego powinno być włączone kerning. **Float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być dziedziczona po Masterze. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Zwraca lub ustawia identyfikator języka korekty. Używany do sprawdzania pisowni i gramatyki. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Zwraca lub ustawia identyfikator języka korekty. Używany do sprawdzania pisowni i gramatyki. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Zwraca lub ustawia identyfikator języka alternatywnego. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Zwraca lub ustawia identyfikator języka alternatywnego. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Zwraca lub ustawia przyrost odstępu między znakami. **Float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być dziedziczona po Masterze. Odczyt/zapis float.

**Zwraca:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Zwraca lub ustawia przyrost odstępu między znakami. **Float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być dziedziczona po Masterze. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Pobiera lub ustawia wartość wskazującą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. Gdy właściwość ma wartość false, sprawdzanie pisowni dla elementów tekstowych jest pomijane. Gdy ma wartość true, sprawdzanie pisowni jest dozwolone. Wartość domyślna to false.

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

**Zwraca:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

Pobiera lub ustawia wartość wskazującą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. Gdy właściwość ma wartość false, sprawdzanie pisowni dla elementów tekstowych jest pomijane. Gdy ma wartość true, sprawdzanie pisowni jest dozwolone. Wartość domyślna to false.

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |