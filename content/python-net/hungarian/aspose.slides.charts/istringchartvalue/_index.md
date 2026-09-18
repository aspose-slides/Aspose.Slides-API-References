---
title: IStringChartValue class
second_title: Aspose.Slides for Python a .NET API referenciához
description: 
type: docs
url: /hu/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue osztály

Képviseli a karakterlánc értékét, amely két módon tárolható pptx prezentációs dokumentumban:
1) a diagramhoz kapcsolódó munkafüzet cella/celláiban;
2) literális értékként.

Az IStringChartValue típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`as_literal_string`](/slides/python-net/hu/aspose.slides.charts/istringchartvalue/as_literal_string/) | Visszaadja vagy beállítja a literális karakterláncot, ha a DataSourceType tulajdonság értéke DataSourceType.StringLiterals.<br/>            Olvasás/írás **str**. |
| [`as_cells`](/slides/python-net/hu/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [`data_source_type`](/slides/python-net/hu/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [`data`](/slides/python-net/hu/aspose.slides.charts/istringchartvalue/data/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`to_string(self)`](/slides/python-net/hu/aspose.slides.charts/istringchartvalue/to_string/#) | Visszaadja a karakterlánc ábrázolását. |
| [`set_from_one_cell(self, cell)`](/slides/python-net/hu/aspose.slides.charts/istringchartvalue/set_from_one_cell/#ichartdatacell) | Beállítja az értéket a megadott cellából. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/hu/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | Ha a DataSourceType tulajdonság értéke DataSourceType.Worksheet, akkor ez a metódus visszaadja a cellák címét<br/>            a munkafüzetben, amelyek a karakterlánc adatot képviselik. Egyébként<br/>            üres karakterláncot ad vissza. |

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)