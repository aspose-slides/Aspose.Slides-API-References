---
title: BasePortionFormat
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Proprietà comuni di formattazione della porzione di testo.
type: docs
url: /it/com.aspose.slides/baseportionformat/
---
**Ereditarietà:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**  
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)  
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Proprietà di formattazione comuni della porzione di testo.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Restituisce le proprietà LineFormat per il contorno del testo. |
| [getFillFormat()](#getFillFormat--) | Restituisce le proprietà FillFormat del testo. |
| [getEffectFormat()](#getEffectFormat--) | Restituisce le proprietà EffectFormat del testo. |
| [getHighlightColor()](#getHighlightColor--) | Restituisce il colore usato per evidenziare un testo. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Restituisce le proprietà LineFormat usate per delineare la linea di sottolineatura. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Restituisce le proprietà FillFormat della linea di sottolineatura. |
| [getFontBold()](#getFontBold--) | Determina se il carattere è in grassetto. |
| [setFontBold(byte value)](#setFontBold-byte-) | Determina se il carattere è in grassetto. |
| [getFontItalic()](#getFontItalic--) | Determina se il carattere è in corsivo. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Determina se il carattere è in corsivo. |
| [getKumimoji()](#getKumimoji--) | Determina se i numeri devono ignorare il layout verticale specifico per le lingue orientali del testo. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Determina se i numeri devono ignorare il layout verticale specifico per le lingue orientali del testo. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Determina se l'altezza di un testo dovrebbe essere normalizzata. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Determina se l'altezza di un testo dovrebbe essere normalizzata. |
| [getProofDisabled()](#getProofDisabled--) | Determina se il testo non deve essere corretto. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Determina se il testo non deve essere corretto. |
| [getFontUnderline()](#getFontUnderline--) | Restituisce o imposta il tipo di sottolineatura del testo. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Restituisce o imposta il tipo di sottolineatura del testo. |
| [getTextCapType()](#getTextCapType--) | Restituisce o imposta il tipo di capitalizzazione del testo. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Restituisce o imposta il tipo di capitalizzazione del testo. |
| [getStrikethroughType()](#getStrikethroughType--) | Restituisce o imposta il tipo di barrato del testo. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Restituisce o imposta il tipo di barrato del testo. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Determina se lo stile di sottolineatura ha proprie proprietà LineFormat o le eredita dalle proprietà LineFormat del testo. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Determina se lo stile di sottolineatura ha proprie proprietà LineFormat o le eredita dalle proprietà LineFormat del testo. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Determina se lo stile di sottolineatura ha proprie proprietà FillFormat o le eredita dalle proprietà FillFormat del testo. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Determina se lo stile di sottolineatura ha proprie proprietà FillFormat o le eredita dalle proprietà FillFormat del testo. |
| [getFontHeight()](#getFontHeight--) | Restituisce o imposta l'altezza del carattere di una porzione. |
| [setFontHeight(float value)](#setFontHeight-float-) | Restituisce o imposta l'altezza del carattere di una porzione. |
| [getLatinFont()](#getLatinFont--) | Restituisce o imposta le informazioni sul carattere Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Restituisce o imposta le informazioni sul carattere Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Restituisce o imposta le informazioni sul carattere East Asian. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Restituisce o imposta le informazioni sul carattere East Asian. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Restituisce o imposta le informazioni sul carattere script complesso. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Restituisce o imposta le informazioni sul carattere script complesso. |
| [getSymbolFont()](#getSymbolFont--) | Restituisce o imposta le informazioni sul carattere simbolico. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Restituisce o imposta le informazioni sul carattere simbolico. |
| [getEscapement()](#getEscapement--) | Restituisce o imposta il testo in apice o pedice. |
| [setEscapement(float value)](#setEscapement-float-) | Restituisce o imposta il testo in apice o pedice. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Restituisce o imposta la dimensione minima del carattere per cui il kerning dovrebbe essere attivato. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Restituisce o imposta la dimensione minima del carattere per cui il kerning dovrebbe essere attivato. |
| [getLanguageId()](#getLanguageId--) | Restituisce o imposta l'Id di una lingua di correzione. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Restituisce o imposta l'Id di una lingua di correzione. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Restituisce o imposta l'Id di una lingua alternativa. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Restituisce o imposta l'Id di una lingua alternativa. |
| [getSpacing()](#getSpacing--) | Restituisce o imposta l'incremento di spaziatura intercarattere. |
| [setSpacing(float value)](#setSpacing-float-) | Restituisce o imposta l'incremento di spaziatura intercarattere. |
| [getSpellCheck()](#getSpellCheck--) | Ottiene o imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Ottiene o imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versione. Solo lettura long.

**Restituisce:**  
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

Restituisce le proprietà LineFormat per il contorno del testo. Nessuna ereditarietà applicata. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Restituisce le proprietà FillFormat del testo. Nessuna ereditarietà applicata. Solo lettura [IFillFormat](../../com.aspose.slides/ifillformat).

**Restituisce:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Restituisce le proprietà EffectFormat del testo. Nessuna ereditarietà applicata. Solo lettura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Restituisce:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Restituisce il colore usato per evidenziare un testo. Nessuna ereditarietà applicata. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Restituisce le proprietà LineFormat usate per delineare la linea di sottolineatura. Nessuna ereditarietà applicata. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Restituisce le proprietà FillFormat della linea di sottolineatura. Nessuna ereditarietà applicata. Solo lettura [IFillFormat](../../com.aspose.slides/ifillformat).

**Restituisce:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Determina se il carattere è in grassetto. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**  
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Determina se il carattere è in grassetto. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Determina se il carattere è in corsivo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**  
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Determina se il carattere è in corsivo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Determina se i numeri devono ignorare il layout verticale specifico per le lingue orientali del testo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**  
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Determina se i numeri devono ignorare il layout verticale specifico per le lingue orientali del testo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Determina se l'altezza di un testo dovrebbe essere normalizzata. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**  
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Determina se l'altezza di un testo dovrebbe essere normalizzata. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Determina se il testo non deve essere corretto. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**  
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Determina se il testo non deve essere corretto. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Restituisce o imposta il tipo di sottolineatura del testo. Nessuna ereditarietà applicata. Lettura/scrittura [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Restituisce:**  
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Restituisce o imposta il tipo di sottolineatura del testo. Nessuna ereditarietà applicata. Lettura/scrittura [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Restituisce o imposta il tipo di capitalizzazione del testo. Nessuna ereditarietà applicata. Lettura/scrittura [TextCapType](../../com.aspose.slides/textcaptype).

**Restituisce:**  
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Restituisce o imposta il tipo di capitalizzazione del testo. Nessuna ereditarietà applicata. Lettura/scrittura [TextCapType](../../com.aspose.slides/textcaptype).

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Restituisce o imposta il tipo di barrato del testo. Nessuna ereditarietà applicata. Lettura/scrittura [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Restituisce:**  
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Restituisce o imposta il tipo di barrato del testo. Nessuna ereditarietà applicata. Lettura/scrittura [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Determina se lo stile di sottolineatura ha proprie proprietà LineFormat o le eredita dalle proprietà LineFormat del testo. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**  
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Determina se lo stile di sottolineatura ha proprie proprietà LineFormat o le eredita dalle proprietà LineFormat del testo. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Determina se lo stile di sottolineatura ha proprie proprietà FillFormat o le eredita dalle proprietà FillFormat del testo. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**  
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Determina se lo stile di sottolineatura ha proprie proprietà FillFormat o le eredita dalle proprietà FillFormat del testo. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Restituisce o imposta l'altezza del carattere di una porzione. **Float.NaN** significa che l'altezza è indefinita e dovrebbe essere ereditata dal Master. Lettura/scrittura  float .

**Restituisce:**  
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Restituisce o imposta l'altezza del carattere di una porzione. **Float.NaN** significa che l'altezza è indefinita e dovrebbe essere ereditata dal Master. Lettura/scrittura  float .

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Restituisce o imposta le informazioni sul carattere Latin. Null significa che il carattere è indefinito e dovrebbe essere ereditato dal Master. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Restituisce o imposta le informazioni sul carattere Latin. Null significa che il carattere è indefinito e dovrebbe essere ereditato dal Master. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Restituisce o imposta le informazioni sul carattere East Asian. Null significa che il carattere è indefinito e dovrebbe essere ereditato dal Master. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Restituisce o imposta le informazioni sul carattere East Asian. Null significa che il carattere è indefinito e dovrebbe essere ereditato dal Master. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Restituisce o imposta le informazioni sul carattere script complesso. Null significa che il carattere è indefinito e dovrebbe essere ereditato dal Master. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Restituisce o imposta le informazioni sul carattere script complesso. Null significa che il carattere è indefinito e dovrebbe essere ereditato dal Master. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Restituisce o imposta le informazioni sul carattere simbolico. Null significa che il carattere è indefinito e dovrebbe essere ereditato dal Master. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Restituisce o imposta le informazioni sul carattere simbolico. Null significa che il carattere è indefinito e dovrebbe essere ereditato dal Master. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Restituisce o imposta il testo in apice o pedice. Valore da -100% (pedice) a 100% (apice). **Float.NaN** significa che il valore è indefinito e dovrebbe essere ereditato dal Master. Lettura/scrittura  float .

**Restituisce:**  
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Restituisce o imposta il testo in apice o pedice. Valore da -100% (pedice) a 100% (apice). **Float.NaN** significa che il valore è indefinito e dovrebbe essere ereditato dal Master. Lettura/scrittura  float .

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKeratinMinimalSize()
```

Restituisce o imposta la dimensione minima del carattere per cui il kerning dovrebbe essere attivato. **Float.NaN** significa che il valore è indefinito e dovrebbe essere ereditato dal Master. Lettura/scrittura  float .

**Restituisce:**  
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Restituisce o imposta la dimensione minima del carattere per cui il kerning dovrebbe essere attivato. **Float.NaN** significa che il valore è indefinito e dovrebbe essere ereditato dal Master. Lettura/scrittura  float .

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Restituisce o imposta l'Id di una lingua di correzione. Usato per il controllo ortografico e grammaticale. Lettura/scrittura String.

**Restituisce:**  
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Restituisce o imposta l'Id di una lingua di correzione. Usato per il controllo ortografico e grammaticale. Lettura/scrittura String.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Restituisce o imposta l'Id di una lingua alternativa. Lettura/scrittura String.

**Restituisce:**  
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Restituisce o imposta l'Id di una lingua alternativa. Lettura/scrittura String.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Restituisce o imposta l'incremento di spaziatura intercarattere. **Float.NaN** significa che il valore è indefinito e dovrebbe essere ereditato dal Master. Lettura/scrittura  float .

**Restituisce:**  
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Restituisce o imposta l'incremento di spaziatura intercarattere. **Float.NaN** significa che il valore è indefinito e dovrebbe essere ereditato dal Master. Lettura/scrittura  float .

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Ottiene o imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata su false, i controlli ortografici per gli elementi di testo sono soppressi. Quando impostata su true, il controllo ortografico è consentito. Il valore predefinito è false.

**Restituisce:**  
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

Ottiene o imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata su false, i controlli ortografici per gli elementi di testo sono soppressi. Quando impostata su true, il controllo ortografico è consentito. Il valore predefinito è false.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

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

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |