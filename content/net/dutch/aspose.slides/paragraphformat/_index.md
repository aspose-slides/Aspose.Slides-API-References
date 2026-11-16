---
title: ParagraphFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Deze klasse bevat de alinea-opmaak eigenschappen. In tegenstelling tot IParagraphFormatEffectiveData./iparagraphformateffectivedata zijn alle eigenschappen van deze klasse schrijfbaar.
type: docs
weight: 9330
url: /nl/aspose.slides/paragraphformat/
---
## ParagraphFormat klasse

Deze klasse bevat de alinea-opmaak eigenschappen. In tegenstelling tot [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) zijn alle eigenschappen van deze klasse schrijfbaar.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Constructoren

| Naam | Beschrijving |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Initialiseert een nieuw exemplaar van [`ParagraphFormat`](../paragraphformat) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Retourneert of stelt de tekstuitlijning in een alinea in zonder overerving. Lezen/schrijven [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Maakt het mogelijk om de basis IPresentationComponent interface op te halen. Alleen-lezen [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Retourneert of stelt de standaard tabulatiegrootte in zonder overerving. Lezen/schrijven Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Bepaalt of de Oost-Aziatische regelafbreking wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Retourneert of stelt een lettertype-uitlijning in een alinea in zonder overerving. Lezen/schrijven [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Bepaalt of de hangende interpunctie wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Retourneert of stelt de eerste regel insprong/hangende insprong van een alinea in zonder overerving. Hangende insprong kan worden gedefinieerd met negatieve waarden. Lezen/schrijven Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Bepaalt of de Latijnse regelafbreking wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Retourneert of stelt de linkermarge in een alinea in zonder overerving. Lezen/schrijven Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Retourneert of stelt de rechtermarge in een alinea in zonder overerving. Lezen/schrijven Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Bepaalt of van rechts naar links schrijven wordt gebruikt in een alinea. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Retourneert of stelt de hoeveelheid ruimte na de laatste regel in een alinea in zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witte ruimte moet zijn. Een negatieve waarde geeft de grootte van de witte ruimte in punt aan. Lezen/schrijven Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Retourneert of stelt de hoeveelheid ruimte vóór de eerste regel in een alinea in zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witte ruimte moet zijn. Een negatieve waarde geeft de grootte van de witte ruimte in punt aan. Lezen/schrijven Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Retourneert of stelt de hoeveelheid ruimte tussen basisregels in een alinea in. Een positieve waarde betekent percentage, een negatieve - grootte in punten. Geen overerving toegepast. Lezen/schrijven Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Retourneert tabulaties van een alinea. Geen overerving toegepast. Alleen-lezen [`ITabCollection`](../itabcollection). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergelijkt met opgegeven object. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Haalt effectieve alinea-opmaakgegevens op met de overerving toegepast. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retourneert hashcode. |

### Opmerkingen

Deze klasse wordt gebruikt om alinea-opmaak eigenschappen die voor een specifieke alinea zijn gedefinieerd te retourneren en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, dus in de meeste gevallen krijg je waarden die “onbepaald” betekenen.

Om de effectieve opmaakparameterwaarden, inclusief geërfd, te verkrijgen, moet je de [`GetEffective`](./geteffective)-methode gebruiken die een [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) instantie retourneert.

### Zie ook

* klasse [PVIObject](../pviobject)
* interface [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interface [IParagraphFormat](../iparagraphformat)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->