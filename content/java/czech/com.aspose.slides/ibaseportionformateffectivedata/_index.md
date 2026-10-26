---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Základní rozhraní pro neměnitelné objekty, které obsahují efektivní vlastnosti formátování textových částí.
type: docs
url: /cs/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Základní rozhraní pro neměnitelné objekty, které obsahují efektivní vlastnosti formátování textových částí.
## Metody

| Metoda | Popis |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Vrací vlastnosti LineFormat pro obrysování textu. |
| [getFillFormat()](#getFillFormat--) | Vrací vlastnosti FillFormat textu. |
| [getEffectFormat()](#getEffectFormat--) | Vrací vlastnosti EffectFormat textu. |
| [getHighlightColor()](#getHighlightColor--) | Vrací barvu použité k zvýraznění textu. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Vrací vlastnosti LineFormat použité k obrysování podtržité čáry. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Vrací vlastnosti FillFormat podtržité čáry. |
| [getFontBold()](#getFontBold--) | Určuje, zda je písmo tučné. |
| [getFontItalic()](#getFontItalic--) | Určuje, zda je písmo kurzívou. |
| [getKumimoji()](#getKumimoji--) | Určuje, zda mají čísla ignorovat vertikální rozvržení textu specifické pro východoasijské jazyky. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Určuje, zda má být výška textu normalizována. |
| [getProofDisabled()](#getProofDisabled--) | Určuje, zda text nemá být kontrolován. |
| [getFontUnderline()](#getFontUnderline--) | Vrací typ podtržení textu. |
| [getTextCapType()](#getTextCapType--) | Vrací typ kapitálkování textu. |
| [getStrikethroughType()](#getStrikethroughType--) | Vrací typ přeškrtnutí textu. |
| [getSmartTagClean()](#getSmartTagClean--) | Určuje, zda má být chytrá značka vyčištěna. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Určuje, zda styl podtržení má vlastní vlastnosti LineFormat nebo je dědí z vlastností LineFormat textu. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Určuje, zda styl podtržení má vlastní vlastnosti FillFormat nebo je dědí z vlastností FillFormat textu. |
| [getFontHeight()](#getFontHeight--) | Vrací výšku písma textové části v bodech. |
| [getLatinFont()](#getLatinFont--) | Vrací informace o latinském písmu. |
| [getEastAsianFont()](#getEastAsianFont--) | Vrací informace o východoasijském písmu. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Vrací informace o písmech komplexních skriptů. |
| [getSymbolFont()](#getSymbolFont--) | Vrací informace o symbolickém písmu. |
| [getEscapement()](#getEscapement--) | Vrací text jako horní index nebo dolní index. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Vrací minimální velikost písma, pro kterou má být zapnuté kerning. |
| [getLanguageId()](#getLanguageId--) | Vrací identifikátor jazyka. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Vrací identifikátor alternativního jazyka. |
| [getSpacing()](#getSpacing--) | Vrací přírůstek mezery mezi znaky v bodech. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

Vrací vlastnosti LineFormat pro obrysování textu. Read-only [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Vrací:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Vrací vlastnosti FillFormat textu. Read-only [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Vrací:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

Vrací vlastnosti EffectFormat textu. Read-only [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Vrací:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```

Vrací barvu použité k zvýraznění textu. Read-only java.awt.Color.

**Vrací:**
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

Vrací vlastnosti LineFormat použité k obrysování podtržité čáry. Read-only [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Vrací:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

Vrací vlastnosti FillFormat podtržité čáry. Read-only [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Vrací:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

Určuje, zda je písmo tučné. Read-only boolean.

**Vrací:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

Určuje, zda je písmo kurzívou. Read-only boolean.

**Vrací:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

Určuje, zda mají čísla ignorovat vertikální rozvržení textu specifické pro východoasijské jazyky. Read-only boolean.

**Vrací:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

Určuje, zda má být výška textu normalizována. Read-only boolean.

**Vrací:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

Určuje, zda text nemá být kontrolován. Read-only boolean.

**Vrací:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Vrací typ podtržení textu. Read-only [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Vrací:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Vrací typ kapitálkování textu. Read-only [TextCapType](../../com.aspose.slides/textcaptype).

**Vrací:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Vrací typ přeškrtnutí textu. Read-only [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Vrací:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Určuje, zda má být chytrá značka vyčištěna. Read-only boolean.

**Vrací:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

Určuje, zda styl podtržení má vlastní vlastnosti LineFormat nebo je dědí z vlastností LineFormat textu. Read-only boolean.

**Vrací:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

Určuje, zda styl podtržení má vlastní vlastnosti FillFormat nebo je dědí z vlastností FillFormat textu. Read-only boolean.

**Vrací:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Vrací výšku písma textové části v bodech. Read-only float.

**Vrací:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Vrací informace o latinském písmu. Read-only [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Vrací informace o východoasijském písmu. Read-only [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Vrací informace o písmech komplexních skriptů. Read-only [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Vrací informace o symbolickém písmu. Read-only [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Vrací text jako horní index nebo dolní index. Hodnota od -100 % (dolní index) do 100 % (horní index). Read-only float.

**Vrací:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Vrací minimální velikost písma, pro kterou má být zapnuté kerning. Read-only float.

**Vrací:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Vrací identifikátor jazyka. Read-only String.

**Vrací:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Vrací identifikátor alternativního jazyka. Read-only String.

**Vrací:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Vrací přírůstek mezery mezi znaky v bodech. Read-only float.

**Vrací:**
float