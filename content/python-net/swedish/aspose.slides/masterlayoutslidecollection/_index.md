---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection klass

Representerar en samling av alla layout-bilder för definierad master-slide.
            Utökar LayoutSlideCollection klass med metoder för att lägga till/infoga/ta bort/klona/omordna 
            layout-bilder i sammanhanget av de individuella samlingarna av masterns layout-bilder.

**Inheritance:**[`MasterLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/sv/aspose.slides/layoutslidecollection)

Typen MasterLayoutSlideCollection exponerar följande medlemmar:

## Indexör

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | Returnerar den första layout-bilden av angiven typ.<br/>            En typ av layout-bild att hitta.[`LayoutSlide`](/slides/python-net/sv/aspose.slides/layoutslide) med angiven typ eller None om inga layouter hittas. |
| [`remove(self, value)`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | Tar bort en layout från samlingen. |
| [`remove_unused(self)`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection/remove_unused/#) | Tar bort oanvända layout-bilder (layout-bilder vars HasDependingSlides är false). |
| [`add_clone(self, source_layout)`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | Lägger till en kopia av en angiven layout-bild i slutet av samlingen. |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | Infogar en kopia av en angiven layout-bild på angiven position i samlingen. |
| [`add(self, layout_type, layout_name)`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | Lägger till en ny layout-bild i slutet av samlingen. |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | Infogar en ny layout-bild på angiven position i samlingen. |
| [`remove_at(self, index)`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection/remove_at/#int) | Tar bort elementet på det angivna indexet i samlingen. |
| [`reorder(self, index, layout_slide)`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | Flyttar layout-bild från samlingen till den angivna positionen. |


### Se även
* klass [`LayoutSlideCollection`](/slides/python-net/sv/aspose.slides/layoutslidecollection)
* klass [`MasterLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)