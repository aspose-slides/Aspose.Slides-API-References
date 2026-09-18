---
title: ISequence class
second_title: Aspose.Slides a Pythonhoz a .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides.animation/isequence/
---
## ISequence osztály

Képviseli a sorozatot (hatások gyűjteménye).

Az ISequence típus a következő tagokkal rendelkezik:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`count`](/slides/python-net/hu/aspose.slides.animation/isequence/count/) | Returns the number of effects in a sequense.<br/>            Csak olvasható **int**. |
| [`trigger_shape`](/slides/python-net/hu/aspose.slides.animation/isequence/trigger_shape/) | Returns or sets shape target for INTERACTIVE sequence.<br/>            If sequence is not interactive then returns None.<br/>            Olvasás/írás [`IShape`](/slides/python-net/hu/aspose.slides/ishape). |

Visszaad egy hatást a megadott indexen.

## Indexelő

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides.animation/isequence/__getitem__/) | Index |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/hu/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Új hatást ad hozzá a sorozat végéhez. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/hu/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Új animációs hatást ad hozzá a bekezdéshez a sorozat végén. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/hu/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Új diagram animációs hatást ad a kategória vagy sorozat számára a sorozat végéhez. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/hu/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Új diagram animációs hatást ad a kategória vagy sorozat elemeihez a sorozat végéhez. |
| [`remove(self, item)`](/slides/python-net/hu/aspose.slides.animation/isequence/remove/#ieffect) | Eltávolítja a megadott hatást a gyűjteményből. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides.animation/isequence/remove_at/#int) | Eltávolít egy hatást a gyűjteményből. |
| [`clear(self)`](/slides/python-net/hu/aspose.slides.animation/isequence/clear/#) | Eltávolítja az összes hatást a gyűjteményből. |
| [`remove_by_shape(self, shape)`](/slides/python-net/hu/aspose.slides.animation/isequence/remove_by_shape/#ishape) | Eltávolítja a hatást a megadott alakzatról. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/hu/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | Visszaad egy tömböt a megadott alakzatra vonatkozó hatásokkal. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/hu/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | Visszaad egy tömböt a megadott bekezdés hatásaival. |
| [`get_count(self, shape)`](/slides/python-net/hu/aspose.slides.animation/isequence/get_count/#ishape) | Visszaadja a hatások számát a megadott alakzatra. |

### Lásd még
* modul [`aspose.slides.animation`](/slides/python-net/hu/aspose.slides.animation)
* könyvtár [`Aspose.Slides`](/slides/python-net)