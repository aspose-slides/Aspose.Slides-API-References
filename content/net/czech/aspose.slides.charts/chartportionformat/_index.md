---
title: ChartPortionFormat
second_title: Aspose.Sildes pro .NET - referenční příručka API
description: Tato třída obsahuje vlastnosti formátování částí grafu používané v grafech. Na rozdíl od IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 1440
url: /cs/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat třída

Tato třída obsahuje vlastnosti formátování částí grafu používané v grafech. Na rozdíl od [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Vrací nebo nastavuje Id alternativního jazyka. Čtení/zápis String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze pro čtení [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Vrací nebo nastavuje informace o fontu pro komplexní skript. Null znamená, že font není definován a měl by být zděděn z Masteru. Čtení/zápis [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Vrací nebo nastavuje informace o fontu pro Východní Asii. Null znamená, že font není definován a měl by být zděděn z Masteru. Čtení/zápis [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Vrací vlastnosti EffectFormat textu. Nedědí se. Pouze pro čtení [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Vrací nebo nastavuje text v horním nebo dolním indexu. Hodnota od -100% (dolní index) do 100% (horní index). **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Vrací vlastnosti FillFormat textu. Nedědí se. Pouze pro čtení [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Určuje, zda je font tučný. Nedědí se. Čtení/zápis [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Vrací nebo nastavuje výšku fontu části. **float.NaN** znamená, že výška není definována a měla by být zděděna z Masteru. Čtení/zápis Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Určuje, zda je font itallic. Nedědí se. Čtení/zápis [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Vrací nebo nastavuje typ podtržení textu. Nedědí se. Čtení/zápis [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Vrací barvu použitou pro zvýraznění textu. Nedědí se. Pouze pro čtení [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo je dědí z vlastností FillFormat textu. Čtení/zápis [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo je dědí z vlastností LineFormat textu. Čtení/zápis [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Vrací nebo nastavuje minimální velikost fontu, při které by mělo být zapnuto kerning. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Určuje, zda mají čísla ignorovat vertikální rozložení textu specifické pro východoasijské jazyky. Nedědí se. Čtení/zápis [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Vrací nebo nastavuje Id jazykové kontroly. Používá se pro kontrolu pravopisu a gramatiky. Čtení/zápis String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Vrací nebo nastavuje informace o latinském fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Čtení/zápis [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Vrací vlastnosti LineFormat pro obrysování textu. Nedědí se. Pouze pro čtení [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Určuje, zda by výška textu měla být normalizována. Nedědí se. Čtení/zápis [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Určuje, zda by text neměl být kontrolován. Nedědí se. Čtení/zápis [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Vrací nebo nastavuje přírůstek mezery mezi znaky. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Získá nebo nastaví hodnotu určující, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové prvky je potlačena. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Vrací nebo nastavuje typ přeškrtnutí textu. Nedědí se. Čtení/zápis [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Vrací nebo nastavuje informace o symbolickém fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Čtení/zápis [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Vrací nebo nastavuje typ kapitalizace textu. Nedědí se. Čtení/zápis [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Vrací vlastnosti FillFormat podtržité čáry. Nedědí se. Pouze pro čtení [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Vrací vlastnosti LineFormat použité k obrysování podtržité čáry. Nedědí se. Pouze pro čtení [`ILineFormat`](../../aspose.slides/ilineformat). |

## Metody

| Název | Popis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porovnává s určeným objektem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Vrací hash kód. |

### Poznámky

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování částí textu definovanými pro konkrétní část. To znamená, že při získávání hodnot se nedědí, takže ve většině případů získáte hodnoty označující „neurčeno“.

Pro získání efektivních hodnot parametrů formátování včetně děděných je nutné použít metodu [`GetEffective`](../../aspose.slides/portionformat/geteffective), která vrací instanci [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### Viz také

* třída [BasePortionFormat](../../aspose.slides/baseportionformat)
* rozhraní [IChartPortionFormat](../ichartportionformat)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->