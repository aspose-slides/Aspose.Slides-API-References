---
title: IParagraphFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Deze klasse bevat de alinea-opmaak eigenschappen. In tegenstelling tot IParagraphFormatEffectiveData./iparagraphformateffectivedata zijn alle eigenschappen van deze klasse schrijfbaar.
type: docs
weight: 6590
url: /nl/aspose.slides/iparagraphformat/
---
## IParagraphFormat interface

Deze klasse bevat de alinea-opmaak eigenschappen. In tegenstelling tot [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), zijn alle eigenschappen van deze klasse schrijfbaar.

```csharp
public interface IParagraphFormat
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Geeft de tekstuitlijning in een alinea terug of stelt deze in zonder overerving. Lezen/schrijven [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Geeft het opsommingstekenformaat van de alinea terug. Alleen-lezen [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Geeft het standaardgedeelteformaat van een alinea terug. Er wordt geen overerving toegepast. Alleen-lezen [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Geeft de standaardtabulatiegrootte terug of stelt deze in zonder overerving. Lezen/schrijven Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Geeft de diepte van de alinea terug of stelt deze in. Waarde 0 betekent een ongedefinieerde waarde. Lezen/schrijven Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Bepaalt of de Oost-Aziatische regeleinde wordt gebruikt in een alinea. Er wordt geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Geeft een lettertype-uitlijning in een alinea terug of stelt deze in zonder overerving. Lezen/schrijven [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Bepaalt of hangende interpunctie wordt gebruikt in een alinea. Er wordt geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Geeft de eerste-regel-inspringing/hangende inspringing van een alinea terug of stelt deze in zonder overerving. Hangende inspringing kan worden gedefinieerd met negatieve waarden. Lezen/schrijven Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Bepaalt of de Latijnse regeleinde wordt gebruikt in een alinea. Er wordt geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Geeft de linkermarge in een alinea terug of stelt deze in zonder overerving. Lezen/schrijven Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Geeft de rechtermarge in een alinea terug of stelt deze in zonder overerving. Lezen/schrijven Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Bepaalt of van rechts-naar-links schrijven wordt gebruikt in een alinea. Er wordt geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Geeft de hoeveelheid ruimte na de laatste regel in een alinea terug of stelt deze in zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet innemen. Een negatieve waarde geeft de grootte van de witruimte in punten aan. Lezen/schrijven Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Geeft de hoeveelheid ruimte vóór de eerste regel in een alinea terug of stelt deze in zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet innemen. Een negatieve waarde geeft de grootte van de witruimte in punten aan. Lezen/schrijven Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Geeft de hoeveelheid ruimte tussen basislijnen in een alinea terug of stelt deze in. Een positieve waarde betekent een percentage, een negatieve - grootte in punten. Er wordt geen overerving toegepast. Lezen/schrijven Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Geeft de tabulaties van een alinea terug. Er wordt geen overerving toegepast. Alleen-lezen [`ITabCollection`](../itabcollection). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Geeft de effectieve alinea-opmaakgegevens terug met de toegepaste overerving. |

### Opmerkingen

Deze klasse wordt gebruikt om alinea-opmaak eigenschappen die voor een specifieke alinea zijn gedefinieerd terug te geven en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, dus in de meeste gevallen krijg je waarden die “ongedefinieerd” betekenen.

Om de effectieve opmaakparameterwaarden, inclusief geërfde, te verkrijgen, moet je de [`GetEffective`](./geteffective) methode gebruiken die een [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) instantie retourneert.

### Zie ook

* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->