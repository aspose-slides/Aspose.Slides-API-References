---
title: IPortion class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iportion/
---
## IPortion klass

Representerar en del av text i ett textstycke.

IPortion-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`portion_format`](/slides/python-net/sv/aspose.slides/iportion/portion_format/) | Returnerar formateringsobjekt som innehåller explicit angivna formateringsegenskaper för textdelen utan någon ärvning tillämpad.<br/>            Endast läsning [`IPortionFormat`](/slides/python-net/sv/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/sv/aspose.slides/iportion/text/) | Hämtar eller anger den enkla texten i en del.<br/>            Läs/skriv **str**. |
| [`field`](/slides/python-net/sv/aspose.slides/iportion/field/) | Returnerar ett fält för denna del.<br/>            Endast läsning [`IField`](/slides/python-net/sv/aspose.slides/ifield). |
| [`slide`](/slides/python-net/sv/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/iportion/presentation/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/sv/aspose.slides/iportion/add_field/#ifieldtype) | Konverterar denna del till det automatiskt uppdaterade fältet. |
| [`add_field(self, internal_string)`](/slides/python-net/sv/aspose.slides/iportion/add_field/#str) | Konverterar denna del till det automatiskt uppdaterade fältet. |
| [`remove_field(self)`](/slides/python-net/sv/aspose.slides/iportion/remove_field/#) | Konverterar detta fältavsnitt till den enkla delen. |
| [`get_rect(self)`](/slides/python-net/sv/aspose.slides/iportion/get_rect/#) | Hämtar koordinater för den rektangel som avgränsar delen. Rektangeln inkluderar alla rader av<br/>             text i delen, inklusive tomma. |
| [`get_coordinates(self)`](/slides/python-net/sv/aspose.slides/iportion/get_coordinates/#) | Hämtar koordinater för början av delen. X-koordinaten för punkten representerar delens början från det första tecknet inklusive vänstersidigt avstånd. Y-koordinaten <br/>            inkluderar toppsidigt avstånd. |

### Se också
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)