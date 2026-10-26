---
title: ISectionCollection class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/isectioncollection/
---
## ISectionCollection klass

Representerar en samling sektioner.

ISectionCollection-typen exponerar följande medlemmar:

Hämtar elementet på det angivna indexet.
Skrivskyddad [`ISection`](/slides/python-net/sv/aspose.slides/isection).

## Indexer

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides/isectioncollection/__getitem__/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`add_section(self, name, started_from_slide)`](/slides/python-net/sv/aspose.slides/isectioncollection/add_section/#str-islide) | Lägg till ny sektion som startas från en specifik bild. |
| [`add_empty_section(self, name, index)`](/slides/python-net/sv/aspose.slides/isectioncollection/add_empty_section/#str-int) | Lägg till tom sektion på angiven position i samlingen. |
| [`remove_section_with_slides(self, section)`](/slides/python-net/sv/aspose.slides/isectioncollection/remove_section_with_slides/#isection) | Ta bort sektion och bilder som ingår i sektionen. |
| [`remove_section(self, section)`](/slides/python-net/sv/aspose.slides/isectioncollection/remove_section/#isection) | Ta bort sektion. Bilder som ingår i sektionen kommer att slås ihop med föregående sektion. |
| [`reorder_section_with_slides(self, section, index)`](/slides/python-net/sv/aspose.slides/isectioncollection/reorder_section_with_slides/#isection-int) | Flyttar sektion och dess bilder från samlingen till den angivna positionen. |
| [`append_empty_section(self, name)`](/slides/python-net/sv/aspose.slides/isectioncollection/append_empty_section/#str) | Lägg till tom sektion i slutet av samlingen. |
| [`index_of(self, section)`](/slides/python-net/sv/aspose.slides/isectioncollection/index_of/#isection) | Returnerar ett index för den angivna sektionen i samlingen. |
| [`clear(self)`](/slides/python-net/sv/aspose.slides/isectioncollection/clear/#) | Tar bort alla sektioner från samlingen. |

### Se även
* klass [`ISection`](/slides/python-net/sv/aspose.slides/isection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)