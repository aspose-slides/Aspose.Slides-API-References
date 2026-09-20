---
title: GlobalLayoutSlideCollection class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection klass

Representerar en samling av alla layoutbilder i presentationen.
Extends LayoutSlideCollection klass med metoder för att lägga till/klona layoutbilder i kontexten av förening av de individuella samlingarna av master-layoutbilder.

**Arv:**[`GlobalLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/globallayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/sv/aspose.slides/layoutslidecollection)

Typen GlobalLayoutSlideCollection exponerar följande medlemmar:

## Indexer

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides/globallayoutslidecollection/__getitem__/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`add_clone(self, source_layout)`](/slides/python-net/sv/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide) | Lägger till en kopia av en specificerad layoutbild till presentationen. |
| [`add_clone(self, source_layout, dest_master)`](/slides/python-net/sv/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide-imasterslide) | Lägger till en kopia av en specificerad layoutbild till presentationen. |
| [`get_by_type(self, type)`](/slides/python-net/sv/aspose.slides/globallayoutslidecollection/get_by_type/#slidelayouttype) | Returnerar den första layoutbilden av specificerad typ.<br/>En typ av layoutbild att hitta.[`LayoutSlide`](/slides/python-net/sv/aspose.slides/layoutslide) med specificerad typ eller None om inga layouter hittades. |
| [`remove(self, value)`](/slides/python-net/sv/aspose.slides/globallayoutslidecollection/remove/#ilayoutslide) | Tar bort en layout från samlingen. |
| [`remove_unused(self)`](/slides/python-net/sv/aspose.slides/globallayoutslidecollection/remove_unused/#) | Tar bort oanvända layoutbilder (layoutbilder vars HasDependingSlides är false). |
| [`add(self, master, layout_type, layout_name)`](/slides/python-net/sv/aspose.slides/globallayoutslidecollection/add/#imasterslide-slidelayouttype-str) | Lägger till en ny layoutbild till presentationen. |

### Se även
* klass [`GlobalLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/globallayoutslidecollection)
* klass [`LayoutSlideCollection`](/slides/python-net/sv/aspose.slides/layoutslidecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)