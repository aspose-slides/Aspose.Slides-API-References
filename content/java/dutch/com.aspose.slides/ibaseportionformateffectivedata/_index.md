---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Basisinterface voor onveranderlijke objecten die effectieve opmaak-eigenschappen van tekstgedeelten bevatten.
type: docs
url: /nl/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Basisinterface voor onveranderlijke objecten die effectieve opmaak-eigenschappen van tekstgedeelten bevatten.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Retourneert de LineFormat-eigenschappen voor tekstomlijning. |
| [getFillFormat()](#getFillFormat--) | Retourneert de tekst-FillFormat-eigenschappen. |
| [getEffectFormat()](#getEffectFormat--) | Retourneert de tekst-EffectFormat-eigenschappen. |
| [getHighlightColor()](#getHighlightColor--) | Retourneert de kleur die wordt gebruikt om een tekst te markeren. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstreeplijn te omlijnen. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Retourneert de FillFormat-eigenschappen van de onderstreeplijn. |
| [getFontBold()](#getFontBold--) | Bepaalt of het lettertype vet is. |
| [getFontItalic()](#getFontItalic--) | Bepaalt of het lettertype cursief is. |
| [getKumimoji()](#getKumimoji--) | Bepaalt of de cijfers de oosterse, taalspecifieke verticale tekstlay-out moeten negeren. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. |
| [getProofDisabled()](#getProofDisabled--) | Bepaalt of de tekst niet moet worden proeflezen. |
| [getFontUnderline()](#getFontUnderline--) | Retourneert het onderlijntype van de tekst. |
| [getTextCapType()](#getTextCapType--) | Retourneert het type hoofdlettergebruik van de tekst. |
| [getStrikethroughType()](#getStrikethroughType--) | Retourneert het doorhaltype van een tekst. |
| [getSmartTagClean()](#getSmartTagClean--) | Bepaalt of de slimme tag moet worden opgeschoond. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Bepaalt of de onderstreeptstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Bepaalt of de onderstreeptstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. |
| [getFontHeight()](#getFontHeight--) | Retourneert de letterhoogte van het tekstgedeelte, in punten. |
| [getLatinFont()](#getLatinFont--) | Retourneert de informatie over het Latijnse lettertype. |
| [getEastAsianFont()](#getEastAsianFont--) | Retourneert de informatie over het Oost-Aziatische lettertype. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Retourneert de informatie over het complexe scriptlettertype. |
| [getSymbolFont()](#getSymbolFont--) | Retourneert de informatie over het symbolische lettertype. |
| [getEscapement()](#getEscapement--) | Retourneert de superscript- of subscript-tekst. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Retourneert de minimale lettergrootte waarvoor kerning moet worden ingeschakeld. |
| [getLanguageId()](#getLanguageId--) | Retourneert de Id van een taal. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Retourneert de Id van een alternatieve taal. |
| [getSpacing()](#getSpacing--) | Retourneert de interkarakter-spatiëringsincrement, in punten. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```


Retourneert de LineFormat-eigenschappen voor tekstomlijning. Alleen-lezen [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Returns:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Retourneert de tekst-FillFormat-eigenschappen. Alleen-lezen [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Returns:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


Retourneert de tekst-EffectFormat-eigenschappen. Alleen-lezen [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Returns:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```


Retourneert de kleur die wordt gebruikt om een tekst te markeren. Alleen-lezen java.awt.Color.

**Returns:**
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```


Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstreeplijn te omlijnen. Alleen-lezen [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Returns:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```


Retourneert de FillFormat-eigenschappen van de onderstreeplijn. Alleen-lezen [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Returns:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```


Bepaalt of het lettertype vet is. Alleen-lezen boolean.

**Returns:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```


Bepaalt of het lettertype cursief is. Alleen-lezen boolean.

**Returns:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```


Bepaalt of de cijfers de oosterse, taalspecifieke verticale tekstlay-out moeten negeren. Alleen-lezen boolean.

**Returns:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```


Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Alleen-lezen boolean.

**Returns:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```


Bepaalt of de tekst niet moet worden proeflezen. Alleen-lezen boolean.

**Returns:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


Retourneert het onderlijntype van de tekst. Alleen-lezen [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Returns:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


Retourneert het type hoofdlettergebruik van de tekst. Alleen-lezen [TextCapType](../../com.aspose.slides/textcaptype).

**Returns:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


Retourneert het doorhaltype van een tekst. Alleen-lezen [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Returns:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


Bepaalt of de slimme tag moet worden opgeschoond. Alleen-lezen boolean.

**Returns:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```


Bepaalt of de onderstreeptstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Alleen-lezen boolean.

**Returns:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```


Bepaalt of de onderstreeptstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Alleen-lezen boolean.

**Returns:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


Retourneert de letterhoogte van het tekstgedeelte, in punten. Alleen-lezen float.

**Returns:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Retourneert de informatie over het Latijnse lettertype. Alleen-lezen [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Retourneert de informatie over het Oost-Aziatische lettertype. Alleen-lezen [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Retourneert de informatie over het complexe scriptlettertype. Alleen-lezen [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


Retourneert de informatie over het symbolische lettertype. Alleen-lezen [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


Retourneert de superscript- of subscript-tekst. Waarde van -100% (subscript) tot 100% (superscript). Alleen-lezen float.

**Returns:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


Retourneert de minimale lettergrootte waarvoor kerning moet worden ingeschakeld. Alleen-lezen float.

**Returns:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```


Retourneert de Id van een taal. Alleen-lezen String.

**Returns:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```


Retourneert de Id van een alternatieve taal. Alleen-lezen String.

**Returns:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


Retourneert de interkarakter-spatiëringsincrement, in punten. Alleen-lezen float.

**Returns:**
float