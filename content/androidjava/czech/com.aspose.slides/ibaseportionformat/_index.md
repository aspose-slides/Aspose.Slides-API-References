---
title: IBasePortionFormat
second_title: Aspose.Slides for Android via Java API Reference
description: This class contains the text portion formatting properties.
type: docs
url: /cs/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Tato třída obsahuje vlastnosti formátování textových částí. Na rozdíl od [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

--------------------

Tato třída se používá k vrácení a manipulaci s vlastnostmi formátování textových částí definovanými pro konkrétní část. To znamená, že při získávání hodnot se nepoužije dědičnost, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Chcete-li získat efektivní hodnoty parametrů formátování včetně zděděných, musíte použít metodu [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective), která vrací instanci [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Metody

| Metoda | Popis |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Vrací vlastnosti LineFormat pro obrys textu. |
| [getFillFormat()](#getFillFormat--) | Vrací vlastnosti FillFormat textu. |
| [getEffectFormat()](#getEffectFormat--) | Vrací vlastnosti EffectFormat textu. |
| [getHighlightColor()](#getHighlightColor--) | Vrací barvu používanou k zvýraznění textu. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Vrací vlastnosti LineFormat použité k obrysování podtržité čáry. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Vrací vlastnosti FillFormat podtržité čáry. |
| [getFontBold()](#getFontBold--) | Určuje, zda je písmo tučné. |
| [setFontBold(byte value)](#setFontBold-byte-) | Určuje, zda je písmo tučné. |
| [getFontItalic()](#getFontItalic--) | Určuje, zda je písmo kurzívní. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Určuje, zda je písmo kurzívní. |
| [getKumimoji()](#getKumimoji--) | Určuje, zda čísla mají ignorovat specifické svislé rozložení textu pro východní jazyky. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Určuje, zda čísla mají ignorovat specifické svislé rozložení textu pro východní jazyky. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Určuje, zda výška textu má být normalizována. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Určuje, zda výška textu má být normalizována. |
| [getProofDisabled()](#getProofDisabled--) | Určuje, zda by text neměl být kontrolován. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Určuje, zda by text neměl být kontrolován. |
| [getFontUnderline()](#getFontUnderline--) | Vrací nebo nastavuje typ podtržení textu. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Vrací nebo nastavuje typ podtržení textu. |
| [getTextCapType()](#getTextCapType--) | Vrací nebo nastavuje typ kapitalizace textu. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Vrací nebo nastavuje typ kapitalizace textu. |
| [getStrikethroughType()](#getStrikethroughType--) | Vrací nebo nastavuje typ přeškrtnutí textu. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Vrací nebo nastavuje typ přeškrtnutí textu. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Určuje, zda styl podtržení má vlastní vlastnosti LineFormat nebo je dědí z vlastností LineFormat textu. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Určuje, zda styl podtržení má vlastní vlastnosti LineFormat nebo je dědí z vlastností LineFormat textu. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Určuje, zda styl podtržení má vlastní vlastnosti FillFormat nebo je dědí z vlastností FillFormat textu. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Určuje, zda styl podtržení má vlastní vlastnosti FillFormat nebo je dědí z vlastností FillFormat textu. |
| [getFontHeight()](#getFontHeight--) | Vrací nebo nastavuje výšku písma části. |
| [setFontHeight(float value)](#setFontHeight-float-) | Vrací nebo nastavuje výšku písma části. |
| [getLatinFont()](#getLatinFont--) | Vrací nebo nastavuje informace o latinském písmu. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje informace o latinském písmu. |
| [getEastAsianFont()](#getEastAsianFont--) | Vrací nebo nastavuje informace o východoasijském písmu. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje informace o východoasijském písmu. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Vrací nebo nastavuje informace o písmu pro komplexní skripty. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje informace o písmu pro komplexní skripty. |
| [getSymbolFont()](#getSymbolFont--) | Vrací nebo nastavuje informace o symbolickém písmu. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje informace o symbolickém písmu. |
| [getEscapement()](#getEscapement--) | Vrací nebo nastavuje text v superskriptu nebo subskriptu. |
| [setEscapement(float value)](#setEscapement-float-) | Vrací nebo nastavuje text v superskriptu nebo subskriptu. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Vrací nebo nastavuje minimální velikost písma, pro kterou se má zapnout kerning. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Vrací nebo nastavuje minimální velikost písma, pro kterou se má zapnout kerning. |
| [getLanguageId()](#getLanguageId--) | Vrací nebo nastavuje ID jazykové kontroly. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Vrací nebo nastavuje ID jazykové kontroly. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Vrací nebo nastavuje ID alternativního jazyka. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Vrací nebo nastavuje ID alternativního jazyka. |
| [getSpacing()](#getSpacing--) | Vrací nebo nastavuje přírůstek mezery mezi znaky. |
| [setSpacing(float value)](#setSpacing-float-) | Vrací nebo nastavuje přírůstek mezery mezi znaky. |
| [getSpellCheck()](#getSpellCheck--) | Získá nebo nastaví hodnotu, která určuje, zda je pro část textu povolena kontrola pravopisu. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Získá nebo nastaví hodnotu, která určuje, zda je pro část textu povolena kontrola pravopisu. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Vrací vlastnosti LineFormat pro obrys textu. Není použita dědičnost. Pouze ke čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Vrací vlastnosti FillFormat textu. Není použita dědičnost. Pouze ke čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Vrací vlastnosti EffectFormat textu. Není použita dědičnost. Pouze ke čtení [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Vrací:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Vrací barvu používanou k zvýraznění textu. Není použita dědičnost. Pouze ke čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Vrací vlastnosti LineFormat použité k obrysování podtržité čáry. Není použita dědičnost. Pouze ke čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Vrací vlastnosti FillFormat podtržité čáry. Není použita dědičnost. Pouze ke čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Určuje, zda je písmo tučné. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Určuje, zda je písmo tučné. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Určuje, zda je písmo kurzívní. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Určuje, zda je písmo kurzívní. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Určuje, zda čísla mají ignorovat specifické svislé rozložení textu pro východní jazyky. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Určuje, zda čísla mají ignorovat specifické svislé rozložení textu pro východní jazyky. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Určuje, zda výška textu má být normalizována. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Určuje, zda výška textu má být normalizována. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Určuje, zda by text neměl být kontrolován. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Určuje, zda by text neměl být kontrolován. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Vrací nebo nastavuje typ podtržení textu. Není použita dědičnost. Čtení/zápis [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Vrací:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Vrací nebo nastavuje typ podtržení textu. Není použita dědičnost. Čtení/zápis [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Vrací nebo nastavuje typ kapitalizace textu. Není použita dědičnost. Čtení/zápis [TextCapType](../../com.aspose.slides/textcaptype).

**Vrací:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Vrací nebo nastavuje typ kapitalizace textu. Není použita dědičnost. Čtení/zápis [TextCapType](../../com.aspose.slides/textcaptype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Vrací nebo nastavuje typ přeškrtnutí textu. Není použita dědičnost. Čtení/zápis [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Vrací:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Vrací nebo nastavuje typ přeškrtnutí textu. Není použita dědičnost. Čtení/zápis [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Určuje, zda styl podtržení má vlastní vlastnosti LineFormat nebo je dědí z vlastností LineFormat textu. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Určuje, zda styl podtržení má vlastní vlastnosti LineFormat nebo je dědí z vlastností LineFormat textu. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Určuje, zda styl podtržení má vlastní vlastnosti FillFormat nebo je dědí z vlastností FillFormat textu. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Určuje, zda styl podtržení má vlastní vlastnosti FillFormat nebo je dědí z vlastností FillFormat textu. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Vrací nebo nastavuje výšku písma části. **Float.NaN** znamená, že výška není definována a měla by být zděděna z Masteru. Čtení/zápis float.

**Vrací:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Vrací nebo nastavuje výšku písma části. **Float.NaN** znamená, že výška není definována a měla by být zděděna z Masteru. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Vrací nebo nastavuje informace o latinském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Vrací nebo nastavuje informace o latinském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Vrací nebo nastavuje informace o východoasijském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Vrací nebo nastavuje informace o východoasijském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Vrací nebo nastavuje informace o písmu pro komplexní skripty. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Vrací nebo nastavuje informace o písmu pro komplexní skripty. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Vrací nebo nastavuje informace o symbolickém písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Vrací nebo nastavuje informace o symbolickém písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Vrací nebo nastavuje text v superskriptu nebo subskriptu. Hodnota od -100 % (subskript) do 100 % (superskript). **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis float.

**Vrací:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Vrací nebo nastavuje text v superskriptu nebo subskriptu. Hodnota od -100 % (subskript) do 100 % (superskript). **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Vrací nebo nastavuje minimální velikost písma, pro kterou se má zapnout kerning. **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis float.

**Vrací:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Vrací nebo nastavuje minimální velikost písma, pro kterou se má zapnout kerning. **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Vrací nebo nastavuje ID jazykové kontroly. Používá se při kontrole pravopisu a gramatiky. Čtení/zápis String.

**Vrací:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Vrací nebo nastavuje ID jazykové kontroly. Používá se při kontrole pravopisu a gramatiky. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Vrací nebo nastavuje ID alternativního jazyka. Čtení/zápis String.

**Vrací:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Vrací nebo nastavuje ID alternativního jazyka. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Vrací nebo nastavuje přírůstek mezery mezi znaky. **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis float.

**Vrací:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Vrací nebo nastavuje přírůstek mezery mezi znaky. **Float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Získá nebo nastaví hodnotu, která určuje, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové elementy je potlačena. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je false.

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
public abstract void setSpellCheck(boolean value)
```

Získá nebo nastaví hodnotu, která určuje, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové elementy je potlačena. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je false.

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