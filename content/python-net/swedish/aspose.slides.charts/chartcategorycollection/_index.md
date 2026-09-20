---
title: ChartCategoryCollection class
second_title: Aspose.Slides for Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection klass

Representerar en samling av [`ChartCategory`](/slides/python-net/sv/aspose.slides.charts/chartcategory)

Typen ChartCategoryCollection exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`use_cells`](/slides/python-net/sv/aspose.slides.charts/chartcategorycollection/use_cells/) | Om true används arbetsblad för att lagra kategorier (detta fall stöder flernivåkategorier).<br/>            Om false används INTE arbetsblad för att lagra värden (och detta fall stöder inte en <br/>            flernivåkategorier).<br/>            Läs/skriv **bool**. |
| [`grouping_level_count`](/slides/python-net/sv/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | Returnerar antalet nivåer för kategorigruppering som används.<br/>            Är mer än ett för flernivåkategorier.<br/>            Skrivskyddad **int**. |

Hämtar elementet på det angivna indexet.

## Indexer

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/sv/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | Om kategorin finns i samlingen, returneras den. Annars skapas en ny diagramkategori från <br/>            [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell) och läggs till i samlingen. |
| [`add(self, value)`](/slides/python-net/sv/aspose.slides.charts/chartcategorycollection/add/#any) | Skapar en ny [`ChartCategory`](/slides/python-net/sv/aspose.slides.charts/chartcategory) från värdet och lägger till den i samlingen. |
| [`index_of(self, value)`](/slides/python-net/sv/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | Söker efter den angivna [`ChartCategory`](/slides/python-net/sv/aspose.slides.charts/chartcategory) och returnerar det nollbaserade indexet för den första förekomsten i hela samlingen. |
| [`remove(self, value)`](/slides/python-net/sv/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | Tar bort det angivna värdet. |
| [`remove_at(self, index)`](/slides/python-net/sv/aspose.slides.charts/chartcategorycollection/remove_at/#int) | Tar bort elementet på angivet index. |
| [`clear(self)`](/slides/python-net/sv/aspose.slides.charts/chartcategorycollection/clear/#) | Tar bort alla element från samlingen. |

### Se också
* klass [`ChartCategory`](/slides/python-net/sv/aspose.slides.charts/chartcategory)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)