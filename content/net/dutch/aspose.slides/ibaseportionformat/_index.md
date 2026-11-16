---
title: IBasePortionFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Deze klasse bevat de tekstgedeelte-opmaakeigenschappen. In tegenstelling tot IPortionFormatEffectiveData./iportionformateffectivedata zijn alle eigenschappen van deze klasse schrijfbaar.
type: docs
weight: 5330
url: /nl/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat interface

Deze klasse bevat de tekstgedeelte-opmaakeigenschappen. In tegenstelling tot [`IPortionFormatEffectiveData`](../iportionformateffectivedata) zijn alle eigenschappen van deze klasse beschrijfbaar.

```csharp
public interface IBasePortionFormat
```

## Eigenschappen

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Retourneert of stelt de Id van een alternatieve taal in. Lezen/Schrijven String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Retourneert of stelt de complexe scriptlettertype-informatie in. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Retourneert of stelt de Oost-Aziatische lettertype-informatie in. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Retourneert de EffectFormat-eigenschappen van de tekst. Er wordt geen overerving toegepast. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Retourneert of stelt de superscript- of subscript-tekst in. Waarde van -100% (subscript) tot 100% (superscript). **float.NaN** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Retourneert de FillFormat-eigenschappen van de tekst. Er wordt geen overerving toegepast. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Bepaalt of het lettertype vet is. Er wordt geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Retourneert of stelt de letterhoogte van een gedeelte in. **float.NaN** betekent dat de hoogte ongedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Bepaalt of het lettertype cursief is. Er wordt geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Retourneert of stelt het onderstreeptype van de tekst in. Er wordt geen overerving toegepast. Lezen/Schrijven [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Retourneert de kleur die wordt gebruikt om een tekst te markeren. Er wordt geen overerving toegepast. Alleen-lezen [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Bepaalt of de onderstreefstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Bepaalt of de onderstreefstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Retourneert of stelt de minimale lettergrootte in waarbij kerning moet worden ingeschakeld. **float.NaN** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Bepaalt of de cijfers de oosterse, taalspecifieke verticale tekstindeling moeten negeren. Er wordt geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Retourneert of stelt de Id van een proefleestaal in. Wordt gebruikt voor spelling- en grammaticacontrole. Lezen/Schrijven String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Retourneert of stelt de Latijnse lettertype-informatie in. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Retourneert de LineFormat-eigenschappen voor tekstomlijning. Er wordt geen overerving toegepast. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Er wordt geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Bepaalt of de tekst niet proefgelezen mag worden. Er wordt geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Retourneert of stelt de interkarakter-spatiëringsstap in. **float.NaN** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Haalt of stelt een waarde in die aangeeft of spellingscontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap op false wordt gezet, worden spellingscontroles voor tekstelementen onderdrukt. Wanneer deze op true wordt gezet, is spellingscontrole toegestaan. Standaardwaarde is `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Retourneert of stelt het doorstrepingstype van een tekst in. Er wordt geen overerving toegepast. Lezen/Schrijven [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Retourneert of stelt de symbolische lettertype-informatie in. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Retourneert of stelt het type hoofdlettergebruik van de tekst in. Er wordt geen overerving toegepast. Lezen/Schrijven [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Retourneert de FillFormat-eigenschappen van de onderstreeplijn. Er wordt geen overerving toegepast. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstreeplijn te omlijnen. Er wordt geen overerving toegepast. Alleen-lezen [`ILineFormat`](../ilineformat). |

### Opmerkingen

Deze klasse wordt gebruikt om de opmaak-eigenschappen van tekstgedeelten die voor het specifieke gedeelte zijn gedefinieerd, op te halen en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, dus in de meeste gevallen krijg je waarden die “ongedefinieerd” betekenen.

Om de effectieve opmaak-parameterwaarden, inclusief geërfde waarden, te verkrijgen, moet je de [`GetEffective`](../iportionformat/geteffective)-methode gebruiken die een [`IPortionFormatEffectiveData`](../iportionformateffectivedata)-instantie retourneert.

### Zie ook

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->