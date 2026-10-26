---
title: IBasePortionFormat
second_title: Aspose.Slides for Java API Reference
description: Deze klasse bevat de opmaak-eigenschappen van tekstdelen.
type: docs
url: /nl/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Deze klasse bevat de opmaak-eigenschappen van tekstdelen. In tegenstelling tot [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) zijn alle eigenschappen van deze klasse schrijfbaar.

--------------------

Deze klasse wordt gebruikt om de opmaak-eigenschappen van een specifiek tekstddeel op te halen en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, zodat u in de meeste gevallen waarden krijgt die “onbepaald” betekenen.

Om de effectieve opmaak-parameterwaarden, inclusief geërfde, te krijgen, dient u de [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective)-methode te gebruiken die een [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-instantie retourneert.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Retourneert de LineFormat-eigenschappen voor tekstomlijning. |
| [getFillFormat()](#getFillFormat--) | Retourneert de FillFormat-eigenschappen van de tekst. |
| [getEffectFormat()](#getEffectFormat--) | Retourneert de EffectFormat-eigenschappen van de tekst. |
| [getHighlightColor()](#getHighlightColor--) | Retourneert de kleur die wordt gebruikt om een tekst te markeren. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstreeplijn te omranden. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Retourneert de FillFormat-eigenschappen van de onderstreeplijn. |
| [getFontBold()](#getFontBold--) | Bepaalt of het lettertype vetgedrukt is. |
| [setFontBold(byte value)](#setFontBold-byte-) | Bepaalt of het lettertype vetgedrukt is. |
| [getFontItalic()](#getFontItalic--) | Bepaalt of het lettertype cursief is. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Bepaalt of het lettertype cursief is. |
| [getKumimoji()](#getKumimoji--) | Bepaalt of cijfers de op tekst gebaseerde verticale lay-out van oost-Aziatische talen moeten negeren. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Bepaalt of cijfers de op tekst gebaseerde verticale lay-out van oost-Aziatische talen moeten negeren. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. |
| [getProofDisabled()](#getProofDisabled--) | Bepaalt of de tekst niet moet worden gecontroleerd. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Bepaalt of de tekst niet moet worden gecontroleerd. |
| [getFontUnderline()](#getFontUnderline--) | Retourneert of stelt het onderstreeptype van de tekst in. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Retourneert of stelt het onderstreeptype van de tekst in. |
| [getTextCapType()](#getTextCapType--) | Retourneert of stelt het type hoofdlettergebruik van de tekst in. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Retourneert of stelt het type hoofdlettergebruik van de tekst in. |
| [getStrikethroughType()](#getStrikethroughType--) | Retourneert of stelt het doorhalings-type van een tekst in. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Retourneert of stelt het doorhalings-type van een tekst in. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Bepaalt of de onderstreepstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Bepaalt of de onderstreepstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Bepaalt of de onderstreepstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Bepaalt of de onderstreepstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. |
| [getFontHeight()](#getFontHeight--) | Retourneert of stelt de lettertype-hoogte van een onderdeel in. |
| [setFontHeight(float value)](#setFontHeight-float-) | Retourneert of stelt de lettertype-hoogte van een onderdeel in. |
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
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Retourneert of stelt de minimale lettergrootte in waarvoor kerning ingeschakeld moet worden. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Retourneert of stelt de minimale lettergrootte in waarvoor kerning ingeschakeld moet worden. |
| [getLanguageId()](#getLanguageId--) | Retourneert of stelt de Id van een proeflees-taal in. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Retourneert of stelt de Id van een proeflees-taal in. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Retourneert of stelt de Id van een alternatieve taal in. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Retourneert of stelt de Id van een alternatieve taal in. |
| [getSpacing()](#getSpacing--) | Retourneert of stelt de interkarakter-spatiëringsstap in. |
| [setSpacing(float value)](#setSpacing-float-) | Retourneert of stelt de interkarakter-spatiëringsstap in. |
| [getSpellCheck()](#getSpellCheck--) | Haalt op of stelt een waarde in die aangeeft of spellingcontrole is ingeschakeld voor het tekstgedeelte. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Haalt op of stelt een waarde in die aangeeft of spellingcontrole is ingeschakeld voor het tekstgedeelte. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```


Retourneert de LineFormat-eigenschappen voor tekstomlijning. Geen overerving toegepast. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**  
[ILineFormat](../../com.aspose.slides/ilineformat)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Retourneert de FillFormat-eigenschappen van de tekst. Geen overerving toegepast. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour:**  
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


Retourneert de EffectFormat-eigenschappen van de tekst. Geen overerving toegepast. Alleen-lezen [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Retour:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```


Retourneert de kleur die wordt gebruikt om een tekst te markeren. Geen overerving toegepast. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```


Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstreeplijn te omranden. Geen overerving toegepast. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**  
[ILineFormat](../../com.aspose.slides/ilineformat)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```


Retourneert de FillFormat-eigenschappen van de onderstreeplijn. Geen overerving toegepast. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour:**  
[IFillFormat](../../com.aspose.slides/ifillformat)
### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```


Bepaalt of het lettertype vetgedrukt is. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**  
byte
### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```


Bepaalt of het lettertype vetgedrukt is. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```


Bepaalt of het lettertype cursief is. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**  
byte
### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```


Bepaalt of het lettertype cursief is. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```


Bepaalt of cijfers de op tekst gebaseerde verticale lay-out van oost-Aziatische talen moeten negeren. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**  
byte
### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```


Bepaalt of cijfers de op tekst gebaseerde verticale lay-out van oost-Aziatische talen moeten negeren. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```


Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**  
byte
### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```


Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```


Bepaalt of de tekst niet moet worden gecontroleerd. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**  
byte
### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```


Bepaalt of de tekst niet moet worden gecontroleerd. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


Retourneert of stelt het onderstreeptype van de tekst in. Geen overerving toegepast. Lezen/schrijven [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Retour:**  
byte
### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```


Retourneert of stelt het onderstreeptype van de tekst in. Geen overerving toegepast. Lezen/schrijven [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


Retourneert of stelt het type hoofdlettergebruik van de tekst in. Geen overerving toegepast. Lezen/schrijven [TextCapType](../../com.aspose.slides/textcaptype).

**Retour:**  
byte
### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```


Retourneert of stelt het type hoofdlettergebruik van de tekst in. Geen overerving toegepast. Lezen/schrijven [TextCapType](../../com.aspose.slides/textcaptype).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


Retourneert of stelt het doorhalings-type van een tekst in. Geen overerving toegepast. Lezen/schrijven [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Retour:**  
byte
### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```


Retourneert of stelt het doorhalings-type van een tekst in. Geen overerving toegepast. Lezen/schrijven [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```


Bepaalt of de onderstreepstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**  
byte
### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```


Bepaalt of de onderstreepstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```


Bepaalt of de onderstreepstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**  
byte
### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```


Bepaalt of de onderstreepstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


Retourneert of stelt de lettertype-hoogte van een onderdeel in. **Float.NaN** betekent dat de hoogte onbepaald is en moet worden geërfd van de Master. Lezen/schrijven float.

**Retour:**  
float
### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```


Retourneert of stelt de lettertype-hoogte van een onderdeel in. **Float.NaN** betekent dat de hoogte onbepaald is en moet worden geërfd van de Master. Lezen/schrijven float.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Retourneert of stelt de informatie over het Latijnse lettertype in. Null betekent dat het lettertype onbepaald is en moet worden geërfd van de Master. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retour:**  
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```


Retourneert of stelt de informatie over het Latijnse lettertype in. Null betekent dat het lettertype onbepaald is en moet worden geërfd van de Master. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Retourneert of stelt de informatie over het Oost-Aziatische lettertype in. Null betekent dat het lettertype onbepaald is en moet worden geërfd van de Master. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retour:**  
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```


Retourneert of stelt de informatie over het Oost-Aziatische lettertype in. Null betekent dat het lettertype onbepaald is en moet worden geërfd van de Master. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Retourneert of stelt de informatie over het complexe script-lettertype in. Null betekent dat het lettertype onbepaald is en moet worden geërfd van de Master. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retour:**  
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```


Retourneert of stelt de informatie over het complexe script-lettertype in. Null betekent dat het lettertype onbepaald is en moet worden geërfd van de Master. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


Retourneert of stelt de informatie over het symbolische lettertype in. Null betekent dat het lettertype onbepaald is en moet worden geërfd van de Master. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retour:**  
[IFontData](../../com.aspose.slides/ifontdata)
### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```


Retourneert of stelt de informatie over het symbolische lettertype in. Null betekent dat het lettertype onbepaald is en moet worden geërfd van de Master. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


Retourneert of stelt de superscript- of subscript-tekst in. Waarde van -100 % (subscript) tot 100 % (superscript). **Float.NaN** betekent dat de waarde onbepaald is en moet worden geërfd van de Master. Lezen/schrijven float.

**Retour:**  
float
### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```


Retourneert of stelt de superscript- of subscript-tekst in. Waarde van -100 % (subscript) tot 100 % (superscript). **Float.NaN** betekent dat de waarde onbepaald is en moet worden geërfd van de Master. Lezen/schrijven float.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


Retourneert of stelt de minimale lettergrootte in waarvoor kerning ingeschakeld moet worden. **Float.NaN** betekent dat de waarde onbepaald is en moet worden geërfd van de Master. Lezen/schrijven float.

**Retour:**  
float
### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```


Retourneert of stelt de minimale lettergrootte in waarvoor kerning ingeschakeld moet worden. **Float.NaN** betekent dat de waarde onbepaald is en moet worden geërfd van de Master. Lezen/schrijven float.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```


Retourneert of stelt de Id van een proeflees-taal in. Wordt gebruikt voor spelling- en grammaticacontrole. Lezen/schrijven String.

**Retour:**  
java.lang.String
### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```


Retourneert of stelt de Id van een proeflees-taal in. Wordt gebruikt voor spelling- en grammaticacontrole. Lezen/schrijven String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```


Retourneert of stelt de Id van een alternatieve taal in. Lezen/schrijven String.

**Retour:**  
java.lang.String
### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```


Retourneert of stelt de Id van een alternatieve taal in. Lezen/schrijven String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


Retourneert of stelt de interkarakter-spatiëringsstap in. **Float.NaN** betekent dat de waarde onbepaald is en moet worden geërfd van de Master. Lezen/schrijven float.

**Retour:**  
float
### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```


Retourneert of stelt de interkarakter-spatiëringsstap in. **Float.NaN** betekent dat de waarde onbepaald is en moet worden geërfd van de Master. Lezen/schrijven float.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```


Haalt op of stelt een waarde in die aangeeft of spellingcontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap false is, worden spellingcontroles voor tekstelementen onderdrukt. Wanneer true, is spellingcontrole toegestaan. Standaardwaarde is false.

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


**Retour:**  
boolean
### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of spellingcontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap false is, worden spellingcontroles voor tekstelementen onderdrukt. Wanneer true, is spellingcontrole toegestaan. Standaardwaarde is false.

--------------------

> ```
> Volgend voorbeeld toont het inschakelen van de SpellCheck-vlag vóór het opslaan van de presentatie:
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |