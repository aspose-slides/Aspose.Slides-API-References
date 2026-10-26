---
title: Sequence class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.animation/sequence/
---
## Sequence klass

Representerar sekvens (samling av effekter).
Sequencetypen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`count`](/slides/python-net/sv/aspose.slides.animation/sequence/count/) | Returnerar antalet effekter i en sekvens.<br/>            Skrivskyddad **int**. |
| [`trigger_shape`](/slides/python-net/sv/aspose.slides.animation/sequence/trigger_shape/) | Returnerar eller anger shape target för INTERACTIVE-sekvens.<br/>            Om sekvensen inte är interaktiv returneras None.<br/>            Läs/skriv [`IShape`](/slides/python-net/sv/aspose.slides/ishape). |

Returnerar en effekt på det angivna indexet.

## Index

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides.animation/sequence/__getitem__/) |  |
## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/sv/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Lägg till en ny effekt i slutet av sekvensen. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/sv/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Lägg till en ny animeringseffekt för stycke i slutet av sekvensen. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/sv/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Lägger till den nya diagramanimeringseffekten för kategori eller serie i slutet av sekvensen. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/sv/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Lägger till den nya diagramanimeringseffekten för element i kategori eller serie i slutet av sekvensen. |
| [`remove(self, item)`](/slides/python-net/sv/aspose.slides.animation/sequence/remove/#ieffect) | Tar bort specificerad effekt från en samling. |
| [`remove_at(self, index)`](/slides/python-net/sv/aspose.slides.animation/sequence/remove_at/#int) | Tar bort en effekt från en samling. |
| [`clear(self)`](/slides/python-net/sv/aspose.slides.animation/sequence/clear/#) | Tar bort alla effekter från en samling. |
| [`remove_by_shape(self, shape)`](/slides/python-net/sv/aspose.slides.animation/sequence/remove_by_shape/#ishape) | Ta bort effekt för den specificerade formen. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/sv/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | Returnerar en array av effekter för den specificerade formen. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/sv/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | Returnerar en array av effekter för det specificerade stycket. |
| [`get_count(self, shape)`](/slides/python-net/sv/aspose.slides.animation/sequence/get_count/#ishape) | Returnerar antalet effekter för den specificerade formen. |

### Se även
* modul [`aspose.slides.animation`](/slides/python-net/sv/aspose.slides.animation)
* bibliotek [`Aspose.Slides`](/slides/python-net)