---
title: IParagraphFormat
second_title: Aspose.Slides voor .NET API-referentie
description: Deze klasse bevat de alinea-opmaak eigenschappen. In tegenstelling tot IParagraphFormatEffectiveData./iparagraphformateffectivedata zijn alle eigenschappen van deze klasse schrijfbaar.
type: docs
weight: 6590
url: /nl/aspose.slides/iparagraphformat/
---
## IParagraphFormat interface

Deze klasse bevat de eigenschappen voor alinea-opmaak. In tegenstelling tot [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) zijn alle eigenschappen van deze klasse schrijfbaar.

```csharp
public interface IParagraphFormat
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Retourneert of stelt de tekstuitlijning in een alinea in zonder overerving. Lezen/Schrijven [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Retourneert bulletformaat van de alinea. Alleen-lezen [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Retourneert het standaardgedeelteformaat van een alinea. Zonder overerving toegepast. Alleen-lezen [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Retourneert of stelt de standaardtabulatiegrootte in zonder overerving. Lezen/Schrijven Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Retourneert of stelt de diepte van de alinea in. Waarde 0 betekent ongedefinieerde waarde. Lezen/Schrijven Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Bepaalt of de Oost-Aziatische regeleinde wordt gebruikt in een alinea. Zonder overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Retourneert of stelt een lettertype-uitlijning in een alinea zonder overerving. Lezen/Schrijven [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Bepaalt of hangende interpunctie wordt gebruikt in een alinea. Zonder overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Retourneert of stelt de eerste regelinsprong/hangende insprong van een alinea in zonder overerving. Hangende insprong kan worden gedefinieerd met negatieve waarden. Lezen/Schrijven Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Bepaalt of de Latijnse regeleinde wordt gebruikt in een alinea. Zonder overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Retourneert of stelt de linkermarge in een alinea zonder overerving. Lezen/Schrijven Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Retourneert of stelt de rechtermarge in een alinea zonder overerving. Lezen/Schrijven Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Bepaalt of van rechts naar links schrijven wordt gebruikt in een alinea. Zonder overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Retourneert of stelt de hoeveelheid ruimte na de laatste regel in een alinea zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet zijn. Een negatieve waarde geeft de grootte van de witruimte in puntgrootte aan. Lezen/Schrijven Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Retourneert of stelt de hoeveelheid ruimte vóór de eerste regel in een alinea zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet zijn. Een negatieve waarde geeft de grootte van de witruimte in puntgrootte aan. Lezen/Schrijven Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Retourneert of stelt de hoeveelheid ruimte tussen basisregels in een alinea. Positieve waarde betekent percentage, negatieve – grootte in punten. Zonder overerving toegepast. Lezen/Schrijven Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Retourneert tabulaties van een alinea. Zonder overerving toegepast. Alleen-lezen [`ITabCollection`](../itabcollection). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Haalt effectieve alinea-opmaakgegevens op met de toegepaste overerving. |

### Opmerkingen

Deze klasse wordt gebruikt om alinea-opmaak eigenschappen te retourneren en te manipuleren die zijn gedefinieerd voor de specifieke alinea. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, dus in de meeste gevallen verkrijgt u waarden die “ongedefinieerd” betekenen.

Om de effectieve opmaakparameterwaarden, inclusief geërfde, te verkrijgen, moet u de [`GetEffective`](./geteffective) methode gebruiken die een [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) instantie retourneert.

### Zie ook

* naamruimte [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->