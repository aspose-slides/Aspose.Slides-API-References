---
title: BasePortionFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Gemensamma formateringsegenskaper för textavsnitt.
type: docs
url: /sv/com.aspose.slides/baseportionformat/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Gemensamma formateringsegenskaper för textavsnitt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Returnerar LineFormat-egenskaperna för textkontur. |
| [getFillFormat()](#getFillFormat--) | Returnerar FillFormat-egenskaperna för texten. |
| [getEffectFormat()](#getEffectFormat--) | Returnerar EffectFormat-egenskaperna för texten. |
| [getHighlightColor()](#getHighlightColor--) | Returnerar färgen som används för att markera en text. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Returnerar LineFormat-egenskaperna som används för att konturera understrykningslinjen. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Returnerar FillFormat-egenskaperna för understrykningslinjen. |
| [getFontBold()](#getFontBold--) | Avgör om typsnittet är fetstil. |
| [setFontBold(byte value)](#setFontBold-byte-) | Avgör om typsnittet är fetstil. |
| [getFontItalic()](#getFontItalic--) | Avgör om typsnittet är kursiv. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Avgör om typsnittet är kursiv. |
| [getKumimoji()](#getKumimoji--) | Avgör om siffrorna ska ignorera det östasiatiska språksspecifika vertikala textlayouten. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Avgör om siffrorna ska ignorera det östasiatiska språksspecifika vertikala textlayouten. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Avgör om höjden på en text ska normaliseras. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Avgör om höjden på en text ska normaliseras. |
| [getProofDisabled()](#getProofDisabled--) | Avgör om texten inte ska rättas. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Avgör om texten inte ska rättas. |
| [getFontUnderline()](#getFontUnderline--) | Returnerar eller anger understrykningstypen för texten. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Returnerar eller anger understrykningstypen för texten. |
| [getTextCapType()](#getTextCapType--) | Returnerar eller anger typ av textversalisering. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Returnerar eller anger typ av textversalisering. |
| [getStrikethroughType()](#getStrikethroughType--) | Returnerar eller anger genomstrykningstypen för en text. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Returnerar eller anger genomstrykningstypen för en text. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Avgör om understrykningsstilen har egna LineFormat-egenskaper eller ärver dem från textens LineFormat-egenskaper. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Avgör om understrykningsstilen har egna LineFormat-egenskaper eller ärver dem från textens LineFormat-egenskaper. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Avgör om understrykningsstilen har egna FillFormat-egenskaper eller ärver dem från textens FillFormat-egenskaper. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Avgör om understrykningsstilen har egna FillFormat-egenskaper eller ärver dem från textens FillFormat-egenskaper. |
| [getFontHeight()](#getFontHeight--) | Returnerar eller anger teckensnittshöjden för en del. |
| [setFontHeight(float value)](#setFontHeight-float-) | Returnerar eller anger teckensnittshöjden för en del. |
| [getLatinFont()](#getLatinFont--) | Returnerar eller anger informationen för det latinska teckensnittet. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Returnerar eller anger informationen för det latinska teckensnittet. |
| [getEastAsianFont()](#getEastAsianFont--) | Returnerar eller anger informationen för det östasiatiska teckensnittet. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Returnerar eller anger informationen för det östasiatiska teckensnittet. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Returnerar eller anger informationen för det komplexa skriptteckensnittet. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Returnerar eller anger informationen för det komplexa skriptteckensnittet. |
| [getSymbolFont()](#getSymbolFont--) | Returnerar eller anger informationen för det symboliska teckensnittet. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Returnerar eller anger informationen för det symboliska teckensnittet. |
| [getEscapement()](#getEscapement--) | Returnerar eller anger upphöjd eller nedsänkt text. |
| [setEscapement(float value)](#setEscapement-float-) | Returnerar eller anger upphöjd eller nedsänkt text. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Returnerar eller anger minimal teckensnittsstorlek för vilken kerning ska aktiveras. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Returnerar eller anger minimal teckensnittsstorlek för vilken kerning ska aktiveras. |
| [getLanguageId()](#getLanguageId--) | Returnerar eller anger ID för ett korrekturspråk. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Returnerar eller anger ID för ett korrekturspråk. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Returnerar eller anger ID för ett alternativt språk. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Returnerar eller anger ID för ett alternativt språk. |
| [getSpacing()](#getSpacing--) | Returnerar eller anger ökning av teckentäthetsavstånd. |
| [setSpacing(float value)](#setSpacing-float-) | Returnerar eller anger ökning av teckentäthetsavstånd. |
| [getSpellCheck()](#getSpellCheck--) | Hämtar eller anger ett värde som indikerar om stavningskontroll är aktiverad för textavsnittet. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Hämtar eller anger ett värde som indikerar om stavningskontroll är aktiverad för textavsnittet. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Skrivskyddad long.

**Returnerar:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

Returnerar LineFormat-egenskaperna för textkontur. Ingen arv tillämpas. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Returnerar FillFormat-egenskaperna för texten. Ingen arv tillämpas. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Returnerar EffectFormat-egenskaperna för texten. Ingen arv tillämpas. Skrivskyddad [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Returnerar:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Returnerar färgen som används för att markera en text. Ingen arv tillämpas. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Returnerar LineFormat-egenskaperna som används för att konturera understrykningslinjen. Ingen arv tillämpas. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Returnerar FillFormat-egenskaperna för understrykningslinjen. Ingen arv tillämpas. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Avgör om typsnittet är fetstil. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Avgör om typsnittet är fetstil. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Avgör om typsnittet är kursiv. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Avgör om typsnittet är kursiv. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Avgör om siffrorna ska ignorera det östasiatiska språksspecifika vertikala textlayouten. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Avgör om siffrorna ska ignorera det östasiatiska språksspecifika vertikala textlayouten. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Avgör om höjden på en text ska normaliseras. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Avgör om höjden på en text ska normaliseras. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Avgör om texten inte ska rättas. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Avgör om texten inte ska rättas. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Returnerar eller anger understrykningstypen för texten. Ingen arv tillämpas. Läs/skriv [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Returnerar:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Returnerar eller anger understrykningstypen för texten. Ingen arv tillämpas. Läs/skriv [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Returnerar eller anger typ av textversalisering. Ingen arv tillämpas. Läs/skriv [TextCapType](../../com.aspose.slides/textcaptype).

**Returnerar:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Returnerar eller anger typ av textversalisering. Ingen arv tillämpas. Läs/skriv [TextCapType](../../com.aspose.slides/textcaptype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Returnerar eller anger genomstrykningstypen för en text. Ingen arv tillämpas. Läs/skriv [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Returnerar:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Returnerar eller anger genomstrykningstypen för en text. Ingen arv tillämpas. Läs/skriv [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Avgör om understrykningsstilen har egna LineFormat-egenskaper eller ärver dem från textens LineFormat-egenskaper. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Avgör om understrykningsstilen har egna LineFormat-egenskaper eller ärver dem från textens LineFormat-egenskaper. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Avgör om understrykningsstilen har egna FillFormat-egenskaper eller ärver dem från textens FillFormat-egenskaper. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Avgör om understrykningsstilen har egna FillFormat-egenskaper eller ärver dem från textens FillFormat-egenskaper. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Returnerar eller anger teckensnittshöjden för en del. **Float.NaN** betyder att höjden är odefinierad och ska ärvas från Master. Läs/skriv  float .

**Returnerar:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Returnerar eller anger teckensnittshöjden för en del. **Float.NaN** betyder att höjden är odefinierad och ska ärvas från Master. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Returnerar eller anger informationen för det latinska teckensnittet. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Returnerar eller anger informationen för det latinska teckensnittet. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Returnerar eller anger informationen för det östasiatiska teckensnittet. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Returnerar eller anger informationen för det östasiatiska teckensnittet. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Returnerar eller anger informationen för det komplexa skriptteckensnittet. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Returnerar eller anger informationen för det komplexa skriptteckensnittet. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Returnerar eller anger informationen för det symboliska teckensnittet. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Returnerar eller anger informationen för det symboliska teckensnittet. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Returnerar eller anger upphöjd eller nedsänkt text. Värde från -100% (nedsänkt) till 100% (upphöjd). **Float.NaN** betyder att värdet är odefinierat och ska ärvas från Master. Läs/skriv  float .

**Returnerar:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Returnerar eller anger upphöjd eller nedsänkt text. Värde från -100% (nedsänkt) till 100% (upphöjd). **Float.NaN** betyder att värdet är odefinierat och ska ärvas från Master. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Returnerar eller anger minimal teckensnittsstorlek för vilken kerning ska aktiveras. **Float.NaN** betyder att värdet är odefinierat och ska ärvas från Master. Läs/skriv  float .

**Returnerar:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Returnerar eller anger minimal teckensnittsstorlek för vilken kerning ska aktiveras. **Float.NaN** betyder att värdet är odefinierat och ska ärvas från Master. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Returnerar eller anger ID för ett korrekturspråk. Används för stavnings- och grammatikkontroll. Läs/skriv String.

**Returnerar:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Returnerar eller anger ID för ett korrekturspråk. Används för stavnings- och grammatikkontroll. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Returnerar eller anger ID för ett alternativt språk. Läs/skriv String.

**Returnerar:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Returnerar eller anger ID för ett alternativt språk. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Returnerar eller anger ökning av teckentäthetsavstånd. **Float.NaN** betyder att värdet är odefinierat och ska ärvas från Master. Läs/skriv  float .

**Returnerar:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Returnerar eller anger ökning av teckentäthetsavstånd. **Float.NaN** betyder att värdet är odefinierat och ska ärvas från Master. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Hämtar eller anger ett värde som indikerar om stavningskontroll är aktiverad för textavsnittet. När detta egenskap är satt till false, undertrycks stavningskontroller för textelement. När satt till true, tillåts stavningskontroll. Standardvärde är  false .

--------------------

> ```
> Nästa exempel visar hur man aktiverar SpellCheck-flaggan innan presentationen sparas:
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
public final void setSpellCheck(boolean value)
```

Hämtar eller anger ett värde som indikerar om stavningskontroll är aktiverad för textavsnittet. När detta egenskap är satt till false, undertrycks stavningskontroller för textelement. När satt till true, tillåts stavningskontroll. Standardvärde är  false .

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