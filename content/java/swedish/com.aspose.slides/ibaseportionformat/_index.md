---
title: IBasePortionFormat
second_title: Aspose.Slides for Java API Reference
description: Denna klass innehåller formateringsegenskaperna för textdelar.
type: docs
url: /sv/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Denna klass innehåller formateringsegenskaperna för textdelar. Till skillnad från [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) är alla egenskaper i denna klass skrivbara.

--------------------

Denna klass används för att returnera och manipulera formateringsegenskaper för textdelar som är definierade för den specifika delen. Detta betyder att ingen arv tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formateringsparameter-värdena inklusive arvade måste du använda [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective)-metoden som returnerar en [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-instans.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Returnerar LineFormat-egenskaperna för textkontur. |
| [getFillFormat()](#getFillFormat--) | Returnerar textens FillFormat-egenskaper. |
| [getEffectFormat()](#getEffectFormat--) | Returnerar textens EffectFormat-egenskaper. |
| [getHighlightColor()](#getHighlightColor--) | Returnerar färgen som används för att markera en text. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Returnerar LineFormat-egenskaperna som används för att omringa understrykning. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Returnerar understrykningens FillFormat-egenskaper. |
| [getFontBold()](#getFontBold--) | Avgör om teckensnittet är fetstil. |
| [setFontBold(byte value)](#setFontBold-byte-) | Avgör om teckensnittet är fetstil. |
| [getFontItalic()](#getFontItalic--) | Avgör om teckensnittet är kursiv. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Avgör om teckensnittet är kursiv. |
| [getKumimoji()](#getKumimoji--) | Avgör om siffrorna ska ignorera östlig språk-specifik vertikal textlayout. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Avgör om siffrorna ska ignorera östlig språk-specifik vertikal textlayout. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Avgör om höjden på en text ska normaliseras. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Avgör om höjden på en text ska normaliseras. |
| [getProofDisabled()](#getProofDisabled--) | Avgör om texten inte ska rättas. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Avgör om texten inte ska rättas. |
| [getFontUnderline()](#getFontUnderline--) | Returnerar eller anger typ av textunderstrykning. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Returnerar eller anger typ av textunderstrykning. |
| [getTextCapType()](#getTextCapType--) | Returnerar eller anger typ av textversalisering. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Returnerar eller anger typ av textversalisering. |
| [getStrikethroughType()](#getStrikethroughType--) | Returnerar eller anger typ av genomstrykning för en text. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Returnerar eller anger typ av genomstrykning för en text. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Avgör om understrykningens stil har egna LineFormat-egenskaper eller ärvt dem från textens LineFormat. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Avgör om understrykningens stil har egna LineFormat-egenskaper eller ärvt dem från textens LineFormat. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Avgör om understrykningens stil har egna FillFormat-egenskaper eller ärvt dem från textens FillFormat. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Avgör om understrykningens stil har egna FillFormat-egenskaper eller ärvt dem från textens FillFormat. |
| [getFontHeight()](#getFontHeight--) | Returnerar eller anger teckensnittshöjden för en del. |
| [setFontHeight(float value)](#setFontHeight-float-) | Returnerar eller anger teckensnittshöjden för en del. |
| [getLatinFont()](#getLatinFont--) | Returnerar eller anger latin-teckensnittsinfo. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Returnerar eller anger latin-teckensnittsinfo. |
| [getEastAsianFont()](#getEastAsianFont--) | Returnerar eller anger östasiatiskt teckensnittsinfo. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Returnerar eller anger östasiatiskt teckensnittsinfo. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Returnerar eller anger komplext skript-teckensnittsinfo. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Returnerar eller anger komplext skript-teckensnittsinfo. |
| [getSymbolFont()](#getSymbolFont--) | Returnerar eller anger symbol-teckensnittsinfo. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Returnerar eller anger symbol-teckensnittsinfo. |
| [getEscapement()](#getEscapement--) | Returnerar eller anger upphöjd eller nedsänkt text. |
| [setEscapement(float value)](#setEscapement-float-) | Returnerar eller anger upphöjd eller nedsänkt text. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Returnerar eller anger minimal teckensnittsstorlek för vilken kerning ska slås på. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Returnerar eller anger minimal teckensnittsstorlek för vilken kerning ska slås på. |
| [getLanguageId()](#getLanguageId--) | Returnerar eller anger Id för ett korrekturspråk. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Returnerar eller anger Id för ett korrekturspråk. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Returnerar eller anger Id för ett alternativt språk. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Returnerar eller anger Id för ett alternativt språk. |
| [getSpacing()](#getSpacing--) | Returnerar eller anger intertecken-avståndsökning. |
| [setSpacing(float value)](#setSpacing-float-) | Returnerar eller anger intertecken-avståndsökning. |
| [getSpellCheck()](#getSpellCheck--) | Hämtar eller anger om stavningskontroll är aktiverad för textdelen. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Hämtar eller anger om stavningskontroll är aktiverad för textdelen. |
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

Returnerar LineFormat-egenskaperna som används för att omringa understrykning. Ingen arv tillämpas. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Returnerar understrykningslinjens FillFormat-egenskaper. Ingen arv tillämpas. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

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

Avgör om teckensnittet är kursiv. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Avgör om teckensnittet är kursiv. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Avgör om siffrorna ska ignorera östlig språk-specifik vertikal textlayout. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Avgör om siffrorna ska ignorera östlig språk-specifik vertikal textlayout. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

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

Avgör om texten inte ska rättas. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Avgör om texten inte ska rättas. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Returnerar eller anger typ av textunderstrykning. Ingen arv tillämpas. Läs/skriv [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Returnerar:**
byte
### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Returnerar eller anger typ av textunderstrykning. Ingen arv tillämpas. Läs/skriv [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Returnerar eller anger typ av textversalisering. Ingen arv tillämpas. Läs/skriv [TextCapType](../../com.aspose.slides/textcaptype).

**Returnerar:**
byte
### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Returnerar eller anger typ av textversalisering. Ingen arv tillämpas. Läs/skriv [TextCapType](../../com.aspose.slides/textcaptype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Returnerar eller anger typ av genomstrykning för en text. Ingen arv tillämpas. Läs/skriv [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Returnerar:**
byte
### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Returnerar eller anger typ av genomstrykning för en text. Ingen arv tillämpas. Läs/skriv [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Avgör om understrykningsstilen har egna LineFormat-egenskaper eller ärver dem från textens LineFormat. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Avgör om understrykningsstilen har egna LineFormat-egenskaper eller ärver dem från textens LineFormat. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Avgör om understrykningsstilen har egna FillFormat-egenskaper eller ärver dem från textens FillFormat. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Avgör om understrykningsstilen har egna FillFormat-egenskaper eller ärver dem från textens FillFormat. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Returnerar eller anger teckensnittshöjden för en del. **Float.NaN** betyder att höjden är odefinierad och bör ärvas från Master. Läs/skriv float.

**Returnerar:**
float
### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Returnerar eller anger teckensnittshöjden för en del. **Float.NaN** betyder att höjden är odefinierad och bör ärvas från Master. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Returnerar eller anger latin-teckensnittsinfo. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Returnerar eller anger latin-teckensnittsinfo. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Returnerar eller anger östasiatiskt teckensnittsinfo. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Returnerar eller anger östasiatiskt teckensnittsinfo. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Returnerar eller anger komplext skript-teckensnittsinfo. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Returnerar eller anger komplext skript-teckensnittsinfo. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Returnerar eller anger symbol-teckensnittsinfo. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Returnerar eller anger symbol-teckensnittsinfo. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Returnerar eller anger upphöjd eller nedsänkt text. Värde från -100 % (nedsänkt) till 100 % (upphöjd). **Float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv float.

**Returnerar:**
float
### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Returnerar eller anger upphöjd eller nedsänkt text. Värde från -100 % (nedsänkt) till 100 % (upphöjd). **Float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Returnerar eller anger minimal teckensnittsstorlek för vilken kerning ska slås på. **Float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv float.

**Returnerar:**
float
### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Returnerar eller anger minimal teckensnittsstorlek för vilken kerning ska slås på. **Float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Returnerar eller anger Id för ett korrekturspråk. Används för stavnings- och grammatikkontroll. Läs/skriv String.

**Returnerar:**
java.lang.String
### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Returnerar eller anger Id för ett korrekturspråk. Används för stavnings- och grammatikkontroll. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Returnerar eller anger Id för ett alternativt språk. Läs/skriv String.

**Returnerar:**
java.lang.String
### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Returnerar eller anger Id för ett alternativt språk. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Returnerar eller anger intertecken-avståndsökning. **Float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv float.

**Returnerar:**
float
### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Returnerar eller anger intertecken-avståndsökning. **Float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Hämtar eller anger om stavningskontroll är aktiverad för textdelen. När egenskapen är falsk undertrycks stavningskontroll för textelement. När den är sann är stavningskontroll tillåten. Standardvärdet är falskt.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Åtkomst till den första textdelen i den första formen på den första bilden
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Aktivera stavningskontroll för denna textdel
>      portion.getPortionFormat().setSpellCheck(true);
>      // Spara den modifierade presentationen
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

Hämtar eller anger om stavningskontroll är aktiverad för textdelen. När egenskapen är falsk undertrycks stavningskontroll för textelement. När den är sann är stavningskontroll tillåten. Standardvärdet är falskt.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Åtkomst till den första textdelen i den första formen på den första bilden
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Aktivera stavningskontroll för denna textdel
>      portion.getPortionFormat().setSpellCheck(true);
>      // Spara den modifierade presentationen
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |