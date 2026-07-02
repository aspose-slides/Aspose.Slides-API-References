---
title: IBasePortionFormat
second_title: Aspose.Slides voor .NET API-referentie
description: Deze klasse bevat de opmaak-eigenschappen van tekstgedeelten. In tegenstelling tot IPortionFormatEffectiveData./iportionformateffectivedata zijn alle eigenschappen van deze klasse schrijfbaar.
type: docs
weight: 5310
url: /nl/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat interface

This class contains the text portion formatting properties. Unlike [`IPortionFormatEffectiveData`](../iportionformateffectivedata), all properties of this class are writeable.

```csharp
public interface IBasePortionFormat
```

## Eigenschappen

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Geeft de Id van een alternatieve taal terug of stelt deze in. Lezen/Schrijven String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Geeft de informatie over het complexe scriptlettertype terug of stelt deze in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/Schrijven [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Geeft de Oost-Aziatische lettertype-informatie terug of stelt deze in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/Schrijven [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Geeft de EffectFormat-eigenschappen van de tekst terug. Er wordt geen overerving toegepast. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Geeft de superscript- of subscript-tekst terug of stelt deze in. Waarde van -100% (subscript) tot 100% (superscript). **float.NaN** betekent dat de waarde niet is gedefinieerd en moet worden geërfd van de Master. Lezen/Schrijven Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Geeft de FillFormat-eigenschappen van de tekst terug. Er wordt geen overerving toegepast. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Bepaalt of het lettertype vet is. Er wordt geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Geeft de letterhoogte van een deel terug of stelt deze in. **float.NaN** betekent dat de hoogte niet is gedefinieerd en moet worden geërfd van de Master. Lezen/Schrijven Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Bepaalt of het lettertype cursief is. Er wordt geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Geeft het onderlijntype van de tekst terug of stelt dit in. Er wordt geen overerving toegepast. Lezen/Schrijven [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Geeft de kleur die wordt gebruikt om tekst te markeren terug. Er wordt geen overerving toegepast. Alleen-lezen [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Bepaalt of de onderstreeleigenschap eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Bepaalt of de onderstreeleigenschap eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Geeft de minimale lettergrootte terug of stelt deze in, waarvoor kerning moet worden ingeschakeld. **float.NaN** betekent dat de waarde niet is gedefinieerd en moet worden geërfd van de Master. Lezen/Schrijven Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Bepaalt of de cijfers de oosterse taal-specifieke verticale lay-out van de tekst moeten negeren. Er wordt geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Geeft de Id van een proefleessaal terug of stelt deze in. Wordt gebruikt voor spelling- en grammaticacontrole. Lezen/Schrijven String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Geeft de informatie over het Latijnse lettertype terug of stelt deze in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/Schrijven [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Geeft de LineFormat-eigenschappen voor tekstomlijning terug. Er wordt geen overerving toegepast. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Er wordt geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Bepaalt of de tekst niet gecontroleerd mag worden. Er wordt geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Geeft de toename van de inter-karakter-afstand terug of stelt deze in. **float.NaN** betekent dat de waarde niet is gedefinieerd en moet worden geërfd van de Master. Lezen/Schrijven Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of spellingscontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap op false is ingesteld, worden spellingscontroles voor tekstelementen onderdrukt. Wanneer op true ingesteld, is spellingscontrole toegestaan. Standaardwaarde is `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Geeft het doorhalingstype van een tekst terug of stelt dit in. Er wordt geen overerving toegepast. Lezen/Schrijven [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Geeft de symbolische lettertype-informatie terug of stelt deze in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/Schrijven [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Geeft het type hoofdlettergebruik van de tekst terug of stelt dit in. Er wordt geen overerving toegepast. Lezen/Schrijven [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Geeft de FillFormat-eigenschappen van de onderstreeplijn terug. Er wordt geen overerving toegepast. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Geeft de LineFormat-eigenschappen die worden gebruikt om de onderstreeplijn te omlijnen terug. Er wordt geen overerving toegepast. Alleen-lezen [`ILineFormat`](../ilineformat). |

### Opmerkingen

Deze klasse wordt gebruikt om de opmaak-eigenschappen van een tekstgedeelte die voor dat specifieke gedeelte zijn gedefinieerd, op te halen en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, zodat u in de meeste gevallen waarden krijgt die ‘ongedefinieerd’ betekenen.

Om de effectieve waarden van de opmaak-parameters, inclusief geërfde, te verkrijgen, moet u de methode [`GetEffective`](../iportionformat/geteffective) gebruiken die een [`IPortionFormatEffectiveData`](../iportionformateffectivedata)-instantie retourneert.

### Zie ook

* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->