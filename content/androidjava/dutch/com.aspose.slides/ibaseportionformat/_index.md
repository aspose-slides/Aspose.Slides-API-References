---
title: IBasePortionFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Deze klasse bevat de opmaak-eigenschappen van het tekstgedeelte.
type: docs
url: /nl/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Deze klasse bevat de opmaak-eigenschappen van het tekstgedeelte. In tegenstelling tot [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) zijn alle eigenschappen van deze klasse beschrijfbaar.

--------------------

Deze klasse wordt gebruikt om de opmaak-eigenschappen van een bepaald tekstgedeelte op te vragen en te wijzigen. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, waardoor u in de meeste gevallen waarden krijgt die "onbepaald" betekenen.

Om de effectieve opmaak-parameterwaarden, inclusief erfelijke, te verkrijgen, moet u de [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective)-methode gebruiken die een [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-instantie retourneert.

## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Retourneert de LineFormat-eigenschappen voor tekstcontour. |
| [getFillFormat()](#getFillFormat--) | Retourneert de FillFormat-eigenschappen voor tekst. |
| [getEffectFormat()](#getEffectFormat--) | Retourneert de EffectFormat-eigenschappen voor tekst. |
| [getHighlightColor()](#getHighlightColor--) | Retourneert de kleur die wordt gebruikt om een tekst te markeren. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstreeplijn te contouren. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Retourneert de FillFormat-eigenschappen van de onderstreeplijn. |
| [getFontBold()](#getFontBold--) | Bepaalt of het lettertype vet is. |
| [setFontBold(byte value)](#setFontBold-byte-) | Bepaalt of het lettertype vet is. |
| [getFontItalic()](#getFontItalic--) | Bepaalt of het lettertype cursief is. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Bepaalt of het lettertype cursief is. |
| [getKumimoji()](#getKumimoji--) | Bepaalt of de getallen de oosterse, taal-specifieke verticale tekstopmaak moeten negeren. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Bepaalt of de getallen de oosterse, taal-specifieke verticale tekstopmaak moeten negeren. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Bepaalt of de hoogte van een tekst moet worden genormaliseerd. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Bepaalt of de hoogte van een tekst moet worden genormaliseerd. |
| [getProofDisabled()](#getProofDisabled--) | Bepaalt of de tekst niet gecontroleerd mag worden. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Bepaalt of de tekst niet gecontroleerd mag worden. |
| [getFontUnderline()](#getFontUnderline--) | Retourneert of stelt het onderstreeptype van de tekst in. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Retourneert of stelt het onderstreeptype van de tekst in. |
| [getTextCapType()](#getTextCapType--) | Retourneert of stelt het type hoofdlettergebruik van de tekst in. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Retourneert of stelt het type hoofdlettergebruik van de tekst in. |
| [getStrikethroughType()](#getStrikethroughType--) | Retourneert of stelt het doorstrepings-type van een tekst in. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Retourneert of stelt het doorstrepings-type van een tekst in. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Bepaalt of de onderstreepsstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Bepaalt of de onderstreepsstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Bepaalt of de onderstreepsstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Bepaalt of de onderstreepsstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. |
| [getFontHeight()](#getFontHeight--) | Retourneert of stelt de letterhoogte van een tekstgedeelte in. |
| [setFontHeight(float value)](#setFontHeight-float-) | Retourneert of stelt de letterhoogte van een tekstgedeelte in. |
| [getLatinFont()](#getLatinFont--) | Retourneert of stelt de Latin-lettertype-informatie in. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Retourneert of stelt de Latin-lettertype-informatie in. |
| [getEastAsianFont()](#getEastAsianFont--) | Retourneert of stelt de East Asian-lettertype-informatie in. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Retourneert of stelt de East Asian-lettertype-informatie in. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Retourneert of stelt de Complex Script-lettertype-informatie in. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Retourneert of stelt de Complex Script-lettertype-informatie in. |
| [getSymbolFont()](#getSymbolFont--) | Retourneert of stelt de Symbolic-lettertype-informatie in. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Retourneert of stelt de Symbolic-lettertype-informatie in. |
| [getEscapement()](#getEscapement--) | Retourneert of stelt superscript- of subscript-tekst in. |
| [setEscapement(float value)](#setEscapement-float-) | Retourneert of stelt superscript- of subscript-tekst in. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Retourneert of stelt de minimale lettergrootte in waarbij kerning moet worden ingeschakeld. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Retourneert of stelt de minimale lettergrootte in waarbij kerning moet worden ingeschakeld. |
| [getLanguageId()](#getLanguageId--) | Retourneert of stelt de Id van een proeflees-taal in. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Retourneert of stelt de Id van een proeflees-taal in. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Retourneert of stelt de Id van een alternatieve taal in. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Retourneert of stelt de Id van een alternatieve taal in. |
| [getSpacing()](#getSpacing--) | Retourneert of stelt de tussen-karakter-spatiëring increment in. |
| [setSpacing(float value)](#setSpacing-float-) | Retourneert of stelt de tussen-karakter-spatiëring increment in. |
| [getSpellCheck()](#getSpellCheck--) | Haalt of stelt een waarde in die aangeeft of spellingscontrole is ingeschakeld voor het tekstgedeelte. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Haalt of stelt een waarde in die aangeeft of spellingscontrole is ingeschakeld voor het tekstgedeelte. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Retourneert de LineFormat-eigenschappen voor tekstcontour. Geen overerving toegepast. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retourneert:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Retourneert de FillFormat-eigenschappen van de tekst. Geen overerving toegepast. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retourneert:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Retourneert de EffectFormat-eigenschappen van de tekst. Geen overerving toegepast. Alleen-lezen [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Retourneert:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Retourneert de kleur die wordt gebruikt om een tekst te markeren. Geen overerving toegepast. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourneert:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstreeplijn te contouren. Geen overerving toegepast. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retourneert:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Retourneert de FillFormat-eigenschappen van de onderstreeplijn. Geen overerving toegepast. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retourneert:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Bepaalt of het lettertype vet is. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Bepaalt of het lettertype vet is. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Bepaalt of het lettertype cursief is. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Bepaalt of het lettertype cursief is. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Bepaalt of de getallen de oosterse, taal-specifieke verticale tekstopmaak moeten negeren. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Bepaalt of de getallen de oosterse, taal-specifieke verticale tekstopmaak moeten negeren. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Bepaalt of de hoogte van een tekst moet worden genormaliseerd. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Bepaalt of de hoogte van een tekst moet worden genormaliseerd. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Bepaalt of de tekst niet gecontroleerd mag worden. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Bepaalt of de tekst niet gecontroleerd mag worden. Geen overerving toegepast. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Retourneert of stelt het onderstreeptype van de tekst in. Geen overerving toegepast. Lezen/Schrijven [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Retourneert:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Retourneert of stelt het onderstreeptype van de tekst in. Geen overerving toegepast. Lezen/Schrijven [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Retourneert of stelt het type hoofdlettergebruik van de tekst in. Geen overerving toegepast. Lezen/Schrijven [TextCapType](../../com.aspose.slides/textcaptype).

**Retourneert:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Retourneert of stelt het type hoofdlettergebruik van de tekst in. Geen overerving toegepast. Lezen/Schrijven [TextCapType](../../com.aspose.slides/textcaptype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Retourneert of stelt het doorstrepings-type van een tekst in. Geen overerving toegepast. Lezen/Schrijven [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Retourneert:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Retourneert of stelt het doorstrepings-type van een tekst in. Geen overerving toegepast. Lezen/Schrijven [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Bepaalt of de onderstreepsstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Bepaalt of de onderstreepsstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Bepaalt of de onderstreepsstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Bepaalt of de onderstreepsstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Retourneert of stelt de letterhoogte van een tekstgedeelte in. **Float.NaN** betekent dat de hoogte onbepaald is en moet worden geërfd van de Master. Lezen/Schrijven float.

**Retourneert:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Retourneert of stelt de letterhoogte van een tekstgedeelte in. **Float.NaN** betekent dat de hoogte onbepaald is en moet worden geërfd van de Master. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Retourneert of stelt de Latin-lettertype-informatie in. Null betekent dat het lettertype onbepaald is en moet worden geërfd van de Master. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retourneert:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Retourneert of stelt de Latin-lettertype-informatie in. Null betekent dat het lettertype onbepaald is en moet worden geërfd van de Master. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Retourneert of stelt de East Asian-lettertype-informatie in. Null betekent dat het lettertype onbepaald is en moet worden geërfd van de Master. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retourneert:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Retourneert of stelt de East Asian-lettertype-informatie in. Null betekent dat het lettertype onbepaald is en moet worden geërfd van de Master. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Retourneert of stelt de Complex Script-lettertype-informatie in. Null betekent dat het lettertype onbepaald is en moet worden geërfd van de Master. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retourneert:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Retourneert of stelt de Complex Script-lettertype-informatie in. Null betekent dat het lettertype onbepaald is en moet worden geërfd van de Master. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Retourneert of stelt de Symbolic-lettertype-informatie in. Null betekent dat het lettertype onbepaald is en moet worden geërfd van de Master. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retourneert:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Retourneert of stelt de Symbolic-lettertype-informatie in. Null betekent dat het lettertype onbepaald is en moet worden geërfd van de Master. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Retourneert of stelt superscript- of subscript-tekst in. Waarde van -100% (subscript) tot 100% (superscript). **Float.NaN** betekent dat de waarde onbepaald is en moet worden geërfd van de Master. Lezen/Schrijven float.

**Retourneert:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Retourneert of stelt superscript- of subscript-tekst in. Waarde van -100% (subscript) tot 100% (superscript). **Float.NaN** betekent dat de waarde onbepaald is en moet worden geërfd van de Master. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Retourneert of stelt de minimale lettergrootte in waarbij kerning moet worden ingeschakeld. **Float.NaN** betekent dat de waarde onbepaald is en moet worden geërfd van de Master. Lezen/Schrijven float.

**Retourneert:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Retourneert of stelt de minimale lettergrootte in waarbij kerning moet worden ingeschakeld. **Float.NaN** betekent dat de waarde onbepaald is en moet worden geërfd van de Master. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Retourneert of stelt de Id van een proeflees-taal in. Wordt gebruikt voor spelling- en grammaticacontrole. Lezen/Schrijven String.

**Retourneert:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Retourneert of stelt de Id van een proeflees-taal in. Wordt gebruikt voor spelling- en grammaticacontrole. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Retourneert of stelt de Id van een alternatieve taal in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Retourneert of stelt de Id van een alternatieve taal in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Retourneert of stelt de tussen-karakter-spatiëring increment in. **Float.NaN** betekent dat de waarde onbepaald is en moet worden geërfd van de Master. Lezen/Schrijven float.

**Retourneert:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Retourneert of stelt de tussen-karakter-spatiëring increment in. **Float.NaN** betekent dat de waarde onbepaald is en moet worden geërfd van de Master. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Haalt of stelt een waarde in die aangeeft of spellingscontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap op false staat, worden spellingcontroles voor tekstelementen onderdrukt. Wanneer deze op true staat, is spellingscontrole toegestaan. Standaardwaarde is false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Toegang tot het eerste tekstgedeelte binnen de eerste vorm op de eerste dia
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Schakel spellingscontrole in voor dit tekstgedeelte
>      portion.getPortionFormat().setSpellCheck(true);
>      // Sla de gewijzigde presentatie op
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

Haalt of stelt een waarde in die aangeeft of spellingscontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap op false staat, worden spellingcontroles voor tekstelementen onderdrukt. Wanneer deze op true staat, is spellingscontrole toegestaan. Standaardwaarde is false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Toegang tot het eerste tekstgedeelte binnen de eerste vorm op de eerste dia
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Schakel spellingscontrole in voor dit tekstgedeelte
>      portion.getPortionFormat().setSpellCheck(true);
>      // Sla de gewijzigde presentatie op
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |