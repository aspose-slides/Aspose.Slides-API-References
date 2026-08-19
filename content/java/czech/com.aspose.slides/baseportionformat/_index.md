---
title: BasePortionFormat
second_title: Aspose.Slides pro Java – referenční příručka API
description: Společné vlastnosti formátování úseku textu.
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

Společné vlastnosti formátování úseku textu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Vrací vlastnosti LineFormat pro obrysování textu. |
| [getFillFormat()](#getFillFormat--) | Vrací vlastnosti FillFormat textu. |
| [getEffectFormat()](#getEffectFormat--) | Vrací vlastnosti EffectFormat textu. |
| [getHighlightColor()](#getHighlightColor--) | Vrací barvu použitou pro zvýraznění textu. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Vrací vlastnosti LineFormat použité k obrysování podtržení. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Vrací vlastnosti FillFormat podtržité čáry. |
| [getFontBold()](#getFontBold--) | Určuje, zda je písmo tučné. |
| [setFontBold(byte value)](#setFontBold-byte-) | Určuje, zda je písmo tučné. |
| [getFontItalic()](#getFontItalic--) | Určuje, zda je písmo kurzíva. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Určuje, zda je písmo kurzíva. |
| [getKumimoji()](#getKumimoji--) | Určuje, zda čísla mají ignorovat vertikální rozložení textu specifické pro východoasijské jazyky. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Určuje, zda čísla mají ignorovat vertikální rozložení textu specifické pro východoasijské jazyky. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Určuje, zda má být výška textu normalizována. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Určuje, zda má být výška textu normalizována. |
| [getProofDisabled()](#getProofDisabled--) | Určuje, zda text nemá být kontrolován pravopisem. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Určuje, zda text nemá být kontrolován pravopisem. |
| [getFontUnderline()](#getFontUnderline--) | Vrací nebo nastavuje typ podtržení textu. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Vrací nebo nastavuje typ podtržení textu. |
| [getTextCapType()](#getTextCapType--) | Vrací nebo nastavuje typ kapitalizace textu. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Vrací nebo nastavuje typ kapitalizace textu. |
| [getStrikethroughType()](#getStrikethroughType--) | Vrací nebo nastavuje typ přeškrtnutí textu. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Vrací nebo nastavuje typ přeškrtnutí textu. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo je dědí z vlastností LineFormat textu. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo je dědí z vlastností LineFormat textu. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo je dědí z vlastností FillFormat textu. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Určuje, či má styl podtržení vlastní vlastnosti FillFormat nebo je dědí z vlastností FillFormat textu. |
| [getFontHeight()](#getFontHeight--) | Vrací nebo nastavuje výšku písma úseku. |
| [setFontHeight(float value)](#setFontHeight-float-) | Vrací nebo nastavuje výšku písma úseku. |
| [getLatinFont()](#getLatinFont--) | Vrací nebo nastavuje informace o latinském písmu. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje informace o latinském písmu. |
| [getEastAsianFont()](#getEastAsianFont--) | Vrací nebo nastavuje informace o východoasijském písmu. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje informace o východoasijském písmu. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Vrací nebo nastavuje informace o komplexním skriptu písma. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje informace o komplexním skriptu písma. |
| [getSymbolFont()](#getSymbolFont--) | Vrací nebo nastavuje informace o symbolickém písmu. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje informace o symbolickém písmu. |
| [getEscapement()](#getEscapement--) | Vrací nebo nastavuje text jako horní index nebo dolní index. |
| [setEscapement(float value)](#setEscapement-float-) | Vrací nebo nastavuje text jako horní index nebo dolní index. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Vrací nebo nastavuje minimální velikost písma, pro kterou má být zapnutý kerning. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Vrací nebo nastavuje minimální velikost písma, pro kterou má být zapnutý kerning. |
| [getLanguageId()](#getLanguageId--) | Vrací nebo nastavuje Id jazyka pro kontrolu pravopisu. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Vrací nebo nastavuje Id jazyka pro kontrolu pravopisu. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Vrací nebo nastavuje Id alternativního jazyka. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Vrací nebo nastavuje Id alternativního jazyka. |
| [getSpacing()](#getSpacing--) | Vrací nebo nastavuje přírůstek mezery mezi znaky. |
| [setSpacing(float value)](#setSpacing-float-) | Vrací nebo nastavuje přírůstek mezery mezi znaky. |
| [getSpellCheck()](#getSpellCheck--) | Vrací nebo nastavuje hodnotu určující, zda je kontrola pravopisu povolena pro úsek textu. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Vrací nebo nastavuje hodnotu určující, zda je kontrola pravopisu povolena pro úsek textu. |

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

Vrací vlastnosti LineFormat pro obrysování textu. Není použito dědění. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Vrací vlastnosti FillFormat textu. Není použito dědění. Pouze pro čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Vrací vlastnosti EffectFormat textu. Není použito dědění. Pouze pro čtení [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Vrací:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Vrací barvu použitou pro zvýraznění textu. Není použito dědění. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Vrací vlastnosti LineFormat použité k obrysování podtržené čáry. Není použito dědění. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Vrací vlastnosti FillFormat podtržené čáry. Není použito dědění. Pouze pro čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Určuje, zda je písmo tučné. Není použito dědění. Pro čtení i zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Určuje, zda je písmo tučné. Není použito dědění. Pro čtení i zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Určuje, zda je písmo kurzíva. Není použito dědění. Pro čtení i zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Určuje, zda je písmo kurzíva. Není použito dědění. Pro čtení i zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Určuje, zda čísla mají ignorovat vertikální rozložení textu specifické pro východoasijské jazyky. Není použito dědění. Pro čtení i zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Určuje, zda čísla mají ignorovat vertikální rozložení textu specifické pro východoasijské jazyky. Není použito dědění. Pro čtení i zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Určuje, zda má být výška textu normalizována. Není použito dědění. Pro čtení i zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Určuje, zda má být výška textu normalizována. Není použito dědění. Pro čtení i zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Určuje, zda text nemá být kontrolován pravopisem. Není použito dědění. Pro čtení i zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Určuje, zda text nemá být kontrolován pravopisem. Není použito dědění. Pro čtení i zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Vrací nebo nastavuje typ podtržení textu. Není použito dědění. Pro čtení i zápis [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Vrací:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Vrací nebo nastavuje typ podtržení textu. Není použito dědění. Pro čtení i zápis [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Vrací nebo nastavuje typ kapitalizace textu. Není použito dědění. Pro čtení i zápis [TextCapType](../../com.aspose.slides/textcaptype).

**Vrací:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Vrací nebo nastavuje typ kapitalizace textu. Není použito dědění. Pro čtení i zápis [TextCapType](../../com.aspose.slides/textcaptype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Vrací nebo nastavuje typ přeškrtnutí textu. Není použito dědění. Pro čtení i zápis [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Vrací:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Vrací nebo nastavuje typ přeškrtnutí textu. Není použito dědění. Pro čtení i zápis [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo je dědí z vlastností LineFormat textu. Pro čtení i zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo je dědí z vlastností LineFormat textu. Pro čtení i zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo je dědí z vlastností FillFormat textu. Pro čtení i zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo je dědí z vlastností FillFormat textu. Pro čtení i zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Vrací nebo nastavuje výšku písma úseku. **Float.NaN** znamená, že výška není definována a měla by být zděděna z Masteru. Pro čtení i zápis  float .

**Vrací:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Vrací nebo nastavuje výšku písma úseku. **Float.NaN** znamená, že výška není definována a měla by být zděděna z Masteru. Pro čtení i zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Vrací nebo nastavuje informace o latinském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Pro čtení i zápis [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Vrací nebo nastavuje informace o latinském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Pro čtení i zápis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Vrací nebo nastavuje informace o východoasijském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Pro čtení i zápis [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Vrací nebo nastavuje informace o východoasijském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Pro čtení i zápis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Vrací nebo nastavuje informace o komplexním skriptu písma. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Pro čtení i zápis [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Vrací nebo nastavuje informace o komplexním skriptu písma. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Pro čtení i zápis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Vrací nebo nastavuje informace o symbolickém písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Pro čtení i zápis [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Vrací nebo nastavuje informace o symbolickém písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Pro čtení i zápis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Vrací nebo nastavuje text jako horní nebo dolní index. Hodnota od -100 % (dolní index) do 100 % (horní index). **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Pro čtení i zápis  float .

**Vrací:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Vrací nebo nastavuje text jako horní nebo dolní index. Hodnota od -100 % (dolní index) do 100 % (horní index). **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Pro čtení i zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Vrací nebo nastavuje minimální velikost písma, pro kterou má být zapnutý kerning. **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Pro čtení i zápis  float .

**Vrací:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Vrací nebo nastavuje minimální velikost písma, pro kterou má být zapnutý kerning. **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Pro čtení i zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Vrací nebo nastavuje Id jazyka pro kontrolu pravopisu. Používá se pro kontrolu pravopisu a gramatiky. Pro čtení i zápis String.

**Vrací:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Vrací nebo nastavuje Id jazyka pro kontrolu pravopisu. Používá se pro kontrolu pravopisu a gramatiky. Pro čtení i zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Vrací nebo nastavuje Id alternativního jazyka. Pro čtení i zápis String.

**Vrací:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Vrací nebo nastavuje Id alternativního jazyka. Pro čtení i zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Vrací nebo nastavuje přírůstek mezery mezi znaky. **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Pro čtení i zápis  float .

**Vrací:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Vrací nebo nastavuje přírůstek mezery mezi znaky. **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Pro čtení i zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Vrací nebo nastavuje hodnotu určující, zda je kontrola pravopisu povolena pro úsek textu. Když je tato vlastnost nastavena na false, kontroly pravopisu pro textové prvky jsou potlačeny. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je false.

**Vrací:**
boolean

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

**Vrací:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

Vrací nebo nastavuje hodnotu určující, zda je kontrola pravopisu povolena pro úsek textu. Když je tato vlastnost nastavena na false, kontroly pravopisu pro textové prvky jsou potlačeny. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je false.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |