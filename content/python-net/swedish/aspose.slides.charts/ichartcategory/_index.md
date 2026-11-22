---
title: IChartCategory class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartcategory/
---
## IChartCategory klass

Representerar diagramkategorier.

IChartCategory-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`use_cell`](/slides/python-net/sv/aspose.slides.charts/ichartcategory/use_cell/) | Om true är då egenskapen AsCell aktuell. Med andra ord används arbetsbladet för att lagra kategori (detta fall stöder en flernivåkategori).<br/>            Om false är då egenskapen AsLiteral aktuell. Med andra ord används arbetsbladet INTE för att lagra kategori (och detta fall stöder inte flernivåkategorier).<br/>            Skrivskyddad **bool**. |
| [`as_cell`](/slides/python-net/sv/aspose.slides.charts/ichartcategory/as_cell/) | Returnerar eller sätter IChartDataCell-objekt.<br/>            Om kategorin är flernivå används IChartDataCell-objekt för nivå "0".<br/>            Read/write [`IChartDataCell`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/sv/aspose.slides.charts/ichartcategory/as_literal/) | Returnerar eller sätter AsLiteral om UseCell är false.<br/>            Read/write **any**. |
| [`value`](/slides/python-net/sv/aspose.slides.charts/ichartcategory/value/) | Om UseCell är true representerar denna egenskap AsCell.Value-egenskapen.<br/>            Om UseCell är false representerar denna egenskap AsLiteral-egenskapen.<br/>            Read/write **any**. |
| [`cached_value`](/slides/python-net/sv/aspose.slides.charts/ichartcategory/cached_value/) | Hämtar det cachade värdet för en diagramkategori.<br/>            Read-only [`ICachedChartValue`](/slides/python-net/sv/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/sv/aspose.slides.charts/ichartcategory/grouping_levels/) | Hanterad behållare för värdena i diagramkategorins grupperingnivåer.<br/>            Flernivåkategori innehåller mer än en grupperingnivå.<br/>            Indexeringen för grupperingnivåer är nollbaserad.<br/>            Read-only [`IChartCategoryLevelsManager`](/slides/python-net/sv/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`remove(self)`](/slides/python-net/sv/aspose.slides.charts/ichartcategory/remove/#) | Tar bort kategori från diagram. |

### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)