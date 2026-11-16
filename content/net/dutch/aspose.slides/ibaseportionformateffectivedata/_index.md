---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes voor .NET API-referentie
description: Basisinterface voor onmutabele objecten die effectieve tekstdelige-opmaak-eigenschappen bevatten.
type: docs
weight: 5340
url: /nl/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData interface

Basis-interface voor onmutabele objecten die effectieve opmaak-eigenschappen van tekstdelen bevatten.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Retourneert de Id van een alternatieve taal. Alleen-lezen String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Retourneert de complexe script-lettertype-info. Alleen-lezen [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Retourneert de Oost-Azia-lettertype-info. Alleen-lezen [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Retourneert de tekst EffectFormat-eigenschappen. Alleen-lezen [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Retourneert de superscript- of subscript-tekst. Waarde van -100 % (subscript) tot 100 % (superscript). Alleen-lezen Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Retourneert de tekst FillFormat-eigenschappen. Alleen-lezen [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Bepaalt of het lettertype vet is. Alleen-lezen Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Retourneert de lettertype-hoogte van het tekstddeel, in points. Alleen-lezen Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Bepaalt of het lettertype cursief is. Alleen-lezen Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Retourneert het onderstreptype van de tekst. Alleen-lezen [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Retourneert de kleur die wordt gebruikt om een tekst te markeren. Alleen-lezen Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Bepaalt of de onderstreepr stijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Alleen-lezen Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Bepaalt of de onderstreepr stijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Alleen-lezen Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Retourneert de minimale lettergrootte waarvoor kerning moet worden ingeschakeld. Alleen-lezen Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Bepaalt of de cijfers de oosterse, taal-specifieke verticale tekstopmaak van de tekst moeten negeren. Alleen-lezen Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Retourneert de Id van een taal. Alleen-lezen String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Retourneert de Latijnse lettertype-info. Alleen-lezen [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Retourneert de LineFormat-eigenschappen voor tekstoplijning. Alleen-lezen [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Alleen-lezen Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Bepaalt of de tekst niet gecontroleerd mag worden. Alleen-lezen Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Bepaalt of de smart-tag moet worden opgeschoond. Alleen-lezen Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Retourneert de tussen-karakter-spatiërings-toename, in points. Alleen-lezen Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Retourneert het doorhalings-type van een tekst. Alleen-lezen [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Retourneert de symbolische lettertype-info. Alleen-lezen [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Retourneert het type hoofdlettergebruik van de tekst. Alleen-lezen [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Retourneert de FillFormat-eigenschappen van de onderstreeplijn. Alleen-lezen [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstreeplijn te omlijnen. Alleen-lezen [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Zie ook

* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->