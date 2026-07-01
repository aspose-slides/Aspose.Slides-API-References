---
title: ChartPortionFormat
second_title: Aspose.Sildes pro .NET – reference API
description: Tato třída obsahuje vlastnosti formátování částí grafu používané v grafech. Na rozdíl od IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 1410
url: /cs/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat třída

Tato třída obsahuje vlastnosti formátování částí grafu používané v grafech. Na rozdíl od [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Vlastnosti

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Vrací nebo nastavuje Id alternativního jazyka. Číst/Zapisovat String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze ke čtení [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Vrací nebo nastavuje informace o písmu komplexního skriptu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Číst/Zapisovat [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Vrací nebo nastavuje informace o písmu pro východoasijské jazyky. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Číst/Zapisovat [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Vrací vlastnosti EffectFormat textu. Není použito dědění. Pouze ke čtení [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Vrací nebo nastavuje text jako horní nebo dolní index. Hodnota od -100 % (dolní index) do 100 % (horní index). **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Číst/Zapisovat Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Vrací vlastnosti FillFormat textu. Není použito dědění. Pouze ke čtení [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Určuje, zda je písmo tučné. Není použito dědění. Číst/Zapisovat [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Vrací nebo nastavuje výšku písma části. **float.NaN** znamená, že výška není definována a měla by být zděděna z Masteru. Číst/Zapisovat Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Určuje, zda je písmo kurzíva. Není použito dědění. Číst/Zapisovat [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Vrací nebo nastavuje typ podtržení textu. Není použito dědění. Číst/Zapisovat [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Vrací barvu použité pro zvýraznění textu. Není použito dědění. Pouze ke čtení [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo je zděděn z vlastností FillFormat textu. Číst/Zapisovat [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo je zděděn z vlastností LineFormat textu. Číst/Zapisovat [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Vrací nebo nastavuje minimální velikost písma, pro kterou má být zapnuto kerning. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Číst/Zapisovat Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Určuje, zda by čísla měla ignorovat specifické svislé rozložení textu pro východoasijské jazyky. Není použito dědění. Číst/Zapisovat [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Vrací nebo nastavuje Id jazyka pro kontrolu pravopisu. Používá se pro kontrolu pravopisu a gramatiky. Číst/Zapisovat String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Vrací nebo nastavuje informace o latiném písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Číst/Zapisovat [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Vrací vlastnosti LineFormat pro obrysování textu. Není použito dědění. Pouze ke čtení [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Určuje, zda má být výška textu normalizována. Není použito dědění. Číst/Zapisovat [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Určuje, zda text nemá být kontrolován. Není použito dědění. Číst/Zapisovat [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Vrací nebo nastavuje přírůstek mezery mezi znaky. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Číst/Zapisovat Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Získává nebo nastavuje hodnotu určující, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové prvky je potlačena. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Vrací nebo nastavuje typ přeškrtnutí textu. Není použito dědění. Číst/Zapisovat [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Vrací nebo nastavuje informace o symbolickém písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Číst/Zapisovat [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Vrací nebo nastavuje typ kapitalizace textu. Není použito dědění. Číst/Zapisovat [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Vrací vlastnosti FillFormat podtržené čáry. Není použito dědění. Pouze ke čtení [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Vrací vlastnosti LineFormat použité k obrysování podtržené čáry. Není použito dědění. Pouze ke čtení [`ILineFormat`](../../aspose.slides/ilineformat). |

## Metody

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porovnává s daným objektem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Vrací hash kód. |

### Poznámky

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování části textu definovanými pro konkrétní část. To znamená, že při získávání hodnot není použito dědění, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Chcete-li získat skutečné hodnoty parametrů formátování včetně zděděných, musíte použít metodu [`GetEffective`](../../aspose.slides/portionformat/geteffective), která vrací instanci [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### Viz také

* třída [BasePortionFormat](../../aspose.slides/baseportionformat)
* rozhraní [IChartPortionFormat](../ichartportionformat)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->