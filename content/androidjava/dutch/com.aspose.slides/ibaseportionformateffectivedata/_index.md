---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Android via Java API-referentie
description: Basisinterface voor onveranderlijke objecten die effectieve opmaakeigenschappen van tekstgedeelten bevatten.
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
| [getFillFormat()](#getFillFormat--) | Retourneert de FillFormat-eigenschappen van de tekst. |
| [getEffectFormat()](#getEffectFormat--) | Retourneert de EffectFormat-eigenschappen van de tekst. |
| [getHighlightColor()](#getHighlightColor--) | Retourneert de kleur die wordt gebruikt om tekst te markeren. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstrepingslijn te omlijnen. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Retourneert de FillFormat-eigenschappen van de onderstrepingslijn. |
| [getFontBold()](#getFontBold--) | Bepaalt of het lettertype vet is. |
| [getFontItalic()](#getFontItalic--) | Bepaalt of het lettertype cursief is. |
| [getKumimoji()](#getKumimoji--) | Bepaalt of de getallen de oosterse specifieke verticale lay-out van de tekst moeten negeren. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. |
| [getProofDisabled()](#getProofDisabled--) | Bepaalt of de tekst niet geproofd moet worden. |
| [getFontUnderline()](#getFontUnderline--) | Retourneert het type onderstreping van de tekst. |
| [getTextCapType()](#getTextCapType--) | Retourneert het type hoofdlettergebruik van de tekst. |
| [getStrikethroughType()](#getStrikethroughType--) | Retourneert het type doorhaling van een tekst. |
| [getSmartTagClean()](#getSmartTagClean--) | Bepaalt of de slimme tag moet worden opgeschoond. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Bepaalt of de onderstrepingsstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Bepaalt of de onderstrepingsstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. |
| [getFontHeight()](#getFontHeight--) | Retourneert de letterhoogte van het tekstdelen, in punten. |
| [getLatinFont()](#getLatinFont--) | Retourneert de informatie over het Latijnse lettertype. |
| [getEastAsianFont()](#getEastAsianFont--) | Retourneert de informatie over het Oost-Aziatische lettertype. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Retourneert de informatie over het complexe scriptlettertype. |
| [getSymbolFont()](#getSymbolFont--) | Retourneert de informatie over het symbolische lettertype. |
| [getEscapement()](#getEscapement--) | Retourneert de superscript- of subscript-tekst. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Retourneert de minimale lettergrootte waarvoor kerning moet worden ingeschakeld. |
| [getLanguageId()](#getLanguageId--) | Retourneert de Id van een taal. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Retourneert de Id van een alternatieve taal. |
| [getSpacing()](#getSpacing--) | Retourneert de tussen-karakterafstandstoename, in punten. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```


Retourneert de LineFormat-eigenschappen voor tekstomlijning. Alleen-lezen [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Retourneert:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Retourneert de FillFormat-eigenschappen van de tekst. Alleen-lezen [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Retourneert:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


Retourneert de EffectFormat-eigenschappen van de tekst. Alleen-lezen [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Retourneert:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Integer getHighlightColor()
```


Retourneert de kleur die wordt gebruikt om tekst te markeren. Alleen-lezen java.lang.Integer.

**Retourneert:**
java.lang.Integer
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```


Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstrepingslijn te omlijnen. Alleen-lezen [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Retourneert:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```


Retourneert de FillFormat-eigenschappen van de onderstrepingslijn. Alleen-lezen [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Retourneert:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```


Bepaalt of het lettertype vet is. Alleen-lezen boolean.

**Retourneert:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```


Bepaalt of het lettertype cursief is. Alleen-lezen boolean.

**Retourneert:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```


Bepaalt of de getallen de oosterse specifieke verticale lay-out van de tekst moeten negeren. Alleen-lezen boolean.

**Retourneert:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```


Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Alleen-lezen boolean.

**Retourneert:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```


Bepaalt of de tekst niet geproofd moet worden. Alleen-lezen boolean.

**Retourneert:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


Retourneert het type onderstreping van de tekst. Alleen-lezen [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Retourneert:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


Retourneert het type hoofdlettergebruik van de tekst. Alleen-lezen [TextCapType](../../com.aspose.slides/textcaptype).

**Retourneert:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


Retourneert het type doorhaling van een tekst. Alleen-lezen [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Retourneert:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


Bepaalt of de slimme tag moet worden opgeschoond. Alleen-lezen boolean.

**Retourneert:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```


Bepaalt of de onderstrepingsstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Alleen-lezen boolean.

**Retourneert:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```


Bepaalt of de onderstrepingsstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Alleen-lezen boolean.

**Retourneert:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


Retourneert de letterhoogte van het tekstdelen, in punten. Alleen-lezen float.

**Retourneert:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Retourneert de informatie over het Latijnse lettertype. Alleen-lezen [IFontData](../../com.aspose.slides/ifontdata).

**Retourneert:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Retourneert de informatie over het Oost-Aziatische lettertype. Alleen-lezen [IFontData](../../com.aspose.slides/ifontdata).

**Retourneert:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Retourneert de informatie over het complexe scriptlettertype. Alleen-lezen [IFontData](../../com.aspose.slides/ifontdata).

**Retourneert:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


Retourneert de informatie over het symbolische lettertype. Alleen-lezen [IFontData](../../com.aspose.slides/ifontdata).

**Retourneert:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


Retourneert de superscript- of subscript-tekst. Waarde van -100 % (subscript) tot 100 % (superscript). Alleen-lezen float.

**Retourneert:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


Retourneert de minimale lettergrootte waarvoor kerning moet worden ingeschakeld. Alleen-lezen float.

**Retourneert:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```


Retourneert de Id van een taal. Alleen-lezen String.

**Retourneert:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```


Retourneert de Id van een alternatieve taal. Alleen-lezen String.

**Retourneert:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


Retourneert de tussen-karakterafstandstoename, in punten. Alleen-lezen float.

**Retourneert:**
float