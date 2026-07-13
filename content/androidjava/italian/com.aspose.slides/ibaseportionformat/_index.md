---
title: IBasePortionFormat
second_title: Aspose.Slides per Android tramite Java API Reference
description: Questa classe contiene le proprietà di formattazione della porzione di testo.
type: docs
url: /it/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Questa classe contiene le proprietà di formattazione della porzione di testo. A differenza di [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), tutte le proprietà di questa classe sono modificabili.

--------------------

Questa classe è usata per restituire e manipolare le proprietà di formattazione della porzione di testo definite per la specifica porzione. Ciò significa che nessuna eredità viene applicata quando si ottengono i valori, quindi nella maggior parte dei casi otterrete valori che significano "undefined".

Per ottenere i valori dei parametri di formattazione efficaci, inclusi quelli ereditati, è necessario utilizzare il metodo [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) che restituisce un'istanza [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Restituisce le proprietà LineFormat per il contorno del testo. |
| [getFillFormat()](#getFillFormat--) | Restituisce le proprietà FillFormat del testo. |
| [getEffectFormat()](#getEffectFormat--) | Restituisce le proprietà EffectFormat del testo. |
| [getHighlightColor()](#getHighlightColor--) | Restituisce il colore usato per evidenziare un testo. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Restituisce le proprietà LineFormat usate per contornare la linea di sottolineatura. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Restituisce le proprietà FillFormat della linea di sottolineatura. |
| [getFontBold()](#getFontBold--) | Determina se il carattere è grassetto. |
| [setFontBold(byte value)](#setFontBold-byte-) | Determina se il carattere è grassetto. |
| [getFontItalic()](#getFontItalic--) | Determina se il carattere è italico. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Determina se il carattere è italico. |
| [getKumimoji()](#getKumimoji--) | Determina se i numeri devono ignorare il layout verticale specifico per lingua orientale del testo. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Determina se i numeri devono ignorare il layout verticale specifico per lingua orientale del testo. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Determina se l'altezza di un testo deve essere normalizzata. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Determina se l'altezza di un testo deve essere normalizzata. |
| [getProofDisabled()](#getProofDisabled--) | Determina se il testo non deve essere corretto. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Determina se il testo non deve essere corretto. |
| [getFontUnderline()](#getFontUnderline--) | Restituisce o imposta il tipo di sottolineatura del testo. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Restituisce o imposta il tipo di sottolineatura del testo. |
| [getTextCapType()](#getTextCapType--) | Restituisce o imposta il tipo di capitalizzazione del testo. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Restituisce o imposta il tipo di capitalizzazione del testo. |
| [getStrikethroughType()](#getStrikethroughType--) | Restituisce o imposta il tipo di barrato del testo. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Restituisce o imposta il tipo di barrato del testo. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Determina se lo stile di sottolineatura possiede proprie proprietà LineFormat o le eredita dalle proprietà LineFormat del testo. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Determina se lo stile di sottolineatura possiede proprie proprietà LineFormat o le eredita dalle proprietà LineFormat del testo. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Determina se lo stile di sottolineatura possiede proprie proprietà FillFormat o le eredita dalle proprietà FillFormat del testo. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Determina se lo stile di sottolineatura possiede proprie proprietà FillFormat o le eredita dalle proprietà FillFormat del testo. |
| [getFontHeight()](#getFontHeight--) | Restituisce o imposta l'altezza del carattere di una porzione. |
| [setFontHeight(float value)](#setFontHeight-float-) | Restituisce o imposta l'altezza del carattere di una porzione. |
| [getLatinFont()](#getLatinFont--) | Restituisce o imposta le informazioni sul font latino. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Restituisce o imposta le informazioni sul font latino. |
| [getEastAsianFont()](#getEastAsianFont--) | Restituisce o imposta le informazioni sul font dell'Est asiatico. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Restituisce o imposta le informazioni sul font dell'Est asiatico. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Restituisce o imposta le informazioni sul font di script complesso. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Restituisce o imposta le informazioni sul font di script complesso. |
| [getSymbolFont()](#getSymbolFont--) | Restituisce o imposta le informazioni sul font simbolico. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Restituisce o imposta le informazioni sul font simbolico. |
| [getEscapement()](#getEscapement--) | Restituisce o imposta il testo in apice o pedice. |
| [setEscapement(float value)](#setEscapement-float-) | Restituisce o imposta il testo in apice o pedice. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Restituisce o imposta la dimensione minima del carattere per cui l'kerning è attivato. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Restituisce o imposta la dimensione minima del carattere per cui l'kerning è attivato. |
| [getLanguageId()](#getLanguageId--) | Restituisce o imposta l'Id di una lingua di correzione. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Restituisce o imposta l'Id di una lingua di correzione. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Restituisce o imposta l'Id di una lingua alternativa. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Restituisce o imposta l'Id di una lingua alternativa. |
| [getSpacing()](#getSpacing--) | Restituisce o imposta l'incremento di spaziatura intercarattere. |
| [setSpacing(float value)](#setSpacing-float-) | Restituisce o imposta l'incremento di spaziatura intercarattere. |
| [getSpellCheck()](#getSpellCheck--) | Ottiene o imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Ottiene o imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Restituisce le proprietà LineFormat per il contorno del testo. Nessuna eredità applicata. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Restituisce le proprietà FillFormat del testo. Nessuna eredità applicata. Solo lettura [IFillFormat](../../com.aspose.slides/ifillformat).

**Restituisce:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Restituisce le proprietà EffectFormat del testo. Nessuna eredità applicata. Solo lettura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Restituisce:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Restituisce il colore usato per evidenziare un testo. Nessuna eredità applicata. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Restituisce le proprietà LineFormat usate per contornare la linea di sottolineatura. Nessuna eredità applicata. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Restituisce le proprietà FillFormat della linea di sottolineatura. Nessuna eredità applicata. Solo lettura [IFillFormat](../../com.aspose.slides/ifillformat).

**Restituisce:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Determina se il carattere è grassetto. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Determina se il carattere è grassetto. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Determina se il carattere è italico. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Determina se il carattere è italico. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Determina se i numeri devono ignorare il layout verticale specifico per lingua orientale del testo. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Determina se i numeri devono ignorare il layout verticale specifico per lingua orientale del testo. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Determina se l'altezza di un testo deve essere normalizzata. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Determina se l'altezza di un testo deve essere normalizzata. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Determina se il testo non deve essere corretto. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Determina se il testo non deve essere corretto. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Restituisce o imposta il tipo di sottolineatura del testo. Nessuna eredità applicata. Lettura/scrittura [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Restituisce:**
byte
### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Restituisce o imposta il tipo di sottolineatura del testo. Nessuna eredità applicata. Lettura/scrittura [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Restituisce o imposta il tipo di capitalizzazione del testo. Nessuna eredità applicata. Lettura/scrittura [TextCapType](../../com.aspose.slides/textcaptype).

**Restituisce:**
byte
### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Restituisce o imposta il tipo di capitalizzazione del testo. Nessuna eredità applicata. Lettura/scrittura [TextCapType](../../com.aspose.slides/textcaptype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Restituisce o imposta il tipo di barrato del testo. Nessuna eredità applicata. Lettura/scrittura [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Restituisce:**
byte
### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Restituisce o imposta il tipo di barrato del testo. Nessuna eredità applicata. Lettura/scrittura [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Determina se lo stile di sottolineatura possiede proprie proprietà LineFormat o le eredita dalle proprietà LineFormat del testo. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Determina se lo stile di sottolineatura possiede proprie proprietà LineFormat o le eredita dalle proprietà LineFormat del testo. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Determina se lo stile di sottolineatura possiede proprie proprietà FillFormat o le eredita dalle proprietà FillFormat del testo. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Determina se lo stile di sottolineatura possiede proprie proprietà FillFormat o le eredita dalle proprietà FillFormat del testo. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Restituisce o imposta l'altezza del carattere di una porzione. **Float.NaN** indica che l'altezza è indefinita e deve essere ereditata dal Master. Lettura/scrittura float.

**Restituisce:**
float
### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Restituisce o imposta l'altezza del carattere di una porzione. **Float.NaN** indica che l'altezza è indefinita e deve essere ereditata dal Master. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Restituisce o imposta le informazioni sul font latino. Null indica che il font è indefinito e deve essere ereditato dal Master. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Restituisce o imposta le informazioni sul font latino. Null indica che il font è indefinito e deve essere ereditato dal Master. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Restituisce o imposta le informazioni sul font dell'Est asiatico. Null indica che il font è indefinito e deve essere ereditato dal Master. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Restituisce o imposta le informazioni sul font dell'Est asiatico. Null indica che il font è indefinito e deve essere ereditato dal Master. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Restituisce o imposta le informazioni sul font di script complesso. Null indica che il font è indefinito e deve essere ereditato dal Master. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Restituisce o imposta le informazioni sul font di script complesso. Null indica che il font è indefinito e deve essere ereditato dal Master. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Restituisce o imposta le informazioni sul font simbolico. Null indica che il font è indefinito e deve essere ereditato dal Master. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Restituisce o imposta le informazioni sul font simbolico. Null indica che il font è indefinito e deve essere ereditato dal Master. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Restituisce o imposta il testo in apice o pedice. Valore da -100% (pedice) a 100% (apice). **Float.NaN** indica che il valore è indefinito e deve essere ereditato dal Master. Lettura/scrittura float.

**Restituisce:**
float
### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Restituisce o imposta il testo in apice o pedice. Valore da -100% (pedice) a 100% (apice). **Float.NaN** indica che il valore è indefinito e deve essere ereditato dal Master. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Restituisce o imposta la dimensione minima del carattere per cui l'kerning è attivato. **Float.NaN** indica che il valore è indefinito e deve essere ereditato dal Master. Lettura/scrittura float.

**Restituisce:**
float
### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Restituisce o imposta la dimensione minima del carattere per cui l'kerning è attivato. **Float.NaN** indica che il valore è indefinito e deve essere ereditato dal Master. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Restituisce o imposta l'Id di una lingua di correzione. Utilizzato per il controllo ortografico e grammaticale. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Restituisce o imposta l'Id di una lingua di correzione. Utilizzato per il controllo ortografico e grammaticale. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Restituisce o imposta l'Id di una lingua alternativa. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Restituisce o imposta l'Id di una lingua alternativa. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Restituisce o imposta l'incremento di spaziatura intercarattere. **Float.NaN** indica che il valore è indefinito e deve essere ereditato dal Master. Lettura/scrittura float.

**Restituisce:**
float
### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Restituisce o imposta l'incremento di spaziatura intercarattere. **Float.NaN** indica che il valore è indefinito e deve essere ereditato dal Master. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Ottiene o imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata su false, i controlli ortografici per gli elementi di testo vengono soppressi. Quando impostata su true, il controllo ortografico è consentito. Il valore predefinito è false.

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

**Restituisce:**
boolean
### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

Ottiene o imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata su false, i controlli ortografici per gli elementi di testo vengono soppressi. Quando impostata su true, il controllo ortografico è consentito. Il valore predefinito è false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Accedi alla prima porzione di testo all'interno della prima forma nella prima diapositiva
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Abilita il controllo ortografico per questa porzione di testo
>      portion.getPortionFormat().setSpellCheck(true);
>      // Salva la presentazione modificata
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |