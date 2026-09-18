---
title: StringChartValue class
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/stringchartvalue/
---
## StringChartValue osztály

Represent string value which can be stored in pptx presentation document in two ways:
            1) in cell/cells of workbook related to chart;
            2) as literal value.

**Öröklődés:**[`StringChartValue`](/slides/python-net/hu/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/hu/aspose.slides.charts/basechartvalue)

The StringChartValue type exposes the following members:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`data_source_type`](/slides/python-net/hu/aspose.slides.charts/stringchartvalue/data_source_type/) | Megadja, hogy az AsCell, AsCells, AsLiteralString vagy AsLiteralDouble <br/>            tulajdonság valóban létezik-e a leszármazottakban. Más szóval meghatározza a Data <br/>            tulajdonság értékének típusát.<br/>            Olvasás/írás [`DataSourceType`](/slides/python-net/hu/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/hu/aspose.slides.charts/stringchartvalue/data/) | Visszaadja vagy beállítja a Data objektumot.<br/>            Olvasás/írás **any**. |
| [`as_cells`](/slides/python-net/hu/aspose.slides.charts/stringchartvalue/as_cells/) | Null érték hozzárendelése nem megengedett.<br/>            A visszaadott érték mindig nem None.<br/>            Olvasás/írás [`IChartCellCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/hu/aspose.slides.charts/stringchartvalue/as_literal_string/) | Visszaadja vagy beállítja az értéket literális karakterláncként.<br/>            Olvasás/írás **str**. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/hu/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | Beállítja az értéket a megadott cellából. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/hu/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | Ha a DataSourceType tulajdonság értéke DataSourceType.Worksheet, akkor ez a metódus a munkafüzetben a karakterlánc adatot képviselő cellák címét adja vissza.<br/>            Egyébként üres karakterláncot ad vissza. |

### Lásd még
* osztály [`BaseChartValue`](/slides/python-net/hu/aspose.slides.charts/basechartvalue)
* osztály [`StringChartValue`](/slides/python-net/hu/aspose.slides.charts/stringchartvalue)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)