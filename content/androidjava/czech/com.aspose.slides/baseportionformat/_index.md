---
title: BasePortionFormat
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Společné vlastnosti formátování textové části.
type: docs
url: /cs/com.aspose.slides/baseportionformat/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Společné vlastnosti formátování textové části.
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Vrací vlastnosti LineFormat pro obrys textu. |
| [getFillFormat()](#getFillFormat--) | Vrací vlastnosti FillFormat textu. |
| [getEffectFormat()](#getEffectFormat--) | Vrací vlastnosti EffectFormat textu. |
| [getHighlightColor()](#getHighlightColor--) | Vrací barvu použitou pro zvýraznění textu. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Vrací vlastnosti LineFormat použité k ohraničení podtržité čáry. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Vrací vlastnosti FillFormat podtržité čáry. |
| [getFontBold()](#getFontBold--) | Určuje, zda je písmo tučné. |
| [setFontBold(byte value)](#setFontBold-byte-) | Určuje, zda je písmo tučné. |
| [getFontItalic()](#getFontItalic--) | Určuje, zda je písmo kurzívou. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Určuje, zda je písmo kurzívou. |
| [getKumimoji()](#getKumimoji--) | Určuje, zda mají čísla ignorovat specifické vertikální rozložení textu pro východoasijské jazyky. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Určuje, zda mají čísla ignorovat specifické vertikální rozložení textu pro východoasijské jazyky. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Určuje, zda má být výška textu normalizována. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Určuje, zda má být výška textu normalizována. |
| [getProofDisabled()](#getProofDisabled--) | Určuje, zda by text neměl být kontrolován pravopisem. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Určuje, zda by text neměl být kontrolován pravopisem. |
| [getFontUnderline()](#getFontUnderline--) | Vrací nebo nastavuje typ podtržení textu. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Vrací nebo nastavuje typ podtržení textu. |
| [getTextCapType()](#getTextCapType--) | Vrací nebo nastavuje typ kapitalizace textu. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Vrací nebo nastavuje typ kapitalizace textu. |
| [getStrikethroughType()](#getStrikethroughType--) | Vrací nebo nastavuje typ přeškrtnutí textu. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Vrací nebo nastavuje typ přeškrtnutí textu. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Určuje, zda podtržítko má vlastní vlastnosti LineFormat nebo je dědí z LineFormat textu. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Určuje, zda podtržítko má vlastní vlastnosti LineFormat nebo je dědí z LineFormat textu. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Určuje, zda podtržítko má vlastní vlastnosti FillFormat nebo je dědí z FillFormat textu. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Určuje, zda podtržítko má vlastní vlastnosti FillFormat nebo je dědí z FillFormat textu. |
| [getFontHeight()](#getFontHeight--) | Vrací nebo nastavuje výšku písma části. |
| [setFontHeight(float value)](#setFontHeight-float-) | Vrací nebo nastavuje výšku písma části. |
| [getLatinFont()](#getLatinFont--) | Vrací nebo nastavuje informace o latinském písmu. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje informace o latinském písmu. |
| [getEastAsianFont()](#getEastAsianFont--) | Vrací nebo nastavuje informace o východoasijském písmu. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje informace o východoasijském písmu. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Vrací nebo nastavuje informace o písmech pro složité skripty. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje informace o písmech pro složité skripty. |
| [getSymbolFont()](#getSymbolFont--) | Vrací nebo nastavuje informace o symbolických písmenech. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje informace o symbolických písmenech. |
| [getEscapement()](#getEscapement--) | Vrací nebo nastavuje text jako horní index nebo dolní index. |
| [setEscapement(float value)](#setEscapement-float-) | Vrací nebo nastavuje text jako horní index nebo dolní index. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Vrací nebo nastavuje minimální velikost písma, pro kterou se zapíná kerning. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Vrací nebo nastavuje minimální velikost písma, pro kterou se zapíná kerning. |
| [getLanguageId()](#getLanguageId--) | Vrací nebo nastavuje Id jazyka pro kontrolu pravopisu. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Vrací nebo nastavuje Id jazyka pro kontrolu pravopisu. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Vrací nebo nastavuje Id alternativního jazyka. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Vrací nebo nastavuje Id alternativního jazyka. |
| [getSpacing()](#getSpacing--) | Vrací nebo nastavuje přírůstek mezery mezi znaky. |
| [setSpacing(float value)](#setSpacing-float-) | Vrací nebo nastavuje přírůstek mezery mezi znaky. |
| [getSpellCheck()](#getSpellCheck--) | Získává nebo nastavuje hodnotu, která určuje, zda je pro část textu povolena kontrola pravopisu. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Získává nebo nastavuje hodnotu, která určuje, zda je pro část textu povolena kontrola pravopisu. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

**Vrací:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

Vrací vlastnosti LineFormat pro obrys textu. Není použita dědičnost. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Vrací vlastnosti FillFormat textu. Není použita dědičnost. Pouze pro čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Vrací vlastnosti EffectFormat textu. Není použita dědičnost. Pouze pro čtení [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Vrací:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Vrací barvu použitou pro zvýraznění textu. Není použita dědičnost. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Vrací vlastnosti LineFormat použité k ohraničení podtržité čáry. Není použita dědičnost. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Vrací vlastnosti FillFormat podtržité čáry. Není použita dědičnost. Pouze pro čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Určuje, zda je písmo tučné. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Určuje, zda je písmo tučné. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Určuje, zda je písmo kurzívou. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Určuje, zda je písmo kurzívou. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Určuje, zda mají čísla ignorovat specifické vertikální rozložení textu pro východoasijské jazyky. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Určuje, zda mají čísla ignorovat specifické vertikální rozložení textu pro východoasijské jazyky. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Určuje, zda má být výška textu normalizována. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Určuje, zda má být výška textu normalizována. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Určuje, zda by text neměl být kontrolován pravopisem. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Určuje, zda by text neměl být kontrolován pravopisem. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Vrací nebo nastavuje typ podtržení textu. Není použita dědičnost. Čtení/zápis [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Vrací:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Vrací nebo nastavuje typ podtržení textu. Není použita dědičnost. Čtení/zápis [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Vrací nebo nastavuje typ kapitalizace textu. Není použita dědičnost. Čtení/zápis [TextCapType](../../com.aspose.slides/textcaptype).

**Vrací:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Vrací nebo nastavuje typ kapitalizace textu. Není použita dědičnost. Čtení/zápis [TextCapType](../../com.aspose.slides/textcaptype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Vrací nebo nastavuje typ přeškrtnutí textu. Není použita dědičnost. Čtení/zápis [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Vrací:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Vrací nebo nastavuje typ přeškrtnutí textu. Není použita dědičnost. Čtení/zápis [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Určuje, zda podtržítko má vlastní vlastnosti LineFormat nebo je dědí z LineFormat textu. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Určuje, zda podtržítko má vlastní vlastnosti LineFormat nebo je dědí z LineFormat textu. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Určuje, zda podtržítko má vlastní vlastnosti FillFormat nebo je dědí z FillFormat textu. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Určuje, zda podtržítko má vlastní vlastnosti FillFormat nebo je dědí z FillFormat textu. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Vrací nebo nastavuje výšku písma části. **Float.NaN** znamená, že výška není definována a měla by být zděděna z Masteru. Čtení/zápis float .

**Vrací:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Vrací nebo nastavuje výšku písma části. **Float.NaN** znamená, že výška není definována a měla by být zděděna z Masteru. Čtení/zápis float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Vrací nebo nastavuje informace o latinském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Vrací nebo nastavuje informace o latinském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Vrací nebo nastavuje informace o východoasijském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Vrací nebo nastavuje informace o východoasijském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Vrací nebo nastavuje informace o písmu pro složité skripty. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Vrací nebo nastavuje informace o písmu pro složité skripty. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Vrací nebo nastavuje informace o symbolickém písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Vrací nebo nastavuje informace o symbolickém písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Vrací nebo nastavuje text jako horní nebo dolní index. Hodnota od -100 % (dolní index) do 100 % (horní index). **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis float .

**Vrací:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Vrací nebo nastavuje text jako horní nebo dolní index. Hodnota od -100 % (dolní index) do 100 % (horní index). **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Vrací nebo nastavuje minimální velikost písma, pro kterou se zapíná kerning. **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis float .

**Vrací:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Vrací nebo nastavuje minimální velikost písma, pro kterou se zapíná kerning. **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Vrací nebo nastavuje Id jazyka pro kontrolu pravopisu. Používá se pro kontrolu pravopisu a gramatiky. Čtení/zápis String.

**Vrací:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Vrací nebo nastavuje Id jazyka pro kontrolu pravopisu. Používá se pro kontrolu pravopisu a gramatiky. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Vrací nebo nastavuje Id alternativního jazyka. Čtení/zápis String.

**Vrací:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Vrací nebo nastavuje Id alternativního jazyka. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Vrací nebo nastavuje přírůstek mezery mezi znaky. **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis float .

**Vrací:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Vrací nebo nastavuje přírůstek mezery mezi znaky. **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Získává nebo nastavuje hodnotu, která určuje, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové elementy je potlačena. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je false.

**Vrací:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

Získává nebo nastavuje hodnotu, která určuje, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové elementy je potlačena. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Přístup k prvnímu úseku textu v první podobě na první snímku
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Povolit kontrolu pravopisu pro tuto část textu
>      portion.getPortionFormat().setSpellCheck(true);
>      // Uložit upravenou prezentaci
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
boolean

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Přístup k prvnímu úseku textu v první podobě na prvním snímku
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Povolit kontrolu pravopisu pro tuto část textu
>      portion.getPortionFormat().setSpellCheck(true);
>      // Uložit upravenou prezentaci
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |