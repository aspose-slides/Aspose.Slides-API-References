---
title: ChartPortionFormat
second_title: Aspose.Sildes pro .NET API reference
description: Tato třída obsahuje vlastnosti formátování částí grafu používané v grafech. Na rozdíl od IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 1430
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
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Vrací nebo nastavuje Id alternativního jazyka. Čtení/Zápis String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze pro čtení [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Vrací nebo nastavuje informace o typu písma pro složité skripty. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/Zápis [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Vrací nebo nastavuje informace o písmu pro východoasijské jazyky. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/Zápis [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Vrací vlastnosti EffectFormat textu. Není použito dědičnosti. Pouze pro čtení [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Vrací nebo nastavuje text horního nebo dolního indexu. Hodnota od -100 % (dolní index) do 100 % (horní index). **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/Zápis Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Vrací vlastnosti FillFormat textu. Není použito dědičnosti. Pouze pro čtení [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Určuje, zda je písmo tučné. Není použito dědičnosti. Čtení/Zápis [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Vrací nebo nastavuje výšku písma části. **float.NaN** znamená, že výška není definována a měla by být zděděna z Masteru. Čtení/Zápis Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Určuje, zda je písmo kurzíva. Není použito dědičnosti. Čtení/Zápis [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Vrací nebo nastavuje typ podtržení textu. Není použito dědičnosti. Čtení/Zápis [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Vrací barvu použité k zvýraznění textu. Není použito dědičnosti. Pouze pro čtení [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Určuje, jestli má styl podtržení vlastní vlastnosti FillFormat nebo je zděděn z vlastností FillFormat textu. Čtení/Zápis [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Určuje, jestli má styl podtržení vlastní vlastnosti LineFormat nebo je zděděn z vlastností LineFormat textu. Čtení/Zápis [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Vrací nebo nastavuje minimální velikost písma, pro kterou by mělo být zapnuto kerning. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/Zápis Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Určuje, zda čísla mají ignorovat specifické vertikální uspořádání textu pro východní jazyky. Není použito dědičnosti. Čtení/Zápis [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Vrací nebo nastavuje Id jazykové kontroly. Používá se pro kontrolu pravopisu a gramatiky. Čtení/Zápis String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Vrací nebo nastavuje informace o latinském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/Zápis [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Vrací vlastnosti LineFormat pro obrys textu. Není použito dědičnosti. Pouze pro čtení [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Určuje, zda má být výška textu normalizována. Není použito dědičnosti. Čtení/Zápis [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Určuje, zda text nemá být kontrolován. Není použito dědičnosti. Čtení/Zápis [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Vrací nebo nastavuje přírůstek mezery mezi znaky. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/Zápis Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Získává nebo nastavuje hodnotu určující, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontroly pravopisu pro textové prvky jsou potlačeny. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Vrací nebo nastavuje typ přeškrtnutí textu. Není použito dědičnosti. Čtení/Zápis [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Vrací nebo nastavuje informace o symbolickém písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/Zápis [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Vrací nebo nastavuje typ kapitalizace textu. Není použito dědičnosti. Čtení/Zápis [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Vrací vlastnosti FillFormat podtržené linky. Není použito dědičnosti. Pouze pro čtení [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Vrací vlastnosti LineFormat používané k obrysování podtržené linky. Není použito dědičnosti. Pouze pro čtení [`ILineFormat`](../../aspose.slides/ilineformat). |

## Metody

| Název | Popis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porovnává s určeným objektem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Vrací hash kód. |

### Poznámky

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování částí textu definovanými pro konkrétní část. To znamená, že při získávání hodnot není použita žádná dědičnost, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Chcete-li získat účinné hodnoty parametrů formátování včetně zděděných, musíte použít metodu [`GetEffective`](../../aspose.slides/portionformat/geteffective), která vrací instanci [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### Viz také

* třída [BasePortionFormat](../../aspose.slides/baseportionformat)
* rozhraní [IChartPortionFormat](../ichartportionformat)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->