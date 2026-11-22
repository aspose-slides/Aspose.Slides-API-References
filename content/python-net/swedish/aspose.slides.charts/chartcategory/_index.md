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

| Property | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/sv/aspose.slides.charts/chartcategory/use_cell/) | Om true då är AsCell-egenskapen aktuell. Med andra ord används arbetsbladet för <br/>            lagring av kategori (detta fall stödjer en flernivåkategori).<br/>            Om false då är AsLiteral-egenskapen aktuell. Med andra ord används arbetsbladet INTE för <br/>            lagring av kategori (och detta fall stödjer inte flernivåkategorier).<br/>            Skrivskyddad **bool**. |
| [`as_cell`](/slides/python-net/sv/aspose.slides.charts/chartcategory/as_cell/) | Returnerar eller anger IChartDataCell-objektet.<br/>            Om kategorin är flernivå används IChartDataCell-objekt för nivå "0".<br/>            Läs/skriv [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/sv/aspose.slides.charts/chartcategory/as_literal/) | Returnerar eller anger AsLiteral-objektet.<br/>            Läs/skriv **any**. |
| [`value`](/slides/python-net/sv/aspose.slides.charts/chartcategory/value/) | Om UseCell är true då representerar denna egenskap AsCell.Value-egenskapen.<br/>            Om UseCell är false då representerar den här egenskapen AsLiteral-egenskapen.<br/>            Läs/skriv **any**. |
| [`grouping_levels`](/slides/python-net/sv/aspose.slides.charts/chartcategory/grouping_levels/) | Hanterad behållare för värdena i diagramkategorins grupperingnivåer.<br/>            Flernivåkategori innehåller mer än en grupperingnivå.<br/>            Indexering av grupperingnivåer är nollbaserad.<br/>            Skrivskyddad [`IChartCategoryLevelsManager`](/slides/python-net/sv/aspose.slides.charts/ichartcategorylevelsmanager). |
| [`cached_value`](/slides/python-net/sv/aspose.slides.charts/chartcategory/cached_value/) | Hämtar det cachade värdet för en diagramkategori.<br/>            Skrivskyddad [`ICachedChartValue`](/slides/python-net/sv/aspose.slides.charts/icachedchartvalue). |

## Metoder

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/sv/aspose.slides.charts/chartcategory/remove/#) | Tar bort kategori från diagrammet. |


### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)