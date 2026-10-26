---
title: StringChartValue class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/stringchartvalue/
---
## StringChartValue klass

Represent string value which can be stored in pptx presentation document in two ways:
            1) in cell/cells of workbook related to chart;
            2) as literal value.

**Arv:**[`StringChartValue`](/slides/python-net/sv/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/sv/aspose.slides.charts/basechartvalue)

The StringChartValue type exposes the following members:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`data_source_type`](/slides/python-net/sv/aspose.slides.charts/stringchartvalue/data_source_type/) | Anger om AsCell, AsCells, AsLiteralString eller AsLiteralDouble <br/>            property is actual i efterföljare. Med andra ord anger den typen <br/>            av värde för Data property.<br/>            Läs/skriv [`DataSourceType`](/slides/python-net/sv/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/sv/aspose.slides.charts/stringchartvalue/data/) | Returnerar eller sätter Data-objektet.<br/>            Läs/skriv **any**. |
| [`as_cells`](/slides/python-net/sv/aspose.slides.charts/stringchartvalue/as_cells/) | Tilldelning av nullvärde är inte tillåtet.<br/>            Returnerat värde är alltid inte None.<br/>            Läs/skriv [`IChartCellCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/sv/aspose.slides.charts/stringchartvalue/as_literal_string/) | Returnerar eller sätter värdet som literal string.<br/>            Läs/skriv **str**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/sv/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | Sätter värdet från angiven cell. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/sv/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | Om DataSourceType property är DataSourceType.Worksheet så returnerar denna metod adressen till cellerna i arbetsboken som representerar strängdata. Annars returneras en tom sträng. |


### Se även
* klass [`BaseChartValue`](/slides/python-net/sv/aspose.slides.charts/basechartvalue)
* klass [`StringChartValue`](/slides/python-net/sv/aspose.slides.charts/stringchartvalue)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)