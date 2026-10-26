---
title: StringChartValue class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/stringchartvalue/
---
## StringChartValue klasse

Stelt een tekenreekswaarde voor die in een pptx-presentatiedocument op twee manieren kan worden opgeslagen:
1) in cel/cellen van de werkmap die aan de grafiek gerelateerd is;
2) als letterlijke waarde.

**Inheritance:**[`StringChartValue`](/slides/python-net/nl/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/nl/aspose.slides.charts/basechartvalue)

Het type StringChartValue geeft de volgende leden weer:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`data_source_type`](/slides/python-net/nl/aspose.slides.charts/stringchartvalue/data_source_type/) | Geeft aan of de AsCell-, AsCells-, AsLiteralString- of AsLiteralDouble-eigenschap daadwerkelijk aanwezig is in afstammelingen. Met andere woorden specificeert het het type van de waarde van de Data-eigenschap.<br/>            Read/write [`DataSourceType`](/slides/python-net/nl/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/nl/aspose.slides.charts/stringchartvalue/data/) | Retourneert of stelt Data-object in.<br/>            Read/write **any**. |
| [`as_cells`](/slides/python-net/nl/aspose.slides.charts/stringchartvalue/as_cells/) | Toewijzen van null-waarde is niet toegestaan.<br/>            Geretourneerde waarde is altijd niet None.<br/>            Read/write [`IChartCellCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/nl/aspose.slides.charts/stringchartvalue/as_literal_string/) | Retourneert of stelt de waarde in als letterlijke tekenreeks.<br/>            Read/write **str**. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/nl/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | Stelt de waarde in vanuit opgegeven cel. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/nl/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | Als de eigenschap DataSourceType gelijk is aan DataSourceType.Worksheet, retourneert deze methode het adres<br/>            van de cellen in de werkmap die de tekenreeksgegevens vertegenwoordigen. Anders retourneer<br/>            een lege tekenreeks. |

### Zie ook
* klasse [`BaseChartValue`](/slides/python-net/nl/aspose.slides.charts/basechartvalue)
* klasse [`StringChartValue`](/slides/python-net/nl/aspose.slides.charts/stringchartvalue)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)