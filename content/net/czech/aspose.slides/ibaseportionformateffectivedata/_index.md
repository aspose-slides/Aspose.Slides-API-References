---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes pro .NET API referenční příručka
description: Základní rozhraní pro neměnné objekty, které obsahují efektivní vlastnosti formátování textových částí.
type: docs
weight: 5340
url: /cs/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData rozhraní

Základní rozhraní pro neměnné objekty, které obsahují efektivní vlastnosti formátování textových částí.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Vrací Id alternativního jazyka. Pouze ke čtení String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Vrací informace o fontu komplexního skriptu. Pouze ke čtení [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Vrací informace o fontu východoasijského písma. Pouze ke čtení [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Vrací vlastnosti textu EffectFormat. Pouze ke čtení [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Vrací text ve formě horního nebo dolního indexu. Hodnota od –100 % (dolní index) do 100 % (horní index). Pouze ke čtení Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Vrací vlastnosti textu FillFormat. Pouze ke čtení [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Určuje, zda je písmo tučné. Pouze ke čtení Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Vrací výšku písma textové části v bodech. Pouze ke čtení Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Určuje, zda je písmo kurzívou. Pouze ke čtení Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Vrací typ podtržení textu. Pouze ke čtení [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Vrací barvu použitou pro zvýraznění textu. Pouze ke čtení Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo je zděděn z FillFormat textu. Pouze ke čtení Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo je zděděn z LineFormat textu. Pouze ke čtení Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Vrací minimální velikost písma, pro kterou má být zapnutý kerning. Pouze ke čtení Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Určuje, zda čísla mají ignorovat specifické vertikální uspořádání východoasijského textu. Pouze ke čtení Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Vrací Id jazyka. Pouze ke čtení String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Vrací informace o latinském fontu. Pouze ke čtení [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Vrací vlastnosti LineFormat pro obrysování textu. Pouze ke čtení [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Určuje, zda má být výška textu normalizována. Pouze ke čtení Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Určuje, zda text nemá být kontrolován pravopisem. Pouze ke čtení Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Určuje, zda má být chytrá značka vyčištěna. Pouze ke čtení Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Vrací přírůstek mezery mezi znaky v bodech. Pouze ke čtení Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Vrací typ přeškrtnutí textu. Pouze ke čtení [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Vrací informace o symbolickém fontu. Pouze ke čtení [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Vrací typ kapitalizace textu. Pouze ke čtení [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Vrací vlastnosti FillFormat podtržité čáry. Pouze ke čtení [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Vrací vlastnosti LineFormat použité pro obrysování podtržité čáry. Pouze ke čtení [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Viz také

* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->