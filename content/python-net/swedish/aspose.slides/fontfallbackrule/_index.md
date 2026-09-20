---
title: FontFallBackRule class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/fontfallbackrule/
---
## FontFallBackRule klass

Representerar font fallback-regel

FontFallBackRule-typen exponerar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/sv/aspose.slides/fontfallbackrule/__init__/#int-int-str) | Skapar en ny instans. |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/sv/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | Skapar en ny instans. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`range_start_index`](/slides/python-net/sv/aspose.slides/fontfallbackrule/range_start_index/) | Hämtar första indexet för ett kontinuerligt unicode-område. |
| [`range_end_index`](/slides/python-net/sv/aspose.slides/fontfallbackrule/range_end_index/) | Hämtar sista indexet för ett kontinuerligt unicode-område. |
| [`count`](/slides/python-net/sv/aspose.slides/fontfallbackrule/count/) | Hämtar antalet teckensnitt som faktiskt definierats för intervallet.<br/>            Läs-endast **int**. |

Hämtar teckensnittets namn på det angivna indexet.  
Läs-endast [`IFontFallBackRule`](/slides/python-net/sv/aspose.slides/ifontfallbackrule).

## Indexator

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides/fontfallbackrule/__getitem__/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/sv/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | Lägger till ett nytt teckensnitt till listan med FallBack-teckensnitt. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/sv/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | Lägger till nya teckensnitt till listan med FallBack-teckensnitt. |
| [`to_array(self)`](/slides/python-net/sv/aspose.slides/fontfallbackrule/to_array/#) | Skapar och returnerar en array med alla FallBack-teckensnitt för den här regeln. |
| [`to_array(self, start_index, count)`](/slides/python-net/sv/aspose.slides/fontfallbackrule/to_array/#int-int) | Skapar och returnerar en array med alla FallBack-teckensnitt från det angivna intervallet i listan. |
| [`clear(self)`](/slides/python-net/sv/aspose.slides/fontfallbackrule/clear/#) | Tar bort alla teckensnitt från listan. |
| [`remove(self, font_name)`](/slides/python-net/sv/aspose.slides/fontfallbackrule/remove/#str) | Tar bort den första förekomsten av ett specifikt FallBack-teckensnitt från listan. |
| [`remove_at(self, index)`](/slides/python-net/sv/aspose.slides/fontfallbackrule/remove_at/#int) | Tar bort FallBack-teckensnittet på det angivna indexet i listan. |
| [`index_of(self, font_name)`](/slides/python-net/sv/aspose.slides/fontfallbackrule/index_of/#str) | Returnerar ett index för den angivna regeln i samlingen. |

### Se även
* klass [`IFontFallBackRule`](/slides/python-net/sv/aspose.slides/ifontfallbackrule)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)