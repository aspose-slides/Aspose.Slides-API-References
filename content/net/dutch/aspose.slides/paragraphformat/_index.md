---
title: ParagraphFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Deze klasse bevat de alinea-opmaak eigenschappen. In tegenstelling tot IParagraphFormatEffectiveData./iparagraphformateffectivedata zijn alle eigenschappen van deze klasse schrijfbaar.
type: docs
weight: 9310
url: /nl/aspose.slides/paragraphformat/
---
## ParagraphFormat klasse

Deze klasse bevat de alinea-opmaak eigenschappen. In tegenstelling tot [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), zijn alle eigenschappen van deze klasse schrijfbaar.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Constructoren

| Naam | Beschrijving |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Initialiseert een nieuwe instantie van [`ParagraphFormat`](../paragraphformat) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Geeft de tekstuitlijning in een alinea terug of stelt deze in zonder overerving. Lezen/schrijven [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Staat toe de basis-IPresentationComponent-interface op te halen. Alleen-lezen [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Geeft de standaardtabulatiegrootte terug of stelt deze in zonder overerving. Lezen/schrijven Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Bepaalt of de Oost-Aziatische regeleinde wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Geeft een lettertype-uitlijning in een alinea terug of stelt deze in zonder overerving. Lezen/schrijven [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Bepaalt of hangende interpunctie wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Geeft de eerste regel-inspringing/hangende inspringing van de alinea terug of stelt deze in zonder overerving. Hangende inspringing kan met negatieve waarden worden gedefinieerd. Lezen/schrijven Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Bepaalt of de Latijnse regeleinde wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Geeft de linkermarge in een alinea terug of stelt deze in zonder overerving. Lezen/schrijven Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Geeft de rechtermarge in een alinea terug of stelt deze in zonder overerving. Lezen/schrijven Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Bepaalt of van rechts naar links schrijven wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Geeft de hoeveelheid ruimte na de laatste regel in een alinea terug of stelt deze in zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet zijn. Een negatieve waarde geeft de grootte van de witruimte in punten aan. Lezen/schrijven Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Geeft de hoeveelheid ruimte vóór de eerste regel in een alinea terug of stelt deze in zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet zijn. Een negatieve waarde geeft de grootte van de witruimte in punten aan. Lezen/schrijven Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Geeft de hoeveelheid ruimte tussen basislijnen in een alinea terug of stelt deze in. Positieve waarde betekent percentage, negatieve - grootte in punten. Geen overerving toegepast. Lezen/schrijven Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Geeft de tabulaties van een alinea terug. Geen overerving toegepast. Alleen-lezen [`ITabCollection`](../itabcollection). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergelijkt met het opgegeven object. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Haalt de effectieve alinea-opmaakgegevens op met de toegepaste overerving. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Geeft de hash-code terug. |

### Opmerkingen

Deze klasse wordt gebruikt om alinea-opmaak eigenschappen die voor een specifieke alinea zijn gedefinieerd, op te halen en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, dus in de meeste gevallen krijg je waarden die "onbepaald" betekenen.

Om de effectieve opmaak-parameterwaarden, inclusief geërfde, te krijgen, moet je de [`GetEffective`](./geteffective)-methode gebruiken die een [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)-instantie retourneert.

### Zie ook

* klasse [PVIObject](../pviobject)
* interface [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interface [IParagraphFormat](../iparagraphformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->