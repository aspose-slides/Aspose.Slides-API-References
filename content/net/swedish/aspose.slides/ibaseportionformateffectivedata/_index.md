---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes för .NET API-referens
description: Basgränssnitt för oföränderliga objekt som innehåller effektiva formateringsegenskaper för textdelar.
type: docs
weight: 5300
url: /sv/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData gränssnitt

Basgränssnitt för oföränderliga objekt som innehåller effektiva formateringsegenskaper för textdelar.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Returnerar Id:t för ett alternativt språk. Skrivskyddad String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Returnerar information om teckensnitt för komplexa skript. Skrivskyddad [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Returnerar information om teckensnitt för östasiatiska språk. Skrivskyddad [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Returnerar egenskaper för textens EffectFormat. Skrivskyddad [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Returnerar text som är upphöjd eller nedsänkt. Värde från -100% (nedsänkt) till 100% (upphöjd). Skrivskyddad Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Returnerar egenskaper för textens FillFormat. Skrivskyddad [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Avgör om teckensnittet är fetstil. Skrivskyddad Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Returnerar teckensnittshöjden för textdelen, i punkter. Skrivskyddad Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Avgör om teckensnittet är kursivt. Skrivskyddad Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Returnerar typ av understrykning för texten. Skrivskyddad [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Returnerar färgen som används för att markera en text. Skrivskyddad Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Avgör om understrykningens stil har egna FillFormat-egenskaper eller ärver dem från textens FillFormat-egenskaper. Skrivskyddad Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Avgör om understrykningens stil har egna LineFormat-egenskaper eller ärver dem från textens LineFormat-egenskaper. Skrivskyddad Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Returnerar minsta teckensnittsstorlek för vilken kerning ska aktiveras. Skrivskyddad Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Avgör om siffrorna ska ignorera östligt språk-specifik vertikal textlayout. Skrivskyddad Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Returnerar Id:t för ett språk. Skrivskyddad String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Returnerar information om latinskt teckensnitt. Skrivskyddad [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Returnerar LineFormat-egenskaper för textkontur. Skrivskyddad [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Avgör om höjden på en text ska normaliseras. Skrivskyddad Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Avgör om texten inte ska korrekturläsas. Skrivskyddad Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Avgör om smart-taggen ska rensas. Skrivskyddad Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Returnerar ökningen av teckenavstånd, i punkter. Skrivskyddad Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Returnerar genomstrykningstyp för en text. Skrivskyddad [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Returnerar information om symbolteckensnitt. Skrivskyddad [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Returnerar typ av textversalering. Skrivskyddad [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Returnerar FillFormat-egenskaper för understrykningens linje. Skrivskyddad [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Returnerar LineFormat-egenskaper som används för att konturera understrykningens linje. Skrivskyddad [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Se också

* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->