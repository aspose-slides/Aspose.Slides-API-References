---
title: ISequence class
second_title: Aspose.Slides pro Python prostřednictvím .NET API
description: 
type: docs
url: /cs/aspose.slides.animation/isequence/
---
## ISequence třída

Represents sequence (collection of effects).

The ISequence type exposes the following members:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`count`](/slides/python-net/cs/aspose.slides.animation/isequence/count/) | Vrací počet efektů v sekvenci.<br/>            Pouze ke čtení **int**. |
| [`trigger_shape`](/slides/python-net/cs/aspose.slides.animation/isequence/trigger_shape/) | Vrací nebo nastavuje cílový tvar pro INTERACTIVE sekvenci.<br/>            Pokud sekvence není interaktivní, vrátí None.<br/>            Číst/zapsat [`IShape`](/slides/python-net/cs/aspose.slides/ishape). |

Vrátí efekt na zadaném indexu.

## Indexér

| Název | Popis |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides.animation/isequence/__getitem__/) | Index |

## Metody

| Metoda | Popis |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/cs/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Přidá nový efekt na konec sekvence. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/cs/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Přidá nový animační efekt pro odstavec na konec sekvence. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/cs/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Přidá nový animační efekt grafu pro kategorii nebo sérii na konec sekvence. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/cs/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Přidá nový animační efekt grafu pro prvky v kategorii nebo sérii na konec sekvence. |
| [`remove(self, item)`](/slides/python-net/cs/aspose.slides.animation/isequence/remove/#ieffect) | Odstraní zadaný efekt z kolekce. |
| [`remove_at(self, index)`](/slides/python-net/cs/aspose.slides.animation/isequence/remove_at/#int) | Odstraní efekt z kolekce. |
| [`clear(self)`](/slides/python-net/cs/aspose.slides.animation/isequence/clear/#) | Odstraní všechny efekty z kolekce. |
| [`remove_by_shape(self, shape)`](/slides/python-net/cs/aspose.slides.animation/isequence/remove_by_shape/#ishape) | Odstraní efekt pro zadaný tvar. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/cs/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | Vrací pole efektů pro zadaný tvar. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/cs/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | Vrací pole efektů pro zadaný odstavec. |
| [`get_count(self, shape)`](/slides/python-net/cs/aspose.slides.animation/isequence/get_count/#ishape) | Vrací počet efektů pro zadaný tvar. |


### Viz také
* modul [`aspose.slides.animation`](/slides/python-net/cs/aspose.slides.animation)
* knihovna [`Aspose.Slides`](/slides/python-net)