---
title: BasePortionFormat
second_title: Aspose.Sildes pro .NET API Reference
description: Obecné vlastnosti formátování textových částí.
type: docs
weight: 950
url: /cs/aspose.slides/baseportionformat/
---
## BasePortionFormat třída

Obecné vlastnosti formátování textových částí.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Vrací nebo nastavuje Id alternativního jazyka. Čtení/zápis String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze pro čtení [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Vrací nebo nastavuje informace o písmu pro složité skripty. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Vrací nebo nastavuje informace o písmu pro východoasijské jazyky. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Vrací vlastnosti EffectFormat textu. Není použito dědičnosti. Pouze pro čtení [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Vrací nebo nastavuje text jako horní nebo dolní index. Hodnota v rozmezí -100 % (dolní index) až 100 % (horní index). **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Vrací vlastnosti FillFormat textu. Není použito dědičnosti. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Určuje, zda je písmo tučné. Není použito dědičnosti. Čtení/zápis [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Vrací nebo nastavuje výšku písma části. **float.NaN** znamená, že výška není definována a měla by být zděděna z Masteru. Čtení/zápis Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Určuje, zda je písmo kurzíva. Není použito dědičnosti. Čtení/zápis [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Vrací nebo nastavuje typ podtržení textu. Není použito dědičnosti. Čtení/zápis [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Vrací barvu použitou pro zvýraznění textu. Není použito dědičnosti. Pouze pro čtení [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti FillFormat, nebo je zděděn z vlastností FillFormat textu. Čtení/zápis [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti LineFormat, nebo je zděděn z vlastností LineFormat textu. Čtení/zápis [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Vrací nebo nastavuje minimální velikost písma, pro kterou má být zapnuta kerning. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Určuje, zda mají čísla ignorovat vertikální rozložení specifické pro východoasijské jazyky. Není použito dědičnosti. Čtení/zápis [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Vrací nebo nastavuje Id jazykové kontroly. Používá se pro kontrolu pravopisu a gramatiky. Čtení/zápis String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Vrací nebo nastavuje informace o latině písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Vrací vlastnosti LineFormat pro obrysování textu. Není použito dědičnosti. Pouze pro čtení [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Určuje, zda má být výška textu normalizována. Není použito dědičnosti. Čtení/zápis [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Určuje, zda text nemá být kontrolován. Není použito dědičnosti. Čtení/zápis [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Vrací nebo nastavuje přírůstek mezery mezi znaky. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Získá nebo nastaví hodnotu určující, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontroly pravopisu pro textové prvky jsou potlačeny. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Vrací nebo nastavuje typ přeškrtnutí textu. Není použito dědičnosti. Čtení/zápis [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Vrací nebo nastavuje informace o symbolickém písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Čtení/zápis [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Vrací nebo nastavuje typ kapitalizace textu. Není použito dědičnosti. Čtení/zápis [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Vrací vlastnosti FillFormat podtržité čáry. Není použito dědičnosti. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Vrací vlastnosti LineFormat použité k obrysování podtržité čáry. Není použito dědičnosti. Pouze pro čtení [`ILineFormat`](../ilineformat). |

## Metody

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porovnává se se zadaným objektem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Vrací hash kód. |

### Viz také

* třída [PVIObject](../pviobject)
* rozhraní [IBasePortionFormat](../ibaseportionformat)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->