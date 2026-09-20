---
title: IChartCategoryCollection class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection klass

Representerar samling av [`IChartCategory`](/slides/python-net/sv/aspose.slides.charts/ichartcategory)

Typen IChartCategoryCollection exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`use_cells`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection/use_cells/) | Om sant används kalkylbladet för att lagra kategorier (detta fall stödjer flernivåkategorier).<br/>            Om falskt används kalkylbladet INTE för att lagra värden (och detta fall stödjer inte <br/>            flernivåkategorier).<br/>            Läs/skriv **bool**. |
| [`grouping_level_count`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | Returnerar antalet nivåer för kategorigruppering som används.<br/>            Är mer än ett för flernivåkategorier.<br/>            Skrivskyddad **int**. |

Hämtar elementet på angivet index.

## Indexator

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | Om kategorin finns i samlingen, returnera den. Annars skapas en ny diagramkategori från <br/>            [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell) och läggs till i samlingen. |
| [`add(self, value)`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection/add/#any) | Skapar ny [`IChartCategory`](/slides/python-net/sv/aspose.slides.charts/ichartcategory) från värdet och lägger till den i samlingen. |
| [`index_of(self, value)`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | Söker efter den angivna [`IChartCategory`](/slides/python-net/sv/aspose.slides.charts/ichartcategory) och returnerar det nollbaserade indexet för den första förekomsten i hela samlingen |
| [`remove(self, value)`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | Tar bort det angivna värdet. |
| [`remove_at(self, index)`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | Tar bort elementet på det givna indexet. |
| [`clear(self)`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection/clear/#) | Tar bort alla element från samlingen. |

### Se även
* klass [`IChartCategory`](/slides/python-net/sv/aspose.slides.charts/ichartcategory)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)