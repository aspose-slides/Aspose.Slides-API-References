---
title: ChartPortionFormat
second_title: Aspose.Sildes voor .NET API Referentie
description: Deze klasse bevat de opmaak-eigenschappen van het diagramgedeelte die in diagrammen worden gebruikt. In tegenstelling tot IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata zijn alle eigenschappen van deze klasse schrijfbaar.
type: docs
weight: 1440
url: /nl/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat klasse

This class contains the chart portion formatting properties used in charts. Unlike [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), all properties of this class are writeable.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Geeft de Id van een alternatieve taal terug of stelt deze in. Lees/schrijf String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Staat toe de basis IPresentationComponent interface op te halen. Alleen-lezen [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Geeft de complexe scriptlettertype-informatie terug of stelt deze in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lees/schrijf [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Geeft de Oost-Aziaanse lettertype-informatie terug of stelt deze in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lees/schrijf [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Geeft de tekst EffectFormat-eigenschappen terug. Geen overerving toegepast. Alleen-lezen [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Geeft de superscript- of subscript-tekst terug of stelt deze in. Waarde van -100% (subscript) tot 100% (superscript). **float.NaN** betekent dat de waarde niet is gedefinieerd en moet worden geërfd van de Master. Lees/schrijf Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Geeft de tekst FillFormat-eigenschappen terug. Geen overerving toegepast. Alleen-lezen [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bepaalt of het lettertype vet is. Geen overerving toegepast. Lees/schrijf [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Geeft de letterhoogte van een gedeelte terug of stelt deze in. **float.NaN** betekent dat de hoogte niet is gedefinieerd en moet worden geërfd van de Master. Lees/schrijf Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bepaalt of het lettertype cursief is. Geen overerving toegepast. Lees/schrijf [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Geeft het onderstrepingstype van de tekst terug of stelt dit in. Geen overerving toegepast. Lees/schrijf [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Geeft de kleur die wordt gebruikt om tekst te markeren terug. Geen overerving toegepast. Alleen-lezen [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bepaalt of de onderstrepingsstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Lees/schrijf [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bepaalt of de onderstrepingsstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Lees/schrijf [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Geeft de minimale lettergrootte terug of stelt deze in, waarvoor kerning moet worden ingeschakeld. **float.NaN** betekent dat de waarde niet is gedefinieerd en moet worden geërfd van de Master. Lees/schrijf Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bepaalt of de cijfers de specifieke verticale lay-out van oosterse tekst moeten negeren. Geen overerving toegepast. Lees/schrijf [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Geeft de Id van een proefleestaal terug of stelt deze in. Wordt gebruikt voor spelling- en grammaticacontrole. Lees/schrijf String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Geeft de Latijnse lettertype-informatie terug of stelt deze in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lees/schrijf [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Geeft de LineFormat-eigenschappen voor tekstomlijning terug. Geen overerving toegepast. Alleen-lezen [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Geen overerving toegepast. Lees/schrijf [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bepaalt of de tekst niet gecorrigeerd mag worden. Geen overerving toegepast. Lees/schrijf [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Geeft de interkarakter-spatiëringsstap terug of stelt deze in. **float.NaN** betekent dat de waarde niet is gedefinieerd en moet worden geërfd van de Master. Lees/schrijf Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Haal een waarde op of stel een waarde in die aangeeft of spellingscontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap false is, worden spellingcontroles voor textelementen onderdrukt. Wanneer true, is spellingscontrole toegestaan. Standaardwaarde is `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Geeft het doorhalings-type van een tekst terug of stelt dit in. Geen overerving toegepast. Lees/schrijf [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Geeft de symbolische lettertype-informatie terug of stelt deze in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lees/schrijf [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Geeft het type hoofdlettergebruik van de tekst terug of stelt dit in. Geen overerving toegepast. Lees/schrijf [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Geeft de onderstrepingslijn FillFormat-eigenschappen terug. Geen overerving toegepast. Alleen-lezen [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Geeft de LineFormat-eigenschappen terug die worden gebruikt om de onderstrepingslijn te omlijnen. Geen overerving toegepast. Alleen-lezen [`ILineFormat`](../../aspose.slides/ilineformat). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergelijkt met het opgegeven object. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Geeft hashcode terug. |

### Opmerkingen

Deze klasse wordt gebruikt om de opmaak-eigenschappen van een tekstgedeelte die voor dat specifieke gedeelte zijn gedefinieerd, terug te geven en te bewerken. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, dus in de meeste gevallen krijg je waarden die “ongedefinieerd” betekenen.

Om de effectieve opmaak-parameterwaarden, inclusief geërfde, te verkrijgen, moet je de [`GetEffective`](../../aspose.slides/portionformat/geteffective)-methode gebruiken die een [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)-instantie teruggeeft.

### Zie ook

* klasse [BasePortionFormat](../../aspose.slides/baseportionformat)
* interface [IChartPortionFormat](../ichartportionformat)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->