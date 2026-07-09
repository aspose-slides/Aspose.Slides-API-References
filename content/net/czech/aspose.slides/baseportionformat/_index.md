---
title: BasePortionFormat
second_title: Aspose.Sildes pro .NET – referenční příručka API
description: Společné vlastnosti formátování textových částí.
type: docs
weight: 970
url: /cs/aspose.slides/baseportionformat/
---
## BasePortionFormat třída

Společné vlastnosti formátování textových částí.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Vrací nebo nastavuje Id alternativního jazyka. Čtení/zápis String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze pro čtení [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Vrací nebo nastavuje informace o fontu pro složité písmo. Null znamená, že font není definován a měl by být zděděn z Masteru. Čtení/zápis [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Vrací nebo nastavuje informace o fontu pro východoasijské písmo. Null znamená, že font není definován a měl by být zděděn z Masteru. Čtení/zápis [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Vrací vlastnosti EffectFormat textu. Dědění není použito. Pouze pro čtení [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Vrací nebo nastavuje text horního nebo dolního indexu. Hodnota od -100 % (dolní index) do 100 % (horní index). **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Vrací vlastnosti FillFormat textu. Dědění není použito. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Určuje, zda je font tučný. Dědění není použito. Čtení/zápis [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Vrací nebo nastavuje výšku fontu úseku. **float.NaN** znamená, že výška není definována a měla by být zděděna z Masteru. Čtení/zápis Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Určuje, zda je font kurzívou. Dědění není použito. Čtení/zápis [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Vrací nebo nastavuje typ podtržení textu. Dědění není použito. Čtení/zápis [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Vrací barvu použitou pro zvýraznění textu. Dědění není použito. Pouze pro čtení [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo je zdědí z vlastností FillFormat textu. Čtení/zápis [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo je zdědí z vlastností LineFormat textu. Čtení/zápis [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Vrací nebo nastavuje minimální velikost fontu, při které má být zapnutý kerning. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Určuje, zda čísla mají ignorovat specifické vertikální rozložení textu pro východoasijské jazyky. Dědění není použito. Čtení/zápis [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Vrací nebo nastavuje Id jazykové kontroly. Používá se pro kontrolu pravopisu a gramatiky. Čtení/zápis String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Vrací nebo nastavuje informace o latinském fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Čtení/zápis [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Vrací vlastnosti LineFormat pro obrys textu. Dědění není použito. Pouze pro čtení [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Určuje, zda má být výška textu normalizována. Dědění není použito. Čtení/zápis [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Určuje, zda by text neměl být kontrolován. Dědění není použito. Čtení/zápis [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Vrací nebo nastavuje přírůstek mezery mezi znaky. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/zápis Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Získává nebo nastavuje hodnotu určující, zda je pro úsek textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontroly pravopisu pro textové prvky jsou potlačeny. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Vrací nebo nastavuje typ přeškrtnutí textu. Dědění není použito. Čtení/zápis [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Vrací nebo nastavuje informace o symbolickém fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Čtení/zápis [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Vrací nebo nastavuje typ kapitalizace textu. Dědění není použito. Čtení/zápis [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Vrací vlastnosti FillFormat podtržené čáry. Dědění není použito. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Vrací vlastnosti LineFormat použité k obrysování podtržené čáry. Dědění není použito. Pouze pro čtení [`ILineFormat`](../ilineformat). |

## Metody

| Název | Popis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porovnává se zadaným objektem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Vrací hash kód. |

### Viz také

* třída [PVIObject](../pviobject)
* rozhraní [IBasePortionFormat](../ibaseportionformat)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->