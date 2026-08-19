---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Basgränssnitt för oföränderliga objekt som innehåller effektiva formateringsegenskaper för textavsnitt.
type: docs
url: /sv/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Basgränssnitt för oföränderliga objekt som innehåller effektiva formateringsegenskaper för textavsnitt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Returnerar LineFormat-egenskaperna för textkontur. |
| [getFillFormat()](#getFillFormat--) | Returnerar FillFormat-egenskaperna för texten. |
| [getEffectFormat()](#getEffectFormat--) | Returnerar EffectFormat-egenskaperna för texten. |
| [getHighlightColor()](#getHighlightColor--) | Returnerar färgen som används för att markera text. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Returnerar LineFormat-egenskaperna som används för att omringa understrykningslinjen. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Returnerar FillFormat-egenskaperna för understrykningslinjen. |
| [getFontBold()](#getFontBold--) | Bestämmer om typsnittet är fetstil. |
| [getFontItalic()](#getFontItalic--) | Bestämmer om typsnittet är kursivt. |
| [getKumimoji()](#getKumimoji--) | Bestämmer om siffror ska ignorera textens östasiatiska språk-specifika vertikala layout. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Bestämmer om höjden på texten ska normaliseras. |
| [getProofDisabled()](#getProofDisabled--) | Bestämmer om texten inte ska korrekturläsas. |
| [getFontUnderline()](#getFontUnderline--) | Returnerar typen av textunderstrykning. |
| [getTextCapType()](#getTextCapType--) | Returnerar typen av textversalisering. |
| [getStrikethroughType()](#getStrikethroughType--) | Returnerar genomstrykningstypen för en text. |
| [getSmartTagClean()](#getSmartTagClean--) | Bestämmer om smart-taggen ska rensas. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Bestämmer om understrykningsstilen har egna LineFormat-egenskaper eller ärver dem från textens LineFormat-egenskaper. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Bestämmer om understrykningsstilen har egna FillFormat-egenskaper eller ärver dem från textens FillFormat-egenskaper. |
| [getFontHeight()](#getFontHeight--) | Returnerar typsnittshöjden för textavsnittet, i punkter. |
| [getLatinFont()](#getLatinFont--) | Returnerar information om latinskt typsnitt. |
| [getEastAsianFont()](#getEastAsianFont--) | Returnerar information om östasiatiskt typsnitt. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Returnerar information om komplex skript-typsnitt. |
| [getSymbolFont()](#getSymbolFont--) | Returnerar information om symboliskt typsnitt. |
| [getEscapement()](#getEscapement--) | Returnerar text som är upphöjd eller nedsänkt. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Returnerar den minsta typsnittsstorleken för vilken kerning ska aktiveras. |
| [getLanguageId()](#getLanguageId--) | Returnerar Id för ett språk. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Returnerar Id för ett alternativt språk. |
| [getSpacing()](#getSpacing--) | Returnerar teckentågsavståndsincrementet, i punkter. |
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

Returnerar FillFormat-egenskaperna för texten. Skrivskyddad [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Returnerar:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

Returnerar EffectFormat-egenskaperna för texten. Skrivskyddad [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Returnerar:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```

Returnerar färgen som används för att markera text. Skrivskyddad java.awt.Color.

**Returnerar:**
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

Returnerar LineFormat-egenskaperna som används för att omringa understrykningslinjen. Skrivskyddad [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Returnerar:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

Returnerar FillFormat-egenskaperna för understrykningslinjen. Skrivskyddad [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Returnerar:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

Bestämmer om typsnittet är fetstil. Skrivskyddad boolean.

**Returnerar:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

Bestämmer om typsnittet är kursivt. Skrivskyddad boolean.

**Returnerar:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

Bestämmer om siffror ska ignorera textens östasiatiska språk-specifika vertikala layout. Skrivskyddad boolean.

**Returnerar:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

Bestämmer om höjden på texten ska normaliseras. Skrivskyddad boolean.

**Returnerar:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

Bestämmer om texten inte ska korrekturläsas. Skrivskyddad boolean.

**Returnerar:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Returnerar typen av textunderstrykning. Skrivskyddad [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Returnerar:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Returnerar typen av textversalisering. Skrivskyddad [TextCapType](../../com.aspose.slides/textcaptype).

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

Bestämmer om smart-taggen ska rensas. Skrivskyddad boolean.

**Returnerar:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

Bestämmer om understrykningsstilen har egna LineFormat-egenskaper eller ärver dem från textens LineFormat-egenskaper. Skrivskyddad boolean.

**Returnerar:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

Bestämmer om understrykningsstilen har egna FillFormat-egenskaper eller ärver dem från textens FillFormat-egenskaper. Skrivskyddad boolean.

**Returnerar:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Returnerar typsnittshöjden för textavsnittet, i punkter. Skrivskyddad float.

**Returnerar:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Returnerar information om latinskt typsnitt. Skrivskyddad [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Returnerar information om östasiatiskt typsnitt. Skrivskyddad [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Returnerar information om komplex skript-typsnitt. Skrivskyddad [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Returnerar information om symboliskt typsnitt. Skrivskyddad [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Returnerar text som är upphöjd eller nedsänkt. Värde från -100 % (nedsänkt) till 100 % (upphöjd). Skrivskyddad float.

**Returnerar:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Returnerar den minsta typsnittsstorleken för vilken kerning ska aktiveras. Skrivskyddad float.

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

Returnerar teckentågsavståndsincrementet, i punkter. Skrivskyddad float.

**Returnerar:**
float