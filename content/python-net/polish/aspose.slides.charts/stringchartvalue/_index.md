---
title: StringChartValue class
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET - dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/stringchartvalue/
---
## StringChartValue klasa

Reprezentuje wartość tekstową, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby:
1) w komórce/komórkach skoroszytu powiązanego z wykresem;
2) jako wartość literałową.

**Dziedziczenie:**[`StringChartValue`](/slides/python-net/pl/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/pl/aspose.slides.charts/basechartvalue)

Typ StringChartValue udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`data_source_type`](/slides/python-net/pl/aspose.slides.charts/stringchartvalue/data_source_type/) | Określa, czy właściwość AsCell, AsCells, AsLiteralString lub AsLiteralDouble <br/> jest aktualna w klasach pochodnych. Innymi słowy określa typ <br/> wartości właściwości Data.<br/> Odczyt/zapis [`DataSourceType`](/slides/python-net/pl/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/pl/aspose.slides.charts/stringchartvalue/data/) | Zwraca lub ustawia obiekt Data.<br/> Odczyt/zapis **any**. |
| [`as_cells`](/slides/python-net/pl/aspose.slides.charts/stringchartvalue/as_cells/) | Przypisanie wartości null nie jest dozwolone.<br/> Zwracana wartość zawsze nie jest None.<br/> Odczyt/zapis [`IChartCellCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/pl/aspose.slides.charts/stringchartvalue/as_literal_string/) | Zwraca lub ustawia wartość jako łańcuch znakowy.<br/> Odczyt/zapis **str**. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/pl/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | Ustawia wartość z określonej komórki. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/pl/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | Jeśli właściwość DataSourceType ma wartość DataSourceType.Worksheet, to ta metoda zwraca adres <br/> komórek w skoroszycie, które reprezentują dane tekstowe. W przeciwnym razie zwraca <br/> pusty łańcuch znakowy. |

### Zobacz także
* klasa [`BaseChartValue`](/slides/python-net/pl/aspose.slides.charts/basechartvalue)
* klasa [`StringChartValue`](/slides/python-net/pl/aspose.slides.charts/stringchartvalue)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)