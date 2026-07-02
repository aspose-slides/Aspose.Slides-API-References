---
title: ParagraphFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Deze klasse bevat de alinea-opmaak-eigenschappen. In tegenstelling tot IParagraphFormatEffectiveData./iparagraphformateffectivedata zijn alle eigenschappen van deze klasse beschrijfbaar.
type: docs
weight: 9310
url: /nl/aspose.slides/paragraphformat/
---
## ParagraphFormat klasse

Deze klasse bevat de opmaak-eigenschappen van alinea's. In tegenstelling tot [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), zijn alle eigenschappen van deze klasse beschrijfbaar.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Initialiseert een nieuw exemplaar van [`ParagraphFormat`](../paragraphformat) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Geeft de tekstuitlijning in een alinea terug of stelt deze in zonder overerving. Lezen/Schrijven [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Staat toe de basis-IPresentationComponent-interface op te halen. Alleen-lezen [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Geeft de standaard tabulatiegrootte terug of stelt deze in zonder overerving. Lezen/Schrijven Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Bepaalt of de Oost-Aziatische regeleinde wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Geeft een lettertype-uitlijning in een alinea terug of stelt deze in zonder overerving. Lezen/Schrijven [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Bepaalt of hangende interpunctie wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Geeft de eerste-lijn-insprong/hangende-insprong van een alinea terug of stelt deze in zonder overerving. Hangende-insprong kan met negatieve waarden worden gedefinieerd. Lezen/Schrijven Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Bepaalt of de Latin-regeleinde wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Geeft de linkermarge in een alinea terug of stelt deze in zonder overerving. Lezen/Schrijven Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Geeft de rechtermarge in een alinea terug of stelt deze in zonder overerving. Lezen/Schrijven Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Bepaalt of rechts-naar-links schrijven wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Geeft de hoeveelheid ruimte na de laatste regel in een alinea terug of stelt deze in zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet zijn. Een negatieve waarde geeft de grootte van de witruimte in punten aan. Lezen/Schrijven Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Geeft de hoeveelheid ruimte vóór de eerste regel in een alinea terug of stelt deze in zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet zijn. Een negatieve waarde geeft de grootte van de witruimte in punten aan. Lezen/Schrijven Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Geeft de hoeveelheid ruimte tussen basisregels in een alinea terug of stelt deze in. Positieve waarde betekent percentage, negatieve – grootte in punten. Geen overerving toegepast. Lezen/Schrijven Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Geeft de tabulaties van een alinea terug. Geen overerving toegepast. Alleen-lezen [`ITabCollection`](../itabcollection). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergelijkt met opgegeven object. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Haalt effectieve alinea-opmaakgegevens op met de toegepaste overerving. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Geeft hash-code terug. |

### Opmerkingen

Deze klasse wordt gebruikt om de opmaak-eigenschappen van een specifieke alinea op te halen en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, zodat in de meeste gevallen de waarden “ongedefinieerd” zijn.

Om de effectieve opmaak-parameterwaarden inclusief geërfde waarden te krijgen, moet u de [`GetEffective`](./geteffective)-methode gebruiken die een [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)-instantie retourneert.

### Zie ook

* klasse [PVIObject](../pviobject)
* interface [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interface [IParagraphFormat](../iparagraphformat)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->