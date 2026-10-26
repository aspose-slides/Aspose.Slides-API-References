---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Interfaccia base per oggetti immutabili che contengono le proprietà di formattazione effettiva delle porzioni di testo.
type: docs
url: /it/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Interfaccia base per oggetti immutabili che contengono le proprietà di formattazione effettiva delle porzioni di testo.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Restituisce le proprietà LineFormat per il contorno del testo. |
| [getFillFormat()](#getFillFormat--) | Restituisce le proprietà FillFormat del testo. |
| [getEffectFormat()](#getEffectFormat--) | Restituisce le proprietà EffectFormat del testo. |
| [getHighlightColor()](#getHighlightColor--) | Restituisce il colore usato per evidenziare un testo. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Restituisce le proprietà LineFormat usate per delineare la linea di sottolineatura. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Restituisce le proprietà FillFormat della linea di sottolineatura. |
| [getFontBold()](#getFontBold--) | Determina se il carattere è in grassetto. |
| [getFontItalic()](#getFontItalic--) | Determina se il carattere è in corsivo. |
| [getKumimoji()](#getKumimoji--) | Determina se i numeri devono ignorare il layout verticale specifico per le lingue orientali del testo. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Determina se l'altezza di un testo deve essere normalizzata. |
| [getProofDisabled()](#getProofDisabled--) | Determina se il testo non deve essere corretto. |
| [getFontUnderline()](#getFontUnderline--) | Restituisce il tipo di sottolineatura del testo. |
| [getTextCapType()](#getTextCapType--) | Restituisce il tipo di capitalizzazione del testo. |
| [getStrikethroughType()](#getStrikethroughType--) | Restituisce il tipo di barrato di un testo. |
| [getSmartTagClean()](#getSmartTagClean--) | Determina se il tag intelligente deve essere pulito. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Determina se lo stile di sottolineatura ha proprie proprietà LineFormat o le eredita dalle proprietà LineFormat del testo. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Determina se lo stile di sottolineatura ha proprie proprietà FillFormat o le eredita dalle proprietà FillFormat del testo. |
| [getFontHeight()](#getFontHeight--) | Restituisce l'altezza del carattere della porzione di testo, in punti. |
| [getLatinFont()](#getLatinFont--) | Restituisce le informazioni sul font latino. |
| [getEastAsianFont()](#getEastAsianFont--) | Restituisce le informazioni sul font dell'Est asiatico. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Restituisce le informazioni sul font script complesso. |
| [getSymbolFont()](#getSymbolFont--) | Restituisce le informazioni sul font simbolico. |
| [getEscapement()](#getEscapement--) | Restituisce il testo in apice o pedice. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Restituisce la dimensione minima del carattere per cui il kerning deve essere attivato. |
| [getLanguageId()](#getLanguageId--) | Restituisce l'Id di una lingua. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Restituisce l'Id di una lingua alternativa. |
| [getSpacing()](#getSpacing--) | Restituisce l'incremento di spaziatura intercarattere, in punti. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```


Restituisce le proprietà LineFormat per il contorno del testo. Solo lettura [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Restituisce:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Restituisce le proprietà FillFormat del testo. Solo lettura [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Restituisce:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


Restituisce le proprietà EffectFormat del testo. Solo lettura [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Restituisce:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```


Restituisce il colore usato per evidenziare un testo. Solo lettura java.awt.Color.

**Restituisce:**
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```


Restituisce le proprietà LineFormat usate per delineare la linea di sottolineatura. Solo lettura [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Restituisce:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```


Restituisce le proprietà FillFormat della linea di sottolineatura. Solo lettura [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Restituisce:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```


Determina se il carattere è in grassetto. Solo lettura boolean.

**Restituisce:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```


Determina se il carattere è in corsivo. Solo lettura boolean.

**Restituisce:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```


Determina se i numeri devono ignorare il layout verticale specifico per le lingue orientali del testo. Solo lettura boolean.

**Restituisce:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```


Determina se l'altezza di un testo deve essere normalizzata. Solo lettura boolean.

**Restituisce:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```


Determina se il testo non deve essere corretto. Solo lettura boolean.

**Restituisce:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


Restituisce il tipo di sottolineatura del testo. Solo lettura [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Restituisce:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


Restituisce il tipo di capitalizzazione del testo. Solo lettura [TextCapType](../../com.aspose.slides/textcaptype).

**Restituisce:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


Restituisce il tipo di barrato di un testo. Solo lettura [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Restituisce:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


Determina se il tag intelligente deve essere pulito. Solo lettura boolean.

**Restituisce:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```


Determina se lo stile di sottolineatura ha proprie proprietà LineFormat o le eredita dalle proprietà LineFormat del testo. Solo lettura boolean.

**Restituisce:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```


Determina se lo stile di sottolineatura ha proprie proprietà FillFormat o le eredita dalle proprietà FillFormat del testo. Solo lettura boolean.

**Restituisce:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


Restituisce l'altezza del carattere della porzione di testo, in punti. Solo lettura float.

**Restituisce:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Restituisce le informazioni sul font latino. Solo lettura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Restituisce le informazioni sul font dell'Est asiatico. Solo lettura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Restituisce le informazioni sul font script complesso. Solo lettura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


Restituisce le informazioni sul font simbolico. Solo lettura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


Restituisce il testo in apice o pedice. Valore da -100 % (pedice) a 100 % (apice). Solo lettura float.

**Restituisce:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


Restituisce la dimensione minima del carattere per cui il kerning deve essere attivato. Solo lettura float.

**Restituisce:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```


Restituisce l'Id di una lingua. Solo lettura String.

**Restituisce:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```


Restituisce l'Id di una lingua alternativa. Solo lettura String.

**Restituisce:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


Restituisce l'incremento di spaziatura intercarattere, in punti. Solo lettura float.

**Restituisce:**
float