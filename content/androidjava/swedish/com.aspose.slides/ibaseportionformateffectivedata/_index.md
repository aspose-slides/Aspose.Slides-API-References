---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Basgränssnitt för oföränderliga objekt som innehåller effektiva format-egenskaper för textdelar.
type: docs
url: /sv/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Basgränssnitt för oföränderliga objekt som innehåller effektiva format-egenskaper för textdelar.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Returnerar LineFormat-egenskaperna för textkontur. |
| [getFillFormat()](#getFillFormat--) | Returnerar textens FillFormat-egenskaper. |
| [getEffectFormat()](#getEffectFormat--) | Returnerar textens EffectFormat-egenskaper. |
| [getHighlightColor()](#getHighlightColor--) | Returnerar färgen som används för att markera en text. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Returnerar LineFormat-egenskaperna som används för att konturera understrykning. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Returnerar understrykningens FillFormat-egenskaper. |
| [getFontBold()](#getFontBold--) | Avgör om teckensnittet är fetstil. |
| [getFontItalic()](#getFontItalic--) | Avgör om teckensnittet är kursiv. |
| [getKumimoji()](#getKumimoji--) | Avgör om siffrorna ska ignorera textens östasiatiska språkspecifika vertikala layout. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Avgör om höjden på en text ska normaliseras. |
| [getProofDisabled()](#getProofDisabled--) | Avgör om texten inte ska korrekturläsas. |
| [getFontUnderline()](#getFontUnderline--) | Returnerar textens understrykningstyp. |
| [getTextCapType()](#getTextCapType--) | Returnerar typen av textversaler. |
| [getStrikethroughType()](#getStrikethroughType--) | Returnerar genomstrykningstypen för en text. |
| [getSmartTagClean()](#getSmartTagClean--) | Avgör om smart-taggen ska rensas. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Avgör om understrykningens stil har egna LineFormat-egenskaper eller ärver dem från textens LineFormat-egenskaper. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Avgör om understrykningens stil har egna FillFormat-egenskaper eller ärver dem från textens FillFormat-egenskaper. |
| [getFontHeight()](#getFontHeight--) | Returnerar teckensnittets höjd för textdelen, i punkter. |
| [getLatinFont()](#getLatinFont--) | Returnerar information om det latinska teckensnittet. |
| [getEastAsianFont()](#getEastAsianFont--) | Returnerar information om det östasiatiska teckensnittet. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Returnerar information om det komplexa skriptteckensnittet. |
| [getSymbolFont()](#getSymbolFont--) | Returnerar information om det symboliska teckensnittet. |
| [getEscapement()](#getEscapement--) | Returnerar text i upphöjd eller nedsänkt stil. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Returnerar minimal teckensnittsstorlek för vilken kerning ska aktiveras. |
| [getLanguageId()](#getLanguageId--) | Returnerar Id för ett språk. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Returnerar Id för ett alternativt språk. |
| [getSpacing()](#getSpacing--) | Returnerar avståndsökning mellan tecken, i punkter. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```


Returnerar LineFormat-egenskaperna för textkontur. Skrivskyddad [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Returnerar:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Returnerar textens FillFormat-egenskaper. Skrivskyddad [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Returnerar:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


Returnerar textens EffectFormat-egenskaper. Skrivskyddad [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Returnerar:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Integer getHighlightColor()
```


Returnerar färgen som används för att markera en text. Skrivskyddad java.lang.Integer.

**Returnerar:**
java.lang.Integer
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```


Returnerar LineFormat-egenskaperna som används för att konturera understrykning. Skrivskyddad [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Returnerar:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```


Returnerar understrykningens FillFormat-egenskaper. Skrivskyddad [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Returnerar:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```


Avgör om teckensnittet är fetstil. Skrivskyddad boolean.

**Returnerar:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```


Avgör om teckensnittet är kursiv. Skrivskyddad boolean.

**Returnerar:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```


Avgör om siffrorna ska ignorera textens östasiatiska språkspecifika vertikala layout. Skrivskyddad boolean.

**Returnerar:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```


Avgör om höjden på en text ska normaliseras. Skrivskyddad boolean.

**Returnerar:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```


Avgör om texten inte ska korrekturläsas. Skrivskyddad boolean.

**Returnerar:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


Returnerar textens understrykningstyp. Skrivskyddad [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Returnerar:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


Returnerar typen av textversaler. Skrivskyddad [TextCapType](../../com.aspose.slides/textcaptype).

**Returnerar:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


Returnerar genomstrykningstypen för en text. Skrivskyddad [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Returnerar:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


Avgör om smart-taggen ska rensas. Skrivskyddad boolean.

**Returnerar:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```


Avgör om understrykningens stil har egna LineFormat-egenskaper eller ärver dem från textens LineFormat-egenskaper. Skrivskyddad boolean.

**Returnerar:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```


Avgör om understrykningens stil har egna FillFormat-egenskaper eller ärver dem från textens FillFormat-egenskaper. Skrivskyddad boolean.

**Returnerar:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


Returnerar teckensnittets höjd för textdelen, i punkter. Skrivskyddad float.

**Returnerar:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Returnerar information om det latinska teckensnittet. Skrivskyddad [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Returnerar information om det östasiatiska teckensnittet. Skrivskyddad [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Returnerar information om det komplexa skriptteckensnittet. Skrivskyddad [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


Returnerar information om det symboliska teckensnittet. Skrivskyddad [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


Returnerar text i upphöjd eller nedsänkt stil. Värde från -100 % (nedsänkt) till 100 % (upphöjd). Skrivskyddad float.

**Returnerar:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


Returnerar minimal teckensnittsstorlek för vilken kerning ska aktiveras. Skrivskyddad float.

**Returnerar:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```


Returnerar Id för ett språk. Skrivskyddad String.

**Returnerar:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```


Returnerar Id för ett alternativt språk. Skrivskyddad String.

**Returnerar:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


Returnerar avståndsökning mellan tecken, i punkter. Skrivskyddad float.

**Returnerar:**
float