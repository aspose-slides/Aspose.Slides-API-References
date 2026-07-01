---
title: IBasePortionFormat
second_title: Aspose.Slides pro .NET API Reference
description: Tato třída obsahuje vlastnosti formátování textových částí. Na rozdíl od IPortionFormatEffectiveData./iportionformateffectivedata jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 5290
url: /cs/aspose.slides/ibaseportionformat/
---
## Rozhraní IBasePortionFormat

Tato třída obsahuje vlastnosti formátování textových částí. Na rozdíl od [`IPortionFormatEffectiveData`](../iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

```csharp
public interface IBasePortionFormat
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Vrací nebo nastavuje Id alternativního jazyka. Čtení/zápis String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Vrací nebo nastavuje informace o písmu pro složité skripty. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Vrací nebo nastavuje informace o písmu východoasijských jazyků. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Vrací vlastnosti textu EffectFormat. Dědictví se neuplatňuje. Pouze pro čtení [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Vrací nebo nastavuje text v horním nebo dolním indexu. Hodnota od -100 % (dolní index) do 100 % (horní index). **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Vrací vlastnosti textu FillFormat. Dědictví se neuplatňuje. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Určuje, zda je písmo tučné. Dědictví se neuplatňuje. Čtení/zápis [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Vrací nebo nastavuje výšku písma části. **float.NaN** znamená, že výška není definována a měla by být zděděna z Masteru. Čtení/zápis Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Určuje, zda je písmo kurzívou. Dědictví se neuplatňuje. Čtení/zápis [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Vrací nebo nastavuje typ podtržení textu. Dědictví se neuplatňuje. Čtení/zápis [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Vrací barvu použitou pro zvýraznění textu. Dědictví se neuplatňuje. Pouze pro čtení [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Určuje, zda styl podtržení má vlastní vlastnosti FillFormat nebo je zděděn z vlastností FillFormat textu. Čtení/zápis [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Určuje, zda styl podtržení má vlastní vlastnosti LineFormat nebo je zděděn z vlastností LineFormat textu. Čtení/zápis [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Vrací nebo nastavuje minimální velikost písma, pro kterou se má zapnout kerning. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Určuje, zda čísla mají ignorovat specifické vertikální rozložení východoasijského jazyka v textu. Dědictví se neuplatňuje. Čtení/zápis [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Vrací nebo nastavuje Id jazykové kontroly. Používá se pro kontrolu pravopisu a gramatiky. Čtení/zápis String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Vrací nebo nastavuje informace o latinském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Vrací vlastnosti LineFormat pro obrysování textu. Dědictví se neuplatňuje. Pouze pro čtení [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Určuje, zda výška textu má být normalizována. Dědictví se neuplatňuje. Čtení/zápis [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Určuje, zda text nemá být kontrolován. Dědictví se neuplatňuje. Čtení/zápis [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Vrací nebo nastavuje přírůstek mezery mezi znaky. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Získá nebo nastaví hodnotu určující, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontroly pravopisu pro textové prvky jsou potlačeny. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Vrací nebo nastavuje typ přeškrtnutí textu. Dědictví se neuplatňuje. Čtení/zápis [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Vrací nebo nastavuje informace o symbolickém písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Vrací nebo nastavuje typ kapitálkování textu. Dědictví se neuplatňuje. Čtení/zápis [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Vrací vlastnosti FillFormat podtržené čáry. Dědictví se neuplatňuje. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Vrací vlastnosti LineFormat použité pro obrys podtržené čáry. Dědictví se neuplatňuje. Pouze pro čtení [`ILineFormat`](../ilineformat). |

### Poznámky

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování částí textu definovanými pro konkrétní část. To znamená, že při získávání hodnot se nedědí, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Pro získání efektivních hodnot parametrů formátování včetně zděděných je třeba použít metodu [`GetEffective`](../iportionformat/geteffective), která vrací instanci [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Viz také

* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->