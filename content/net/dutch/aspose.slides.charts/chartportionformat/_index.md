---
title: ChartPortionFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Deze klasse bevat de opmaak-eigenschappen voor grafiekonderdelen die in grafieken worden gebruikt. In tegenstelling tot IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata zijn alle eigenschappen van deze klasse schrijfbaar.
type: docs
weight: 1430
url: /nl/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat klasse

Deze klasse bevat de opmaak-eigenschappen voor grafiekonderdelen die worden gebruikt in grafieken. In tegenstelling tot [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), zijn alle eigenschappen van deze klasse schrijfbaar.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Retourneert of stelt de Id van een alternatieve taal in. Read/write String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Stelt het mogelijk de basis IPresentationComponent interface op te halen. Read-only [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Retourneert of stelt de complexe scriptlettertype-informatie in. Null betekent dat het lettertype niet gedefinieerd is en moet worden geërfd van de Master. Read/write [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Retourneert of stelt de Oost-Aziatische lettertype-informatie in. Null betekent dat het lettertype niet gedefinieerd is en moet worden geërfd van de Master. Read/write [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Retourneert de EffectFormat-eigenschappen van de tekst. Er wordt geen overerving toegepast. Read-only [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Retourneert of stelt de superscript- of subscript-tekst in. Waarde van -100 % (subscript) tot 100 % (superscript). **float.NaN** betekent dat de waarde niet gedefinieerd is en moet worden geërfd van de Master. Read/write Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Retourneert de FillFormat-eigenschappen van de tekst. Er wordt geen overerving toegepast. Read-only [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bepaalt of het lettertype vetgedrukt is. Er wordt geen overerving toegepast. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Retourneert of stelt de letterhoogte van een deel in. **float.NaN** betekent dat de hoogte niet gedefinieerd is en moet worden geërfd van de Master. Read/write Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bepaalt of het lettertype cursief is. Er wordt geen overerving toegepast. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Retourneert of stelt het onderlijntype van de tekst in. Er wordt geen overerving toegepast. Read/write [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Retourneert de kleur die gebruikt wordt om een tekst te markeren. Er wordt geen overerving toegepast. Read-only [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bepaalt of de onderstreeptstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bepaalt of de onderstreeptstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Retourneert of stelt de minimale lettergrootte in waarvoor kerning moet worden ingeschakeld. **float.NaN** betekent dat de waarde niet gedefinieerd is en moet worden geërfd van de Master. Read/write Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bepaalt of de cijfers de oosterse, taal-specifieke verticale tekstlay-out moeten negeren. Er wordt geen overerving toegepast. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Retourneert of stelt de Id van een proefleestaal in. Wordt gebruikt voor spelling- en grammaticacontrole. Read/write String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Retourneert of stelt de Latijnse lettertype-informatie in. Null betekent dat het lettertype niet gedefinieerd is en moet worden geërfd van de Master. Read/write [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Retourneert de LineFormat-eigenschappen voor tekstomlijning. Er wordt geen overerving toegepast. Read-only [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Er wordt geen overerving toegepast. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bepaalt of de tekst niet moet worden proefgelezen. Er wordt geen overerving toegepast. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Retourneert of stelt de interkarakter-spatiëringsstap in. **float.NaN** betekent dat de waarde niet gedefinieerd is en moet worden geërfd van de Master. Read/write Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Haalt op of stelt een waarde in die aangeeft of spellingscontrole is ingeschakeld voor het tekstdeel. Wanneer deze eigenschap op false wordt gezet, worden spellingcontroles voor textelementen onderdrukt. Wanneer op true gezet, is spellingscontrole toegestaan. Standaardwaarde is `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Retourneert of stelt het doorhalings-type van een tekst in. Er wordt geen overerving toegepast. Read/write [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Retourneert of stelt de symbolische lettertype-informatie in. Null betekent dat het lettertype niet gedefinieerd is en moet worden geërfd van de Master. Read/write [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Retourneert of stelt het type hoofdlettergebruik van de tekst in. Er wordt geen overerving toegepast. Read/write [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Retourneert de FillFormat-eigenschappen van de onderstreeplijn. Er wordt geen overerving toegepast. Read-only [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstreeplijn te omlijnen. Er wordt geen overerving toegepast. Read-only [`ILineFormat`](../../aspose.slides/ilineformat). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergelijkt met het opgegeven object. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retourneert hashcode. |

### Opmerkingen

Deze klasse wordt gebruikt om de opmaak-eigenschappen van een tekstdeel op te halen en te manipuleren die voor dat specifieke deel zijn gedefinieerd. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, zodat je in de meeste gevallen waarden krijgt die "onbepaald" betekenen.

Om de effectieve opmaak-parameterwaarden, inclusief geërfde waarden, te verkrijgen moet je de [`GetEffective`](../../aspose.slides/portionformat/geteffective)-methode gebruiken die een [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)-instantie retourneert.

### Zie ook

* klasse [BasePortionFormat](../../aspose.slides/baseportionformat)
* interface [IChartPortionFormat](../ichartportionformat)
* naamruimte [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->