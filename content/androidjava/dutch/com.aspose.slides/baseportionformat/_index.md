---
title: BasePortionFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Algemene opmaak-eigenschappen voor tekstgedeelten.
type: docs
url: /nl/com.aspose.slides/baseportionformat/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Algemene opmaak-eigenschappen voor tekstgedeelten.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Retourneert de LineFormat-eigenschappen voor tekstomlijsting. |
| [getFillFormat()](#getFillFormat--) | Retourneert de FillFormat-eigenschappen van de tekst. |
| [getEffectFormat()](#getEffectFormat--) | Retourneert de EffectFormat-eigenschappen van de tekst. |
| [getHighlightColor()](#getHighlightColor--) | Retourneert de kleur die wordt gebruikt om een tekst te markeren. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstrepingslijn te omranden. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Retourneert de FillFormat-eigenschappen van de onderstrepingslijn. |
| [getFontBold()](#getFontBold--) | Bepaalt of het lettertype vetgedrukt is. |
| [setFontBold(byte value)](#setFontBold-byte-) | Bepaalt of het lettertype vetgedrukt is. |
| [getFontItalic()](#getFontItalic--) | Bepaalt of het lettertype cursief is. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Bepaalt of het lettertype cursief is. |
| [getKumimoji()](#getKumimoji--) | Bepaalt of de cijfers de oosterse, taal-specifieke verticale tekstopmaak moeten negeren. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Bepaalt of de cijfers de oosterse, taal-specifieke verticale tekstopmaak moeten negeren. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. |
| [getProofDisabled()](#getProofDisabled--) | Bepaalt of de tekst niet moet worden proeflezen. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Bepaalt of de tekst niet moet worden proeflezen. |
| [getFontUnderline()](#getFontUnderline--) | Retourneert of stelt het onderlijntype van de tekst in. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Retourneert of stelt het onderlijntype van de tekst in. |
| [getTextCapType()](#getTextCapType--) | Retourneert of stelt het type hoofdlettergebruik van de tekst in. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Retourneert of stelt het type hoofdlettergebruik van de tekst in. |
| [getStrikethroughType()](#getStrikethroughType--) | Retourneert of stelt het doorhalings-type van een tekst in. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Retourneert of stelt het doorhalings-type van een tekst in. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Bepaalt of de onderstrepingsstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Bepaalt of de onderstrepingsstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Bepaalt of de onderstrepingsstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Bepaalt of de onderstrepingsstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. |
| [getFontHeight()](#getFontHeight--) | Retourneert of stelt de lettergrootte van een deel in. |
| [setFontHeight(float value)](#setFontHeight-float-) | Retourneert of stelt de lettergrootte van een deel in. |
| [getLatinFont()](#getLatinFont--) | Retourneert of stelt de informatie over het Latijnse lettertype in. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Retourneert of stelt de informatie over het Latijnse lettertype in. |
| [getEastAsianFont()](#getEastAsianFont--) | Retourneert of stelt de informatie over het Oost-Aziatische lettertype in. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Retourneert of stelt de informatie over het Oost-Aziatische lettertype in. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Retourneert of stelt de informatie over het complexe script-lettertype in. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Retourneert of stelt de informatie over het complexe script-lettertype in. |
| [getSymbolFont()](#getSymbolFont--) | Retourneert of stelt de informatie over het symbolische lettertype in. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Retourneert of stelt de informatie over het symbolische lettertype in. |
| [getEscapement()](#getEscapement--) | Retourneert of stelt de superscript- of subscript-tekst in. |
| [setEscapement(float value)](#setEscapement-float-) | Retourneert of stelt de superscript- of subscript-tekst in. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Retourneert of stelt de minimale lettergrootte in, waarbij kerning moet worden ingeschakeld. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Retourneert of stelt de minimale lettergrootte in, waarbij kerning moet worden ingeschakeld. |
| [getLanguageId()](#getLanguageId--) | Retourneert of stelt de Id van een proefleessaal in. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Retourneert of stelt de Id van een proefleessaal in. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Retourneert of stelt de Id van een alternatieve taal in. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Retourneert of stelt de Id van een alternatieve taal in. |
| [getSpacing()](#getSpacing--) | Retourneert of stelt de interkarakter-spatiëringstoename in. |
| [setSpacing(float value)](#setSpacing-float-) | Retourneert of stelt de interkarakter-spatiëringstoename in. |
| [getSpellCheck()](#getSpellCheck--) | Haalt op of stelt een waarde in die aangeeft of spellingscontrole is ingeschakeld voor het tekstgedeelte. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Haalt op of stelt een waarde in die aangeeft of spellingscontrole is ingeschakeld voor het tekstgedeelte. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versie. Alleen-lezen long.

**Retourneert:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

Retourneert de LineFormat-eigenschappen voor tekstomlijsting. Geen overerving toegepast. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retourneert:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Retourneert de FillFormat-eigenschappen van de tekst. Geen overerving toegepast. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retourneert:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Retourneert de EffectFormat-eigenschappen van de tekst. Geen overerving toegepast. Alleen-lezen [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Retourneert:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Retourneert de kleur die wordt gebruikt om een tekst te markeren. Geen overerving toegepast. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourneert:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstrepingslijn te omranden. Geen overerving toegepast. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retourneert:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Retourneert de FillFormat-eigenschappen van de onderstrepingslijn. Geen overerving toegepast. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retourneert:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Bepaalt of het lettertype vetgedrukt is. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Bepaalt of het lettertype vetgedrukt is. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Bepaalt of het lettertype cursief is. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Bepaalt of het lettertype cursief is. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Bepaalt of de cijfers de oosterse, taal-specifieke verticale tekstopmaak moeten negeren. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Bepaalt of de cijfers de oosterse, taal-specifieke verticale tekstopmaak moeten negeren. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Bepaalt of de tekst niet moet worden proeflezen. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Bepaalt of de tekst niet moet worden proeflezen. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Retourneert of stelt het onderlijntype van de tekst in. Geen overerving toegepast. Lezen/Schrijven [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Retourneert:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Retourneert of stelt het onderlijntype van de tekst in. Geen overerving toegepast. Lezen/Schrijven [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Retourneert of stelt het type hoofdlettergebruik van de tekst in. Geen overerving toegepast. Lezen/Schrijven [TextCapType](../../com.aspose.slides/textcaptype).

**Retourneert:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Retourneert of stelt het type hoofdlettergebruik van de tekst in. Geen overerving toegepast. Lezen/Schrijven [TextCapType](../../com.aspose.slides/textcaptype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Retourneert of stelt het doorhalings-type van een tekst in. Geen overerving toegepast. Lezen/Schrijven [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Retourneert:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Retourneert of stelt het doorhalings-type van een tekst in. Geen overerving toegepast. Lezen/Schrijven [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Bepaalt of de onderstrepingsstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Bepaalt of de onderstrepingsstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Bepaalt of de onderstrepingsstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Bepaalt of de onderstrepingsstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Retourneert of stelt de letterhoogte van een deel in. **Float.NaN** betekent dat de hoogte ongedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven  float .

**Retourneert:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Retourneert of stelt de letterhoogte van een deel in. **Float.NaN** betekent dat de hoogte ongedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven  float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Retourneert of stelt de informatie over het Latijnse lettertype in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retourneert:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Retourneert of stelt de informatie over het Latijnse lettertype in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Retourneert of stelt de informatie over het Oost-Aziatische lettertype in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retourneert:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Retourneert of stelt de informatie over het Oost-Aziatische lettertype in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Retourneert of stelt de informatie over het complexe script-lettertype in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retourneert:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Retourneert of stelt de informatie over het complexe script-lettertype in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Retourneert of stelt de informatie over het symbolische lettertype in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retourneert:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Retourneert of stelt de informatie over het symbolische lettertype in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Retourneert of stelt de superscript- of subscript-tekst in. Waarde van -100 % (subscript) tot 100 % (superscript). **Float.NaN** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven  float .

**Retourneert:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Retourneert of stelt de superscript- of subscript-tekst in. Waarde van -100 % (subscript) tot 100 % (superscript). **Float.NaN** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven  float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Retourneert of stelt de minimale lettergrootte in, waarbij kerning moet worden ingeschakeld. **Float.NaN** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven  float .

**Retourneert:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Retourneert of stelt de minimale lettergrootte in, waarbij kerning moet worden ingeschakeld. **Float.NaN** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven  float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Retourneert of stelt de Id van een proefleessaal in. Wordt gebruikt voor controle van spelling en grammatica. Lezen/Schrijven String.

**Retourneert:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Retourneert of stelt de Id van een proefleessaal in. Wordt gebruikt voor controle van spelling en grammatica. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Retourneert of stelt de Id van een alternatieve taal in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Retourneert of stelt de Id van een alternatieve taal in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Retourneert of stelt de interkarakter-spatiëringstoename in. **Float.NaN** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven  float .

**Retourneert:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Retourneert of stelt de interkarakter-spatiëringstoename in. **Float.NaN** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven  float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Haalt op of stelt een waarde in die aangeeft of spellingscontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap **false** is, worden spellingscontroles voor tekstelementen onderdrukt. Wanneer hij **true** is, is spellingscontrole toegestaan. Standaardwaarde is **false**.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Toegang tot het eerste tekstgedeelte binnen de eerste vorm op de eerste dia
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Spellingscontrole inschakelen voor dit tekstgedeelte
>      portion.getPortionFormat().setSpellCheck(true);
>      // De gewijzigde presentatie opslaan
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

Haalt op of stelt een waarde in die aangeeft of spellingscontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap **false** is, worden spellingscontroles voor tekstelementen onderdrukt. Wanneer hij **true** is, is spellingscontrole toegestaan. Standaardwaarde is **false**.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Toegang tot het eerste tekstgedeelte binnen de eerste vorm op de eerste dia
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Spellingscontrole inschakelen voor dit tekstgedeelte
>      portion.getPortionFormat().setSpellCheck(true);
>      // De gewijzigde presentatie opslaan
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |