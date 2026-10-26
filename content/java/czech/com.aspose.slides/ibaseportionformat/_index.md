---
title: IBasePortionFormat
second_title: Aspose.Slides for Java API Reference
description: Tato třída obsahuje vlastnosti formátování textového úseku.
type: docs
url: /cs/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Tato třída obsahuje vlastnosti formátování textového úseku. Na rozdíl od [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

--------------------

Tato třída se používá k načtení a manipulaci s vlastnostmi formátování textového úseku definovanými pro konkrétní úsek. To znamená, že při získávání hodnot se nepoužije žádné dědění, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Pro získání skutečných hodnot parametrů formátování včetně zděděných je třeba použít metodu [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective), která vrací instanci [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Metody

| Metoda | Popis |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Vrací vlastnosti LineFormat pro obrys textu. |
| [getFillFormat()](#getFillFormat--) | Vrací vlastnosti FillFormat textu. |
| [getEffectFormat()](#getEffectFormat--) | Vrací vlastnosti EffectFormat textu. |
| [getHighlightColor()](#getHighlightColor--) | Vrací barvu použité k zvýraznění textu. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Vrací vlastnosti LineFormat použité k obrysování podtržené čáry. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Vrací vlastnosti FillFormat podtržené čáry. |
| [getFontBold()](#getFontBold--) | Určuje, zda je písmo tučné. |
| [setFontBold(byte value)](#setFontBold-byte-) | Určuje, zda je písmo tučné. |
| [getFontItalic()](#getFontItalic--) | Určuje, zda je písmo kurzíva. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Určuje, zda je písmo kurzíva. |
| [getKumimoji()](#getKumimoji--) | Určuje, zda mají čísla ignorovat specifické svislé rozložení textu pro východní jazyky. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Určuje, zda mají čísla ignorovat specifické svislé rozložení textu pro východní jazyky. |
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
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo zda je zděděn z vlastností LineFormat textu. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo zda je zděděn z vlastností LineFormat textu. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo zda je zděděn z vlastností FillFormat textu. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo zda je zděděn z vlastností FillFormat textu. |
| [getFontHeight()](#getFontHeight--) | Vrací nebo nastavuje výšku písma úseku. |
| [setFontHeight(float value)](#setFontHeight-float-) | Vrací nebo nastavuje výšku písma úseku. |
| [getLatinFont()](#getLatinFont--) | Vrací nebo nastavuje informace o latinském fontu. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje informace o latinském fontu. |
| [getEastAsianFont()](#getEastAsianFont--) | Vrací nebo nastavuje informace o východoasijském fontu. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje informace o východoasijském fontu. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Vrací nebo nastavuje informace o fontu pro složité skripty. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje informace o fontu pro složité skripty. |
| [getSymbolFont()](#getSymbolFont--) | Vrací nebo nastavuje informace o symbolickém fontu. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje informace o symbolickém fontu. |
| [getEscapement()](#getEscapement--) | Vrací nebo nastavuje text jako horní nebo dolní index. |
| [setEscapement(float value)](#setEscapement-float-) | Vrací nebo nastavuje text jako horní nebo dolní index. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Vrací nebo nastavuje minimální velikost písma, při které by mělo být zapnuto kerning. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Vrací nebo nastavuje minimální velikost písma, při které by mělo být zapnuto kerning. |
| [getLanguageId()](#getLanguageId--) | Vrací nebo nastavuje Id jazykové kontroly. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Vrací nebo nastavuje Id jazykové kontroly. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Vrací nebo nastavuje Id alternativního jazyka. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Vrací nebo nastavuje Id alternativního jazyka. |
| [getSpacing()](#getSpacing--) | Vrací nebo nastavuje přírůstek mezery mezi znaky. |
| [setSpacing(float value)](#setSpacing-float-) | Vrací nebo nastavuje přírůstek mezery mezi znaky. |
| [getSpellCheck()](#getSpellCheck--) | Načte nebo nastaví hodnotu indikující, zda je pro úsek textu povoleno kontrola pravopisu. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Načte nebo nastaví hodnotu indikující, zda je pro úsek textu povoleno kontrola pravopisu. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Vrací vlastnosti LineFormat pro obrys textu. Nedědí se. **Pouze pro čtení** [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Vrací vlastnosti FillFormat textu. Nedědí se. **Pouze pro čtení** [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Vrací vlastnosti EffectFormat textu. Nedědí se. **Pouze pro čtení** [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Vrací:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Vrací barvu použité k zvýraznění textu. Nedědí se. **Pouze pro čtení** [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Vrací vlastnosti LineFormat použité k obrysování podtržené čáry. Nedědí se. **Pouze pro čtení** [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Vrací vlastnosti FillFormat podtržené čáry. Nedědí se. **Pouze pro čtení** [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Určuje, zda je písmo tučné. Nedědí se. **Čtení/Zápis** [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Určuje, zda je písmo tučné. Nedědí se. **Čtení/Zápis** [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Určuje, zda je písmo kurzíva. Nedědí se. **Čtení/Zápis** [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Určuje, zda je písmo kurzíva. Nedědí se. **Čtení/Zápis** [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Určuje, zda mají čísla ignorovat specifické svislé rozložení textu pro východní jazyky. Nedědí se. **Čtení/Zápis** [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Určuje, zda mají čísla ignorovat specifické svislé rozložení textu pro východní jazyky. Nedědí se. **Čtení/Zápis** [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Určuje, zda má být výška textu normalizována. Nedědí se. **Čtení/Zápis** [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Určuje, zda má být výška textu normalizována. Nedědí se. **Čtení/Zápis** [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Určuje, zda text nemá být kontrolován pravopisem. Nedědí se. **Čtení/Zápis** [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Určuje, zda text nemá být kontrolován pravopisem. Nedědí se. **Čtení/Zápis** [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Vrací nebo nastavuje typ podtržení textu. Nedědí se. **Čtení/Zápis** [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Vrací:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Vrací nebo nastavuje typ podtržení textu. Nedědí se. **Čtení/Zápis** [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Vrací nebo nastavuje typ kapitalizace textu. Nedědí se. **Čtení/Zápis** [TextCapType](../../com.aspose.slides/textcaptype).

**Vrací:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Vrací nebo nastavuje typ kapitalizace textu. Nedědí se. **Čtení/Zápis** [TextCapType](../../com.aspose.slides/textcaptype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Vrací nebo nastavuje typ přeškrtnutí textu. Nedědí se. **Čtení/Zápis** [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Vrací:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Vrací nebo nastavuje typ přeškrtnutí textu. Nedědí se. **Čtení/Zápis** [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo zda je zděděn z vlastností LineFormat textu. **Čtení/Zápis** [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo zda je zděděn z vlastností LineFormat textu. **Čtení/Zápis** [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo zda je zděděn z vlastností FillFormat textu. **Čtení/Zápis** [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo zda je zděděn z vlastností FillFormat textu. **Čtení/Zápis** [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Vrací nebo nastavuje výšku písma úseku. **Float.NaN** znamená, že výška je nedefinována a měla by být zděděna z Masteru. **Čtení/Zápis** float.

**Vrací:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Vrací nebo nastavuje výšku písma úseku. **Float.NaN** znamená, že výška je nedefinována a měla by být zděděna z Masteru. **Čtení/Zápis** float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Vrací nebo nastavuje informace o latinském fontu. Null znamená, že font je nedefinován a měl by být zděděn z Masteru. **Čtení/Zápis** [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Vrací nebo nastavuje informace o latinském fontu. Null znamená, že font je nedefinován a měl by být zděděn z Masteru. **Čtení/Zápis** [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Vrací nebo nastavuje informace o východoasijském fontu. Null znamená, že font je nedefinován a měl by být zděděn z Masteru. **Čtení/Zápis** [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Vrací nebo nastavuje informace o východoasijském fontu. Null znamená, že font je nedefinován a měl by být zděděn z Masteru. **Čtení/Zápis** [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Vrací nebo nastavuje informace o fontu pro složité skripty. Null znamená, že font je nedefinován a měl by být zděděn z Masteru. **Čtení/Zápis** [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Vrací nebo nastavuje informace o fontu pro složité skripty. Null znamená, že font je nedefinován a měl by být zděděn z Masteru. **Čtení/Zápis** [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Vrací nebo nastavuje informace o symbolickém fontu. Null znamená, že font je nedefinován a měl by být zděděn z Masteru. **Čtení/Zápis** [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Vrací nebo nastavuje informace o symbolickém fontu. Null znamená, že font je nedefinován a měl by být zděděn z Masteru. **Čtení/Zápis** [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Vrací nebo nastavuje text jako horní nebo dolní index. Hodnota od -100 % (dolní index) do 100 % (horní index). **Float.NaN** znamená, že hodnota je nedefinována a měla by být zděděna z Masteru. **Čtení/Zápis** float.

**Vrací:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Vrací nebo nastavuje text jako horní nebo dolní index. Hodnota od -100 % (dolní index) do 100 % (horní index). **Float.NaN** znamená, že hodnota je nedefinována a měla by být zděděna z Masteru. **Čtení/Zápis** float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Vrací nebo nastavuje minimální velikost písma, při které by mělo být zapnuto kerning. **Float.NaN** znamená, že hodnota je nedefinována a měla by být zděděna z Masteru. **Čtení/Zápis** float.

**Vrací:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Vrací nebo nastavuje minimální velikost písma, při které by mělo být zapnuto kerning. **Float.NaN** znamená, že hodnota je nedefinována a měla by být zděděna z Masteru. **Čtení/Zápis** float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Vrací nebo nastavuje Id jazykové kontroly. Používá se pro kontrolu pravopisu a gramatiky. **Čtení/Zápis** String.

**Vrací:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Vrací nebo nastavuje Id jazykové kontroly. Používá se pro kontrolu pravopisu a gramatiky. **Čtení/Zápis** String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Vrací nebo nastavuje Id alternativního jazyka. **Čtení/Zápis** String.

**Vrací:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Vrací nebo nastavuje Id alternativního jazyka. **Čtení/Zápis** String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Vrací nebo nastavuje přírůstek mezery mezi znaky. **Float.NaN** znamená, že hodnota je nedefinována a měla by být zděděna z Masteru. **Čtení/Zápis** float.

**Vrací:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Vrací nebo nastavuje přírůstek mezery mezi znaky. **Float.NaN** znamená, že hodnota je nedefinována a měla by být zděděna z Masteru. **Čtení/Zápis** float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Načte nebo nastaví hodnotu indikující, zda je pro úsek textu povoleno kontrola pravopisu. Když je tato vlastnost nastavena na false, kontroly pravopisu pro textové elementy jsou potlačeny. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Přístup k prvnímu úseku textu uvnitř prvního tvaru na první snímku
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Povolit kontrolu pravopisu pro tento úsek textu
>      portion.getPortionFormat().setSpellCheck(true);
>      // Uložit upravenou prezentaci
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

Načte nebo nastaví hodnotu indikující, zda je pro úsek textu povoleno kontrola pravopisu. Když je tato vlastnost nastavena na false, kontroly pravopisu pro textové elementy jsou potlačeny. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Přístup k prvnímu úseku textu uvnitř prvního tvaru na první snímku
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Povolit kontrolu pravopisu pro tento úsek textu
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