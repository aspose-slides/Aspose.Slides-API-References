---
title: ChartCategory class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartcategory/
---
## ChartCategory klass

Representerar diagramkategorier.

ChartCategory-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`use_cell`](/slides/python-net/sv/aspose.slides.charts/chartcategory/use_cell/) | Om true är sedan AsCell-egenskapen aktuell. Med andra ord används arbetsbladet för <br/>            lagring av kategori (detta fall stödjer en flernivåkategori).<br/>            Om false är sedan AsLiteral-egenskapen aktuell. Med andra ord används arbetsbladet INTE för <br/>            lagring av kategori (och detta fall stödjer inte flernivåkategorier).<br/>            Read-only **bool**. |
| [`as_cell`](/slides/python-net/sv/aspose.slides.charts/chartcategory/as_cell/) | Returnerar eller sätter IChartDataCell-objektet.<br/>            Om kategorin är flernivå används IChartDataCell-objektet för nivå "0".<br/>            Read/write [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/sv/aspose.slides.charts/chartcategory/as_literal/) | Returnerar eller sätter AsLiteral-objektet.<br/>            Read/write **any**. |
| [`value`](/slides/python-net/sv/aspose.slides.charts/chartcategory/value/) | Om UseCell är true representerar denna egenskap AsCell.Value-egenskapen.<br/>            Om UseCell är false representerar denna egenskap AsLiteral-egenskapen.<br/>            Read/write **any**. |
| [`grouping_levels`](/slides/python-net/sv/aspose.slides.charts/chartcategory/grouping_levels/) | Hanterad behållare för värdena på diagramkategorins gruppnivåer.<br/>            Flernivåkategori innehåller mer än en gruppnivå.<br/>            Indexering av gruppnivåer är nollbaserad.<br/>            Read-only [`IChartCategoryLevelsManager`](/slides/python-net/sv/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`remove(self)`](/slides/python-net/sv/aspose.slides.charts/chartcategory/remove/#) | Tar bort kategori från diagrammet. |

### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)