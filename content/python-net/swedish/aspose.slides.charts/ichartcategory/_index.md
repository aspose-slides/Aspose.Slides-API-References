---
title: IChartCategory class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartcategory/
---
## IChartCategory klass

Representerar diagramkategorier.

Typen IChartCategory exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/sv/aspose.slides.charts/ichartcategory/use_cell/) | Om true är AsCell-egenskapen aktuell. Med andra ord används arbetsbladet för <br/>            lagring av kategori (detta fall stödjer en flernivåkategori).<br/>            Om false är AsLiteral-egenskapen aktuell. Med andra ord används arbetsbladet INTE för <br/>            lagring av kategori (och detta fall stödjer inte flernivåkategorier).<br/>            Skrivskyddad **bool**. |
| [`as_cell`](/slides/python-net/sv/aspose.slides.charts/ichartcategory/as_cell/) | Returnerar eller anger IChartDataCell-objekt.<br/>            Om kategori är flernivå används IChartDataCell-objekt för nivå "0".<br/>            Läs/skriv [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/sv/aspose.slides.charts/ichartcategory/as_literal/) | Returnerar eller anger AsLiteral om UseCell är false.<br/>            Läs/skriv **any**. |
| [`value`](/slides/python-net/sv/aspose.slides.charts/ichartcategory/value/) | Om UseCell är true representerar denna egenskap AsCell.Value-egenskapen.<br/>            Om UseCell är false representerar denna egenskap AsLiteral-egenskapen.<br/>            Läs/skriv **any**. |
| [`grouping_levels`](/slides/python-net/sv/aspose.slides.charts/ichartcategory/grouping_levels/) | Hanterad behållare för värdena i diagramkategori-grupperingsnivåerna.<br/>            Flernivåkategori innehåller mer än en grupperingsnivå.<br/>            Indexering av grupperingsnivåer är nollbaserad.<br/>            Skrivskyddad [`IChartCategoryLevelsManager`](/slides/python-net/sv/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metoder

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/sv/aspose.slides.charts/ichartcategory/remove/#) | Tar bort kategori från diagrammet. |


### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)