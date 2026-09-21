---
title: ParagraphFormat class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/paragraphformat/
---
## ParagraphFormat klasse

Deze klasse bevat de alinea-opmaak-eigenschappen. In tegenstelling tot [`IParagraphFormatEffectiveData`](/slides/python-net/nl/aspose.slides/iparagraphformateffectivedata) zijn alle eigenschappen van deze klasse schrijfbaar.

**Inheritance:**[`ParagraphFormat`](/slides/python-net/nl/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/nl/aspose.slides/pviobject)

Het ParagraphFormat-type biedt de volgende leden:

## Constructoren

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides/paragraphformat/__init__/#) | Initialiseert een nieuw exemplaar van de [`ParagraphFormat`](/slides/python-net/nl/aspose.slides/paragraphformat)-klasse. |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`alignment`](/slides/python-net/nl/aspose.slides/paragraphformat/alignment/) | Retourneert of stelt de tekstuitlijning in een alinea zonder overerving in.<br/>            Lezen/Schrijven [`TextAlignment`](/slides/python-net/nl/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/nl/aspose.slides/paragraphformat/space_within/) | Retourneert of stelt de hoeveelheid ruimte tussen basislijnen in een alinea in. Een positieve waarde betekent percentage, een negatieve - grootte in punten. Geen overerving toegepast.<br/>            Lezen/Schrijven **float**. |
| [`space_before`](/slides/python-net/nl/aspose.slides/paragraphformat/space_before/) | Retourneert of stelt de hoeveelheid ruimte vóór de eerste regel in een alinea zonder overerving in.<br/>            Een positieve waarde specificeert het percentage van de lettergrootte dat de witruimte moet zijn.<br/>            Een negatieve waarde specificeert de grootte van de witruimte in punten.<br/>            Lezen/Schrijven **float**. |
| [`space_after`](/slides/python-net/nl/aspose.slides/paragraphformat/space_after/) | Retourneert of stelt de hoeveelheid ruimte na de laatste regel in een alinea zonder overerving in.<br/>            Een positieve waarde specificeert het percentage van de lettergrootte dat de witruimte moet zijn.<br/>            Een negatieve waarde specificeert de grootte van de witruimte in punten.<br/>            Lezen/Schrijven **float**. |
| [`east_asian_line_break`](/slides/python-net/nl/aspose.slides/paragraphformat/east_asian_line_break/) | Bepaalt of de Oost-Aziatische regeleinde wordt gebruikt in een alinea. Geen overerving toegepast.<br/>            Lezen/Schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/nl/aspose.slides/paragraphformat/right_to_left/) | Bepaalt of rechts-naar-links schrijven wordt gebruikt in een alinea. Geen overerving toegepast.<br/>            Lezen/Schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/nl/aspose.slides/paragraphformat/latin_line_break/) | Bepaalt of de Latijnse regeleinde wordt gebruikt in een alinea. Geen overerving toegepast.<br/>            Lezen/Schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/nl/aspose.slides/paragraphformat/hanging_punctuation/) | Bepaalt of de hangende interpunctie wordt gebruikt in een alinea. Geen overerving toegepast.<br/>            Lezen/Schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/nl/aspose.slides/paragraphformat/margin_left/) | Retourneert of stelt de linkermarge in een alinea zonder overerving in.<br/>            Lezen/Schrijven **float**. |
| [`margin_right`](/slides/python-net/nl/aspose.slides/paragraphformat/margin_right/) | Retourneert of stelt de rechtermargin in een alinea zonder overerving in.<br/>            Lezen/Schrijven **float**. |
| [`indent`](/slides/python-net/nl/aspose.slides/paragraphformat/indent/) | Retourneert of stelt de eerste regel-inspringing/hangende inspringing van een alinea in zonder overerving. Hangende inspringing kan worden gedefinieerd met negatieve waarden.<br/>            Lezen/Schrijven **float**. |
| [`default_tab_size`](/slides/python-net/nl/aspose.slides/paragraphformat/default_tab_size/) | Retourneert of stelt de standaard tabulatiegrootte in zonder overerving.<br/>            Lezen/Schrijven **float**. |
| [`tabs`](/slides/python-net/nl/aspose.slides/paragraphformat/tabs/) | Retourneert tabulaties van een alinea. Geen overerving toegepast.<br/>            Alleen-lezen [`ITabCollection`](/slides/python-net/nl/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/nl/aspose.slides/paragraphformat/font_alignment/) | Retourneert of stelt een lettertype-uitlijning in een alinea zonder overerving in.<br/>            Lezen/Schrijven [`FontAlignment`](/slides/python-net/nl/aspose.slides/fontalignment). |
| [`slide`](/slides/python-net/nl/aspose.slides/paragraphformat/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides/paragraphformat/presentation/) |  |
| [`bullet`](/slides/python-net/nl/aspose.slides/paragraphformat/bullet/) |  |
| [`depth`](/slides/python-net/nl/aspose.slides/paragraphformat/depth/) |  |
| [`default_portion_format`](/slides/python-net/nl/aspose.slides/paragraphformat/default_portion_format/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/nl/aspose.slides/paragraphformat/get_effective/#) | Verkrijgt effectieve alinea-opmaakgegevens met de toegepaste overerving. |

### Opmerkingen

Deze klasse wordt gebruikt om alinea-opmaak-eigenschappen die voor een specifieke alinea zijn gedefinieerd, op te halen en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, zodat u in de meeste gevallen waarden krijgt die “onbepaald” betekenen.

Om de effectieve opmaak-parameterwaarden inclusief geërfde waarden te verkrijgen, moet u de [`ParagraphFormat.get_effective`](/slides/python-net/nl/aspose.slides/paragraphformat/get_effective)-methode gebruiken die een [`IParagraphFormatEffectiveData`](/slides/python-net/nl/aspose.slides/iparagraphformateffectivedata)-instantie retourneert.

### Zie ook
* klasse [`IParagraphFormatEffectiveData`](/slides/python-net/nl/aspose.slides/iparagraphformateffectivedata)
* klasse [`ParagraphFormat`](/slides/python-net/nl/aspose.slides/paragraphformat)
* klasse [`PVIObject`](/slides/python-net/nl/aspose.slides/pviobject)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)