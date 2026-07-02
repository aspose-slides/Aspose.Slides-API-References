---
title: ChartPortionFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Deze klasse bevat de opmaak-eigenschappen voor diagramonderdelen die in diagrammen worden gebruikt. In tegenstelling tot IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata zijn alle eigenschappen van deze klasse schrijfbaar.
type: docs
weight: 1430
url: /nl/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat klasse

Deze klasse bevat de formatteereigenschappen voor diagramonderdelen die in diagrammen worden gebruikt. In tegenstelling tot [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) zijn alle eigenschappen van deze klasse schrijfbaar.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Geeft of stelt de Id van een alternatieve taal in. Lezen/Schrijven String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Staat toe de basis IPresentationComponent-interface op te halen. Alleen-lezen [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Geeft of stelt de complexe script lettertype-informatie in. Null betekent dat het lettertype niet gedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Geeft of stelt de Oost-Aziatische lettertype-informatie in. Null betekent dat het lettertype niet gedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Geeft de EffectFormat-eigenschappen van de tekst terug. Er wordt geen overerving toegepast. Alleen-lezen [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Geeft of stelt de superscript- of subscript-tekst in. Waarde van -100% (subscript) tot 100% (superscript). **float.NaN** betekent dat de waarde niet gedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Geeft de FillFormat-eigenschappen van de tekst terug. Er wordt geen overerving toegepast. Alleen-lezen [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bepaalt of het lettertype vet is. Er wordt geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Geeft of stelt de lettertype-hoogte van een gedeelte in. **float.NaN** betekent dat de hoogte niet gedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bepaalt of het lettertype cursief is. Er wordt geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Geeft of stelt het onderstrepingtstype van de tekst in. Er wordt geen overerving toegepast. Lezen/Schrijven [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Geeft de kleur die wordt gebruikt om tekst te markeren terug. Er wordt geen overerving toegepast. Alleen-lezen [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bepaalt of de onderstrepingsstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Lezen/Schrijven [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bepaalt of de onderstrepingsstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Lezen/Schrijven [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Geeft of stelt de minimale lettergrootte in waarvoor kerning moet worden ingeschakeld. **float.NaN** betekent dat de waarde niet gedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bepaalt of de getallen de oosterse taalspecifieke verticale tekstlay-out van de tekst moeten negeren. Er wordt geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Geeft of stelt de Id van een proefleestaal in. Wordt gebruikt voor spelling- en grammaticacontrole. Lezen/Schrijven String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Geeft of stelt de Latijnse lettertype-informatie in. Null betekent dat het lettertype niet gedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Geeft de LineFormat-eigenschappen voor het omranden van tekst terug. Er wordt geen overerving toegepast. Alleen-lezen [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Er wordt geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bepaalt of de tekst niet moet worden proefgelezen. Er wordt geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Geeft of stelt de interkarakter-spatiëringsincrement in. **float.NaN** betekent dat de waarde niet gedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Haalt op of stelt een waarde in die aangeeft of spellingscontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap op false staat, worden spellingcontroles voor tekstelementen onderdrukt. Wanneer deze op true staat, is spellingscontrole toegestaan. Standaardwaarde is `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Geeft of stelt het doorhalings type van een tekst in. Er wordt geen overerving toegepast. Lezen/Schrijven [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Geeft of stelt de symbolische lettertype-informatie in. Null betekent dat het lettertype niet gedefinieerd is en moet worden geërfd van de Master. Lezen/Schrijven [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Geeft of stelt het type hoofdlettergebruik van de tekst in. Er wordt geen overerving toegepast. Lezen/Schrijven [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Geeft de FillFormat-eigenschappen van de onderstrepingslijn terug. Er wordt geen overerving toegepast. Alleen-lezen [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Geeft de LineFormat-eigenschappen die worden gebruikt om de onderstrepingslijn te omlijnen terug. Er wordt geen overerving toegepast. Alleen-lezen [`ILineFormat`](../../aspose.slides/ilineformat). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergelijkt met het opgegeven object. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Geeft de hashcode terug. |

### Opmerkingen

Deze klasse wordt gebruikt om de opmaak-eigenschappen van een tekstgedeelte die voor het specifieke gedeelte zijn gedefinieerd, op te halen en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het opvragen van waarden, dus in de meeste gevallen krijg je waarden die ‘onbepaald’ betekenen.

Om de effectieve formatteerparameterwaarden inclusief geërfde waarden te verkrijgen, moet je de [`GetEffective`](../../aspose.slides/portionformat/geteffective)-methode gebruiken die een [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)-instantie retourneert.

### Zie ook

* klasse [BasePortionFormat](../../aspose.slides/baseportionformat)
* interface [IChartPortionFormat](../ichartportionformat)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->