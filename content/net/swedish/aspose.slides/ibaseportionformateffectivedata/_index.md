---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes för .NET API-referens
description: Basgränssnitt för oföränderliga objekt som innehåller faktiska formateringsegenskaper för textdelar.
type: docs
weight: 5320
url: /sv/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData gränssnitt

Basgränssnitt för oföränderliga objekt som innehåller faktiska formateringsfunktioner för textdelar.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Returnerar Id för ett alternativt språk. Skrivskyddad String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Returnerar information om komplex skript-font. Skrivskyddad [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Returnerar information om östasiatiskt font. Skrivskyddad [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Returnerar textens EffectFormat-egenskaper. Skrivskyddad [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Returnerar upphöjd eller nedsänkt text. Värde från -100 % (nedsänkt) till 100 % (upphöjd). Skrivskyddad Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Returnerar textens FillFormat-egenskaper. Skrivskyddad [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Avgör om teckensnittet är fetstilat. Skrivskyddad Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Returnerar teckenhöjden för textdelen, i punkter. Skrivskyddad Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Avgör om teckensnittet är kursivt. Skrivskyddad Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Returnerar textens understrykningstyp. Skrivskyddad [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Returnerar färgen som används för att markera text. Skrivskyddad Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Avgör om understrykningsstilen har egna FillFormat-egenskaper eller ärver dem från textens FillFormat. Skrivskyddad Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Avgör om understrykningsstilen har egna LineFormat-egenskaper eller ärver dem från textens LineFormat. Skrivskyddad Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Returnerar minimal teckenstorlek för vilken kerning ska aktiveras. Skrivskyddad Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Avgör om siffror ska ignorera den östasiatiska språk-specifika vertikala textlayouten. Skrivskyddad Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Returnerar Id för ett språk. Skrivskyddad String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Returnerar information om latinfont. Skrivskyddad [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Returnerar LineFormat-egenskaper för textkontur. Skrivskyddad [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Avgör om textens höjd ska normaliseras. Skrivskyddad Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Avgör om texten inte ska rättas. Skrivskyddad Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Avgör om smart-taggen ska rensas. Skrivskyddad Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Returnerar teckenavståndsincrement, i punkter. Skrivskyddad Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Returnerar igenomslagstyp för text. Skrivskyddad [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Returnerar symbolisk fontinformation. Skrivskyddad [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Returnerar typ av textkapitalisering. Skrivskyddad [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Returnerar FillFormat-egenskaper för understrykningslinjen. Skrivskyddad [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Returnerar LineFormat-egenskaper som används för att konturera understrykningslinjen. Skrivskyddad [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Se också

* namnrymd [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->