---
title: Portion class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/portion/
---
## Portion klass

Representerar en del av text i ett textavsnitt.

Portion-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides/portion/__init__/#) | Initierar en ny instans av Portion klass. |
| [`__init__(self, str)`](/slides/python-net/sv/aspose.slides/portion/__init__/#str) | Initierar en ny instans av Portion klass. |
| [`__init__(self, portion)`](/slides/python-net/sv/aspose.slides/portion/__init__/#portion) | Initierar en ny instans av Portion klass. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`portion_format`](/slides/python-net/sv/aspose.slides/portion/portion_format/) | Returnerar formateringsobjekt som innehåller explicit angivna formateringsegenskaper för textavsnittet utan att ärva.<br/>            Skrivskyddad [`IPortionFormat`](/slides/python-net/sv/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/sv/aspose.slides/portion/text/) | Hämtar eller anger den raka texten för ett avsnitt.<br/>            Läs/skriv **str**. |
| [`field`](/slides/python-net/sv/aspose.slides/portion/field/) | Returnerar ett fält för detta avsnitt.<br/>            Skrivskyddad [`IField`](/slides/python-net/sv/aspose.slides/ifield). |
| [`slide`](/slides/python-net/sv/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/portion/presentation/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/sv/aspose.slides/portion/add_field/#ifieldtype) | Konverterar detta avsnitt till det automatiskt uppdaterade fältet. |
| [`add_field(self, internal_string)`](/slides/python-net/sv/aspose.slides/portion/add_field/#str) | Konverterar detta avsnitt till det automatiskt uppdaterade fältet. |
| [`remove_field(self)`](/slides/python-net/sv/aspose.slides/portion/remove_field/#) | Konverterar detta fältavsnitt till ett enkelt avsnitt. |
| [`get_rect(self)`](/slides/python-net/sv/aspose.slides/portion/get_rect/#) | Hämtar koordinater för rektangeln som begränsar avsnittet. Rektangeln inkluderar alla rader av<br/>             text i avsnittet, inklusive tomma. |
| [`get_coordinates(self)`](/slides/python-net/sv/aspose.slides/portion/get_coordinates/#) | Hämtar koordinater för avsnittets början. X-koordinaten för punkten representerar avsnittets början från det första tecknet inklusive vänstersida. Y-koordinaten <br/>            inkluderar översidan. |

### Se också
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)