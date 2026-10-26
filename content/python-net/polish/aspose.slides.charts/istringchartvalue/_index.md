---
title: IStringChartValue class
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue klasa

Reprezentuje wartość ciągu znaków, która może być przechowywana w dokumencie prezentacji pptx na dwa sposoby:
            1) w komórce/komórkach skoroszytu powiązanego z wykresem;
            2) jako wartość literałowa.

Typ IStringChartValue udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`as_literal_string`](/slides/python-net/pl/aspose.slides.charts/istringchartvalue/as_literal_string/) | Zwraca lub ustawia literałowy ciąg znaków, jeśli właściwość DataSourceType ma wartość DataSourceType.StringLiterals.<br/>            Read/write **str**. |
| [`as_cells`](/slides/python-net/pl/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [`data_source_type`](/slides/python-net/pl/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [`data`](/slides/python-net/pl/aspose.slides.charts/istringchartvalue/data/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`to_string(self)`](/slides/python-net/pl/aspose.slides.charts/istringchartvalue/to_string/#) | Zwraca reprezentację ciągu znaków. |
| [`set_from_one_cell(self, cell)`](/slides/python-net/pl/aspose.slides.charts/istringchartvalue/set_from_one_cell/#ichartdatacell) | Ustawia wartość z określonej komórki. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/pl/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | Jeśli właściwość DataSourceType ma wartość DataSourceType.Worksheet, wtedy ta metoda zwraca adres<br/>            komórek w arkuszu kalkulacyjnym, które reprezentują dane ciągu znaków. W przeciwnym razie zwraca<br/>            pusty ciąg znaków. |


### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)