---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes pro .NET – referenční příručka API
description: Základní rozhraní pro neměnné objekty, které obsahují efektivní vlastnosti formátování textových částí.
type: docs
weight: 5320
url: /cs/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData interface

Základní rozhraní pro neměnné objekty, které obsahují efektivní vlastnosti formátování textových částí.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Vrací Id alternativního jazyka. Jen pro čtení String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Vrací informace o fontu komplexního skriptu. Jen pro čtení [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Vrací informace o fontu východní Asie. Jen pro čtení [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Vrací vlastnosti textu EffectFormat. Jen pro čtení [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Vrací text v podobě horního nebo dolního indexu. Hodnota od -100 % (dolní index) do 100 % (horní index). Jen pro čtení Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Vrací vlastnosti textu FillFormat. Jen pro čtení [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Určuje, zda je písmo tučné. Jen pro čtení Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Vrací výšku písma textové části v bodech. Jen pro čtení Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Určuje, zda je písmo kurzíva. Jen pro čtení Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Vrací typ podtržení textu. Jen pro čtení [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Vrací barvu použité k zvýraznění textu. Jen pro čtení Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo jej dědí z vlastností FillFormat textu. Jen pro čtení Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo jej dědí z vlastností LineFormat textu. Jen pro čtení Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Vrací minimální velikost písma, pro kterou má být zapnutý kerning. Jen pro čtení Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Určuje, zda mají čísla ignorovat specifické svislé rozložení textu východních jazyků. Jen pro čtení Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Vrací Id jazyka. Jen pro čtení String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Vrací informace o fontu latině. Jen pro čtení [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Vrací vlastnosti LineFormat pro obrysování textu. Jen pro čtení [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Určuje, zda výšku textu normalizovat. Jen pro čtení Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Určuje, zda by text neměl být kontrolován. Jen pro čtení Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Určuje, zda má být inteligentní značka vyčištěna. Jen pro čtení Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Vrací přírůstek mezery mezi znaky v bodech. Jen pro čtení Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Vrací typ přeškrtnutí textu. Jen pro čtení [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Vrací informace o symbolickém fontu. Jen pro čtení [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Vrací typ kapitálkování textu. Jen pro čtení [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Vrací vlastnosti FillFormat podtržité čáry. Jen pro čtení [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Vrací vlastnosti LineFormat použité k obrysování podtržité čáry. Jen pro čtení [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Viz také

* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- NEUPRAVUJTE: vygenerováno nástrojem xmldocmd pro Aspose.Slides.dll -->