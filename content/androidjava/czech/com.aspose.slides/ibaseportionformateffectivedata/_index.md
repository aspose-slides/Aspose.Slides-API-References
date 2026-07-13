---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides pro Android přes Java API Reference
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
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Vrací vlastnosti LineFormat použité k obrysování podtržené čáry. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Vrací vlastnosti FillFormat podtržené čáry. |
| [getFontBold()](#getFontBold--) | Určuje, zda je písmo tučné. |
| [getFontItalic()](#getFontItalic--) | Určuje, zda je písmo kurzíva. |
| [getKumimoji()](#getKumimoji--) | Určuje, zda čísla mají ignorovat specifické svislé rozložení textu pro východoasijské jazyky. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Určuje, zda výška textu má být normalizována. |
| [getProofDisabled()](#getProofDisabled--) | Určuje, zda text nemá být kontrolován. |
| [getFontUnderline()](#getFontUnderline--) | Vrací typ podtržení textu. |
| [getTextCapType()](#getTextCapType--) | Vrací typ kapitalizace textu. |
| [getStrikethroughType()](#getStrikethroughType--) | Vrací typ přeškrtnutí textu. |
| [getSmartTagClean()](#getSmartTagClean--) | Určuje, zda má být inteligentní značka vyčištěna. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Určuje, zda styl podtržení má vlastní vlastnosti LineFormat nebo je dědí z vlastností LineFormat textu. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Určuje, zda styl podtržení má vlastní vlastnosti FillFormat nebo je dědí z vlastností FillFormat textu. |
| [getFontHeight()](#getFontHeight--) | Vrací výšku písma textové části v bodech. |
| [getLatinFont()](#getLatinFont--) | Vrací informace o latinském písmu. |
| [getEastAsianFont()](#getEastAsianFont--) | Vrací informace o východoasijském písmu. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Vrací informace o písmu pro komplexní skript. |
| [getSymbolFont()](#getSymbolFont--) | Vrací informace o symbolickém písmu. |
| [getEscapement()](#getEscapement--) | Vrací text v podobě horního nebo dolního indexu. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Vrací minimální velikost písma, pro kterou má být zapnuté kerning. |
| [getLanguageId()](#getLanguageId--) | Vrací ID jazyka. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Vrací ID alternativního jazyka. |
| [getSpacing()](#getSpacing--) | Vrací přírůstek mezery mezi znaky v bodech. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```


Vrací vlastnosti LineFormat pro obrysování textu. Pouze pro čtení [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Vrací:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Vrací vlastnosti FillFormat textu. Pouze pro čtení [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Vrací:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


Vrací vlastnosti EffectFormat textu. Pouze pro čtení [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Vrací:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Integer getHighlightColor()
```


Vrací barvu použitou pro zvýraznění textu. Pouze pro čtení java.lang.Integer.

**Vrací:**
java.lang.Integer
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```


Vrací vlastnosti LineFormat použité k obrysování podtržené čáry. Pouze pro čtení [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Vrací:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```


Vrací vlastnosti FillFormat podtržené čáry. Pouze pro čtení [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Vrací:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```


Určuje, zda je písmo tučné. Pouze pro čtení boolean.

**Vrací:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```


Určuje, zda je písmo kurzíva. Pouze pro čtení boolean.

**Vrací:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```


Určuje, zda čísla mají ignorovat specifické svislé rozložení textu pro východoasijské jazyky. Pouze pro čtení boolean.

**Vrací:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```


Určuje, zda výška textu má být normalizována. Pouze pro čtení boolean.

**Vrací:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```


Určuje, zda text nemá být kontrolován. Pouze pro čtení boolean.

**Vrací:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


Vrací typ podtržení textu. Pouze pro čtení [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Vrací:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


Vrací typ kapitalizace textu. Pouze pro čtení [TextCapType](../../com.aspose.slides/textcaptype).

**Vrací:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


Vrací typ přeškrtnutí textu. Pouze pro čtení [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Vrací:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


Určuje, zda má být inteligentní značka vyčištěna. Pouze pro čtení boolean.

**Vrací:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```


Určuje, zda styl podtržení má vlastní vlastnosti LineFormat nebo je dědí z vlastností LineFormat textu. Pouze pro čtení boolean.

**Vrací:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```


Určuje, zda styl podtržení má vlastní vlastnosti FillFormat nebo je dědí z vlastností FillFormat textu. Pouze pro čtení boolean.

**Vrací:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


Vrací výšku písma textové části v bodech. Pouze pro čtení float.

**Vrací:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Vrací informace o latinském písmu. Pouze pro čtení [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Vrací informace o východoasijském písmu. Pouze pro čtení [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Vrací informace o písmu pro komplexní skript. Pouze pro čtení [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


Vrací informace o symbolickém písmu. Pouze pro čtení [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


Vrací text v podobě horního nebo dolního indexu. Hodnota od -100 % (dolní index) do 100 % (horní index). Pouze pro čtení float.

**Vrací:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


Vrací minimální velikost písma, pro kterou má být zapnuté kerning. Pouze pro čtení float.

**Vrací:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```


Vrací ID jazyka. Pouze pro čtení String.

**Vrací:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```


Vrací ID alternativního jazyka. Pouze pro čtení String.

**Vrací:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


Vrací přírůstek mezery mezi znaky v bodech. Pouze pro čtení float.

**Vrací:**
float