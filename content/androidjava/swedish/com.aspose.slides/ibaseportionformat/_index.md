---
title: IBasePortionFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Denna klass innehåller formateringsegenskaperna för textdelar.
type: docs
url: /sv/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Denna klass innehåller formateringsegenskaperna för textdelar. Till skillnad från [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) är alla egenskaper i denna klass skrivbara.

--------------------

Denna klass används för att returnera och manipulera formateringsegenskaper för textdelar som är definierade för den specifika delen. Detta innebär att ingen arv tillämpas vid hämtning av värden, så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formateringsparametervärdena inklusive ärvda måste du använda metoden [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) som returnerar en [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-instans.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Returns the LineFormat properties for text outlining. |
| [getFillFormat()](#getFillFormat--) | Returns the text FillFormat properties. |
| [getEffectFormat()](#getEffectFormat--) | Returns the text EffectFormat properties. |
| [getHighlightColor()](#getHighlightColor--) | Returns the color used to highlight a text. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Returns the LineFormat properties used to outline underline line. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Returns the underline line FillFormat properties. |
| [getFontBold()](#getFontBold--) | Determines whether the font is bold. |
| [setFontBold(byte value)](#setFontBold-byte-) | Determines whether the font is bold. |
| [getFontItalic()](#getFontItalic--) | Determines whether the font is itallic. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Determines whether the font is itallic. |
| [getKumimoji()](#getKumimoji--) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Determines whether the height of a text should be normalized. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Determines whether the height of a text should be normalized. |
| [getProofDisabled()](#getProofDisabled--) | Determines whether the text shouldn't be proofed. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Determines whether the text shouldn't be proofed. |
| [getFontUnderline()](#getFontUnderline--) | Returns or sets the text underline type. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Returns or sets the text underline type. |
| [getTextCapType()](#getTextCapType--) | Returns or sets the type of text capitalization. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Returns or sets the type of text capitalization. |
| [getStrikethroughType()](#getStrikethroughType--) | Returns or sets the strikethrough type of a text. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Returns or sets the strikethrough type of a text. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. |
| [getFontHeight()](#getFontHeight--) | Returns or sets the font height of a portion. |
| [setFontHeight(float value)](#setFontHeight-float-) | Returns or sets the font height of a portion. |
| [getLatinFont()](#getLatinFont--) | Returns or sets the Latin font info. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Returns or sets the Latin font info. |
| [getEastAsianFont()](#getEastAsianFont--) | Returns or sets the East Asian font info. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Returns or sets the East Asian font info. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Returns or sets the complex script font info. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Returns or sets the complex script font info. |
| [getSymbolFont()](#getSymbolFont--) | Returns or sets the symbolic font info. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Returns or sets the symbolic font info. |
| [getEscapement()](#getEscapement--) | Returns or sets the superscript or subscript text. |
| [setEscapement(float value)](#setEscapement-float-) | Returns or sets the superscript or subscript text. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Returns or sets the minimal font size, for which kerning should be switched on. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Returns or sets the minimal font size, for which kerning should be switched on. |
| [getLanguageId()](#getLanguageId--) | Returns or sets the Id of a proofing language. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Returns or sets the Id of a proofing language. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Returns or sets the Id of an alternative language. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Returns or sets the Id of an alternative language. |
| [getSpacing()](#getSpacing--) | Returns or sets the intercharacter spacing increment. |
| [setSpacing(float value)](#setSpacing-float-) | Returns or sets the intercharacter spacing increment. |
| [getSpellCheck()](#getSpellCheck--) | Gets or sets a value indicating whether spell checking is enabled for the text portion. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Gets or sets a value indicating whether spell checking is enabled for the text portion. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Returnerar LineFormat-egenskaperna för textkontur. Ingen arv tillämpas. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Returnerar textens FillFormat-egenskaper. Ingen arv tillämpas. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Returnerar textens EffectFormat-egenskaper. Ingen arv tillämpas. Skrivskyddad [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Returnerar:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Returnerar färgen som används för att markera en text. Ingen arv tillämpas. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Returnerar LineFormat-egenskaperna som används för att konturera understrykninglinjen. Ingen arv tillämpas. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Returnerar FillFormat-egenskaperna för understrykninglinjen. Ingen arv tillämpas. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Avgör om teckensnittet är fetstil. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Avgör om teckensnittet är fetstil. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Avgör om teckensnittet är kursivt. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Avgör om teckensnittet är kursivt. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Avgör om siffrorna ska ignorera den östasiatiska språksspecifika vertikala textlayouten. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Avgör om siffrorna ska ignorera den östasiatiska språksspecifika vertikala textlayouten. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Avgör om höjden på en text ska normaliseras. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Avgör om höjden på en text ska normaliseras. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Avgör om texten inte ska korrekturläsas. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Avgör om texten inte ska korrekturläsas. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Returnerar eller ställer in textens understrykningstyp. Ingen arv tillämpas. Läs/skriv [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Returnerar:**
byte
### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Returnerar eller ställer in textens understrykningstyp. Ingen arv tillämpas. Läs/skriv [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Returnerar eller ställer in typ av textkapitalisering. Ingen arv tillämpas. Läs/skriv [TextCapType](../../com.aspose.slides/textcaptype).

**Returnerar:**
byte
### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Returnerar eller ställer in typ av textkapitalisering. Ingen arv tillämpas. Läs/skriv [TextCapType](../../com.aspose.slides/textcaptype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Returnerar eller ställer in överstrykningstyp för en text. Ingen arv tillämpas. Läs/skriv [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Returnerar:**
byte
### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Returnerar eller ställer in överstrykningstyp för en text. Ingen arv tillämpas. Läs/skriv [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Avgör om understrykningsstilen har egna LineFormat-egenskaper eller ärver dem från textens LineFormat-egenskaper. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Avgör om understrykningsstilen har egna LineFormat-egenskaper eller ärver dem från textens LineFormat-egenskaper. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Avgör om understrykningsstilen har egna FillFormat-egenskaper eller ärver dem från textens FillFormat-egenskaper. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Avgör om understrykningsstilen har egna FillFormat-egenskaper eller ärver dem från textens FillFormat-egenskaper. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Returnerar eller ställer in teckensnittshöjden för en del. **Float.NaN** betyder att höjden är odefinierad och bör ärvas från Master. Läs/skriv float.

**Returnerar:**
float
### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Returnerar eller ställer in teckensnittshöjden för en del. **Float.NaN** betyder att höjden är odefinierad och bör ärvas från Master. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Returnerar eller ställer in information om det latinska teckensnittet. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Returnerar eller ställer in information om det latinska teckensnittet. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Returnerar eller ställer in information om det östasiatiska teckensnittet. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Returnerar eller ställer in information om det östasiatiska teckensnittet. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Returnerar eller ställer in information om det komplexa skriptteckensnittet. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Returnerar eller ställer in information om det komplexa skriptteckensnittet. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Returnerar eller ställer in information om det symboliska teckensnittet. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Returnerar eller ställer in information om det symboliska teckensnittet. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Returnerar eller ställer in text som är upphöjd eller nedsänkt. Värde från -100% (nedsänkt) till 100% (upphöjd). **Float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv float.

**Returnerar:**
float
### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Returnerar eller ställer in text som är upphöjd eller nedsänkt. Värde från -100% (nedsänkt) till 100% (upphöjd). **Float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Returnerar eller ställer in den minsta teckensnittsstorleken för vilken kerning ska slås på. **Float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv float.

**Returnerar:**
float
### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Returnerar eller ställer in den minsta teckensnittsstorleken för vilken kerning ska slås på. **Float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Returnerar eller ställer in ID för ett korrekturspråk. Används för stavnings- och grammatikkontroll. Läs/skriv String.

**Returnerar:**
java.lang.String
### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Returnerar eller ställer in ID för ett korrekturspråk. Används för stavnings- och grammatikkontroll. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Returnerar eller ställer in ID för ett alternativt språk. Läs/skriv String.

**Returnerar:**
java.lang.String
### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Returnerar eller ställer in ID för ett alternativt språk. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Returnerar eller ställer in interkaraktärsåståndsincrementen. **Float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv float.

**Returnerar:**
float
### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Returnerar eller ställer in interkaraktärsåståndsincrementen. **Float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Hämtar eller anger ett värde som visar om stavningskontroll är aktiverad för textdelen. När denna egenskap är satt till false undertrycks stavningskontroller för textelement. När den är satt till true tillåts stavningskontroll. Standardvärdet är false.

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

**Returnerar:**
boolean
### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

Hämtar eller anger ett värde som visar om stavningskontroll är aktiverad för textdelen. När denna egenskap är satt till false undertrycks stavningskontroller för textelement. När den är satt till true tillåts stavningskontroll. Standardvärdet är false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Åtkomst till den första textdelen inuti den första formen på den första bilden
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Aktivera stavningskontroll för denna textdel
>      portion.getPortionFormat().setSpellCheck(true);
>      // Spara den ändrade presentationen
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |