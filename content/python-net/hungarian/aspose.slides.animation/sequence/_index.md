---
title: Sequence class
second_title: Aspose.Slides a Python számára .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides.animation/sequence/
---
## Sequence osztály

A sorozatot (hatások gyűjteménye) ábrázolja.

A Sequence típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`count`](/slides/python-net/hu/aspose.slides.animation/sequence/count/) | Visszaadja a hatások számát egy sorozatban.<br/>            Csak olvasható **int**. |
| [`trigger_shape`](/slides/python-net/hu/aspose.slides.animation/sequence/trigger_shape/) | Visszaadja vagy beállítja a forma célpontját INTERACTIVE sorozathoz.<br/>            Ha a sorozat nem interaktív, akkor None értéket ad vissza.<br/>            Olvasás/írás [`IShape`](/slides/python-net/hu/aspose.slides/ishape). |

Visszaad egy hatást a megadott indexnél.

## Indexelő

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides.animation/sequence/__getitem__/) |  |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/hu/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Új hatás hozzáadása a sorozat végéhez. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/hu/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Új animációs hatás hozzáadása a bekezdéshez a sorozat végén. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/hu/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Új diagram animációs hatás hozzáadása kategóriához vagy sorozathoz a sorozat végéhez. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/hu/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Új diagram animációs hatás hozzáadása a kategória vagy sorozat elemeihez a sorozat végén. |
| [`remove(self, item)`](/slides/python-net/hu/aspose.slides.animation/sequence/remove/#ieffect) | Eltávolítja a megadott hatást egy gyűjteményből. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides.animation/sequence/remove_at/#int) | Eltávolít egy hatást egy gyűjteményből. |
| [`clear(self)`](/slides/python-net/hu/aspose.slides.animation/sequence/clear/#) | Eltávolítja az összes hatást egy gyűjteményből. |
| [`remove_by_shape(self, shape)`](/slides/python-net/hu/aspose.slides.animation/sequence/remove_by_shape/#ishape) | Eltávolítja a hatást a megadott forma esetén. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/hu/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | Visszaadja a hatások tömbjét a megadott forma számára. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/hu/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | Visszaadja a hatások tömbjét a megadott bekezdés számára. |
| [`get_count(self, shape)`](/slides/python-net/hu/aspose.slides.animation/sequence/get_count/#ishape) | Visszaadja a hatások számát a megadott forma esetén. |

### Lásd még
* modul [`aspose.slides.animation`](/slides/python-net/hu/aspose.slides.animation)
* könyvtár [`Aspose.Slides`](/slides/python-net)