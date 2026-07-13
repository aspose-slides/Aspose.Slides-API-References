---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides dla Androida za pośrednictwem Java API Reference
description: Podstawowy interfejs dla niezmiennych obiektów zawierających efektywne właściwości formatowania fragmentów tekstu.
type: docs
url: /pl/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Podstawowy interfejs dla niezmiennych obiektów zawierających efektywne właściwości formatowania fragmentów tekstu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Zwraca właściwości LineFormat dla obramowania tekstu. |
| [getFillFormat()](#getFillFormat--) | Zwraca właściwości FillFormat tekstu. |
| [getEffectFormat()](#getEffectFormat--) | Zwraca właściwości EffectFormat tekstu. |
| [getHighlightColor()](#getHighlightColor--) | Zwraca kolor używany do podświetlenia tekstu. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Zwraca właściwości LineFormat używane do obramowania linii podkreślenia. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Zwraca właściwości FillFormat linii podkreślenia. |
| [getFontBold()](#getFontBold--) | Określa, czy czcionka jest pogrubiona. |
| [getFontItalic()](#getFontItalic--) | Określa, czy czcionka jest pochyła. |
| [getKumimoji()](#getKumimoji--) | Określa, czy liczby powinny ignorować specyficzny dla wschodnich języków pionowy układ tekstu. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Określa, czy wysokość tekstu powinna być normalizowana. |
| [getProofDisabled()](#getProofDisabled--) | Określa, czy tekst nie powinien być sprawdzany. |
| [getFontUnderline()](#getFontUnderline--) | Zwraca typ podkreślenia tekstu. |
| [getTextCapType()](#getTextCapType--) | Zwraca typ kapitalizacji tekstu. |
| [getStrikethroughType()](#getStrikethroughType--) | Zwraca typ przekreślenia tekstu. |
| [getSmartTagClean()](#getSmartTagClean--) | Określa, czy znacznik inteligentny powinien być wyczyszczony. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Określa, czy styl podkreślenia ma własne właściwości LineFormat czy dziedziczy je z właściwości LineFormat tekstu. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Określa, czy styl podkreślenia ma własne właściwości FillFormat czy dziedziczy je z właściwości FillFormat tekstu. |
| [getFontHeight()](#getFontHeight--) | Zwraca wysokość czcionki fragmentu tekstu, w punktach. |
| [getLatinFont()](#getLatinFont--) | Zwraca informacje o czcionce łacińskiej. |
| [getEastAsianFont()](#getEastAsianFont--) | Zwraca informacje o czcionce wschodnioazjatyckiej. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Zwraca informacje o czcionce skryptu złożonego. |
| [getSymbolFont()](#getSymbolFont--) | Zwraca informacje o czcionce symbolicznej. |
| [getEscapement()](#getEscapement--) | Zwraca tekst w formie indeksu górnego lub dolnego. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Zwraca minimalny rozmiar czcionki, przy którym powinno być włączone kerning. |
| [getLanguageId()](#getLanguageId--) | Zwraca identyfikator języka. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Zwraca identyfikator języka alternatywnego. |
| [getSpacing()](#getSpacing--) | Zwraca przyrost odstępu między znakami, w punktach. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

Zwraca właściwości LineFormat dla obramowania tekstu. Tylko do odczytu [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Zwraca:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Zwraca właściwości FillFormat tekstu. Tylko do odczytu [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Zwraca:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

Zwraca właściwości EffectFormat tekstu. Tylko do odczytu [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Zwraca:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Integer getHighlightColor()
```

Zwraca kolor używany do podświetlenia tekstu. Tylko do odczytu java.lang.Integer.

**Zwraca:**
java.lang.Integer
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

Zwraca właściwości LineFormat używane do obramowania linii podkreślenia. Tylko do odczytu [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Zwraca:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

Zwraca właściwości FillFormat linii podkreślenia. Tylko do odczytu [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Zwraca:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

Określa, czy czcionka jest pogrubiona. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

Określa, czy czcionka jest pochyła. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

Określa, czy liczby powinny ignorować specyficzny dla wschodnich języków pionowy układ tekstu. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

Określa, czy wysokość tekstu powinna być normalizowana. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

Określa, czy tekst nie powinien być sprawdzany. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Zwraca typ podkreślenia tekstu. Tylko do odczytu [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Zwraca:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Zwraca typ kapitalizacji tekstu. Tylko do odczytu [TextCapType](../../com.aspose.slides/textcaptype).

**Zwraca:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Zwraca typ przekreślenia tekstu. Tylko do odczytu [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Zwraca:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Określa, czy znacznik inteligentny powinien być wyczyszczony. Tylko do odczytu boolean.

**Zwraca:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

Określa, czy styl podkreślenia ma własne właściwości LineFormat czy dziedziczy je z właściwości LineFormat tekstu. Tylko do odczytu boolean.

**Zwraca:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

Określa, czy styl podkreślenia ma własne właściwości FillFormat czy dziedziczy je z właściwości FillFormat tekstu. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Zwraca wysokość czcionki fragmentu tekstu, w punktach. Tylko do odczytu float.

**Zwraca:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Zwraca informacje o czcionce łacińskiej. Tylko do odczytu [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Zwraca informacje o czcionce wschodnioazjatyckiej. Tylko do odczytu [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Zwraca informacje o czcionce skryptu złożonego. Tylko do odczytu [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Zwraca informacje o czcionce symbolicznej. Tylko do odczytu [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Zwraca tekst w formie indeksu górnego lub dolnego. Wartość od -100 % (indeks dolny) do 100 % (indeks górny). Tylko do odczytu float.

**Zwraca:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Zwraca minimalny rozmiar czcionki, przy którym powinno być włączone kerning. Tylko do odczytu float.

**Zwraca:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Zwraca identyfikator języka. Tylko do odczytu String.

**Zwraca:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Zwraca identyfikator języka alternatywnego. Tylko do odczytu String.

**Zwraca:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Zwraca przyrost odstępu między znakami, w punktach. Tylko do odczytu float.

**Zwraca:**
float