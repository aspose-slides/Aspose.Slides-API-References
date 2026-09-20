---
title: Sequence class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.animation/sequence/
---
## Sequence třída

Representuje sekvenci (kolekci efektů).

Typ Sequence obsahuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`count`](/slides/python-net/cs/aspose.slides.animation/sequence/count/) | Vrací počet efektů v sekvenci.<br/>            Pouze pro čtení **int**. |
| [`trigger_shape`](/slides/python-net/cs/aspose.slides.animation/sequence/trigger_shape/) | Vrací nebo nastavuje cíl tvaru pro INTERACTIVE sekvenci.<br/>            Pokud sekvence není interaktivní, vrátí None.<br/>            Čtení/Zápis [`IShape`](/slides/python-net/cs/aspose.slides/ishape). |

Vrací efekt na zadaném indexu.

## Indexér

| Název | Popis |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides.animation/sequence/__getitem__/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/cs/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Přidá nový efekt na konec sekvence. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/cs/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Přidá nový animační efekt pro odstavec na konec sekvence. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/cs/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Přidá nový animační efekt grafu pro kategorii nebo sérii na konec sekvence. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/cs/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Přidá nový animační efekt grafu pro prvky v kategorii nebo sérii na konec sekvence. |
| [`remove(self, item)`](/slides/python-net/cs/aspose.slides.animation/sequence/remove/#ieffect) | Odstraní zadaný efekt ze sbírky. |
| [`remove_at(self, index)`](/slides/python-net/cs/aspose.slides.animation/sequence/remove_at/#int) | Odstraní efekt ze sbírky. |
| [`clear(self)`](/slides/python-net/cs/aspose.slides.animation/sequence/clear/#) | Odstraní všechny efekty ze sbírky. |
| [`remove_by_shape(self, shape)`](/slides/python-net/cs/aspose.slides.animation/sequence/remove_by_shape/#ishape) | Odstraní efekt pro zadaný tvar. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/cs/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | Vrací pole efektů pro zadaný tvar. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/cs/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | Vrací pole efektů pro zadaný odstavec. |
| [`get_count(self, shape)`](/slides/python-net/cs/aspose.slides.animation/sequence/get_count/#ishape) | Vrací počet efektů pro zadaný tvar. |


### Viz také
* modul [`aspose.slides.animation`](/slides/python-net/cs/aspose.slides.animation)
* knihovna [`Aspose.Slides`](/slides/python-net)