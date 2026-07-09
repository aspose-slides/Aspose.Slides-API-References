---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes voor .NET API-referentie
description: Basisinterface voor onveranderlijke objecten die effectieve tekstgedeelte-opmaak-eigenschappen bevatten.
type: docs
weight: 5320
url: /nl/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData interface

Basisinterface voor onveranderlijke objecten die effectieve tekstgedeelte-opmaak-eigenschappen bevatten.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Retourneert de Id van een alternatieve taal. Alleen-lezen String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Retourneert de complexe scriptlettertype-informatie. Alleen-lezen [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Retourneert de Oost-Aziatische lettertype-informatie. Alleen-lezen [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Retourneert de tekst EffectFormat-eigenschappen. Alleen-lezen [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Retourneert de superscript- of subscript-tekst. Waarde van -100% (subscript) tot 100% (superscript). Alleen-lezen Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Retourneert de tekst FillFormat-eigenschappen. Alleen-lezen [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Bepaalt of het lettertype vetgedrukt is. Alleen-lezen Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Retourneert de lettertypehoogte van het tekstgedeelte, in punten. Alleen-lezen Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Bepaalt of het lettertype cursief is. Alleen-lezen Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Retourneert het onderlijntype van de tekst. Alleen-lezen [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Retourneert de kleur die wordt gebruikt om tekst te markeren. Alleen-lezen Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Bepaalt of de onderstreeplijnstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Alleen-lezen Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Bepaalt of de onderstreeplijnstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Alleen-lezen Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Retourneert de minimale lettergrootte waarvoor kerning moet worden ingeschakeld. Alleen-lezen Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Bepaalt of de cijfers de oosterse taalspecifieke verticale tekstlay-out moeten negeren. Alleen-lezen Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Retourneert de Id van een taal. Alleen-lezen String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Retourneert de Latijnse lettertype-informatie. Alleen-lezen [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Retourneert de LineFormat-eigenschappen voor tekstomlijning. Alleen-lezen [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Bepaalt of de hoogte van een tekst moet worden genormaliseerd. Alleen-lezen Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Bepaalt of de tekst niet moet worden gecontroleerd. Alleen-lezen Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Bepaalt of de smart tag moet worden opgeschoond. Alleen-lezen Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Retourneert de interkarakterafstandstoevoeging, in punten. Alleen-lezen Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Retourneert het doorhalings-type van een tekst. Alleen-lezen [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Retourneert de symbolische lettertype-informatie. Alleen-lezen [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Retourneert het type hoofdlettergebruik van de tekst. Alleen-lezen [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Retourneert de onderlijntijlijn FillFormat-eigenschappen. Alleen-lezen [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderlijntijlijn te omlijnen. Alleen-lezen [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Zie ook

* naamruimte [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->