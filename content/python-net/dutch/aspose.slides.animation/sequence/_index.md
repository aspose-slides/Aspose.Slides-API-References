---
title: Sequence class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.animation/sequence/
---
## Sequence klasse

Stelt een sequentie (collectie van effecten) voor.

Het type Sequence geeft de volgende leden weer:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`count`](/slides/python-net/nl/aspose.slides.animation/sequence/count/) | Retourneert het aantal effecten in een sequentie.<br/>            Alleen-lezen **int**. |
| [`trigger_shape`](/slides/python-net/nl/aspose.slides.animation/sequence/trigger_shape/) | Retourneert of stelt het vormdoel in voor een INTERACTIVE sequentie.<br/>            Als de sequentie niet interactief is, retourneert dan None.<br/>            Lezen/schrijven [`IShape`](/slides/python-net/nl/aspose.slides/ishape). |

Retourneert een effect op de opgegeven index.

## Indexer

| Naam | Beschrijving |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides.animation/sequence/__getitem__/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/nl/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Voeg een nieuw effect toe aan het einde van de sequentie. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/nl/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Voeg een nieuw animatie-effect voor alinea toe aan het einde van de sequentie. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/nl/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Voegt het nieuwe grafiekanimatie-effect voor categorie of reeks toe aan het einde van de sequentie. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/nl/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Voegt het nieuwe grafiekanimatie-effect voor elementen in categorie of reeks toe aan het einde van de sequentie. |
| [`remove(self, item)`](/slides/python-net/nl/aspose.slides.animation/sequence/remove/#ieffect) | Verwijdert het opgegeven effect uit een collectie. |
| [`remove_at(self, index)`](/slides/python-net/nl/aspose.slides.animation/sequence/remove_at/#int) | Verwijdert een effect uit een collectie. |
| [`clear(self)`](/slides/python-net/nl/aspose.slides.animation/sequence/clear/#) | Verwijdert alle effecten uit een collectie. |
| [`remove_by_shape(self, shape)`](/slides/python-net/nl/aspose.slides.animation/sequence/remove_by_shape/#ishape) | Verwijder effect voor de opgegeven vorm. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/nl/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | Retourneert een array van effecten voor de opgegeven vorm. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/nl/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | Retourneert een array van effecten voor de opgegeven alinea. |
| [`get_count(self, shape)`](/slides/python-net/nl/aspose.slides.animation/sequence/get_count/#ishape) | Retourneert het aantal effecten voor de opgegeven vorm. |

### Zie ook
* module [`aspose.slides.animation`](/slides/python-net/nl/aspose.slides.animation)
* bibliotheek [`Aspose.Slides`](/slides/python-net)