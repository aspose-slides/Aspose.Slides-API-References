---
title: ISequence class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.animation/isequence/
---
## ISequence klasse

Stelt een reeks (collectie van effecten) voor.

Het ISequence-type maakt de volgende leden beschikbaar:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`count`](/slides/python-net/nl/aspose.slides.animation/isequence/count/) | Retourneert het aantal effecten in een reeks.<br/>            Alleen-lezen **int**. |
| [`trigger_shape`](/slides/python-net/nl/aspose.slides.animation/isequence/trigger_shape/) | Retourneert of stelt het shape-doel in voor een INTERACTIVE-reeks.<br/>            Als de reeks niet interactief is, dan wordt None geretourneerd.<br/>            Lezen/Schrijven [`IShape`](/slides/python-net/nl/aspose.slides/ishape). |

Retourneert een effect op de opgegeven index.

## Indexer

| Naam | Beschrijving |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides.animation/isequence/__getitem__/) | Index |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/nl/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Voeg een nieuw effect toe aan het einde van de reeks. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/nl/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Voeg een nieuw animatie-effect voor een alinea toe aan het einde van de reeks. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/nl/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Voeg het nieuwe diagram-animatie-effect voor een categorie of serie toe aan het einde van de reeks. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/nl/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Voeg het nieuwe diagram-animatie-effect voor elementen in een categorie of serie toe aan het einde van de reeks. |
| [`remove(self, item)`](/slides/python-net/nl/aspose.slides.animation/isequence/remove/#ieffect) | Verwijdert het opgegeven effect uit een collectie. |
| [`remove_at(self, index)`](/slides/python-net/nl/aspose.slides.animation/isequence/remove_at/#int) | Verwijdert een effect uit een collectie. |
| [`clear(self)`](/slides/python-net/nl/aspose.slides.animation/isequence/clear/#) | Verwijdert alle effecten uit een collectie. |
| [`remove_by_shape(self, shape)`](/slides/python-net/nl/aspose.slides.animation/isequence/remove_by_shape/#ishape) | Verwijder effect voor de opgegeven shape. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/nl/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | Retourneert een array van effecten voor de opgegeven shape. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/nl/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | Retourneert een array van effecten voor de opgegeven alinea. |
| [`get_count(self, shape)`](/slides/python-net/nl/aspose.slides.animation/isequence/get_count/#ishape) | Retourneert het aantal effecten voor de opgegeven shape. |


### Zie Ook
* module [`aspose.slides.animation`](/slides/python-net/nl/aspose.slides.animation)
* bibliotheek [`Aspose.Slides`](/slides/python-net)