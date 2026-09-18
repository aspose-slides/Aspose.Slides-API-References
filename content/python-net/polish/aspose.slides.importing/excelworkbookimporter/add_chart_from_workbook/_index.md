---
title: add_chart_from_workbook method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
Pobiera wykres z określonego skoroszytu Excel i dodaje go na koniec podanej kolekcji kształtów w określonych współrzędnych.

### Returns

Wykres, który został dodany do kolekcji kształtów.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection) | Kolekcja kształtów, do której wykres zostanie dodany. |
| x | **float** | Współrzędna X określająca położenie wykresu. |
| y | **float** | Współrzędna Y określająca położenie wykresu. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/pl/aspose.slides.excel/iexceldataworkbook) | Skoroszyt Excel. |
| worksheet_name | **str** | Nazwa arkusza zawierającego wykres. |
| chart_index | **int** | Indeks wykresu zaczynający się od zera, który ma zostać wstawiony. <br/><br/>            Ten indeks można uzyskać przy użyciu metody **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste**. |
| embed_all_workbook | **bool** | Jeśli `true`, cały skoroszyt zostanie osadzony w wykresie; <br/><br/>            jeśli `false`, zostaną osadzone tylko dane wykresu. |

### Exceptions

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucony, gdy którykolwiek wymagany parametr jest None, pusty lub gdy wykres nie zostanie znaleziony w skoroszycie. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
Pobiera wykres z określonego skoroszytu Excel i dodaje go na koniec podanej kolekcji kształtów w określonych współrzędnych.

### Returns

Wykres, który został dodany do kolekcji kształtów.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection) | Kolekcja kształtów, do której wykres zostanie dodany. |
| x | **float** | Współrzędna X określająca położenie wykresu. |
| y | **float** | Współrzędna Y określająca położenie wykresu. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/pl/aspose.slides.excel/iexceldataworkbook) | Skoroszyt Excel. |
| worksheet_name | **str** | Nazwa arkusza zawierającego wykres. |
| chart_name | **str** | Nazwa wykresu, który ma zostać dodany. |
| embed_all_workbook | **bool** | Jeśli `true`, cały skoroszyt zostanie osadzony w wykresie; <br/><br/>            jeśli `false`, zostaną osadzone tylko dane wykresu. |

### Exceptions

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucony, gdy którykolwiek wymagany parametr jest None, pusty lub gdy wykres nie zostanie znaleziony w skoroszycie. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
Pobiera wykres z określonego skoroszytu Excel i dodaje go na koniec podanej kolekcji kształtów w określonych współrzędnych.

### Returns

Wykres, który został dodany do kolekcji kształtów.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection) | Kolekcja kształtów, do której wykres zostanie dodany. |
| x | **float** | Współrzędna X określająca położenie wykresu. |
| y | **float** | Współrzędna Y określająca położenie wykresu. |
| workbook_stream | **io.RawIOBase** | Strumień zawierający dane skoroszytu. |
| worksheet_name | **str** | Nazwa arkusza zawierającego wykres. |
| chart_name | **str** | Nazwa wykresu, który ma zostać dodany. |
| embed_all_workbook | **bool** | Jeśli `true`, cały skoroszyt zostanie osadzony w wykresie; <br/><br/>            jeśli `false`, zostaną osadzone tylko dane wykresu. |

### Exceptions

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucony, gdy którykolwiek wymagany parametr jest None, pusty lub gdy wykres nie zostanie znaleziony w skoroszycie. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Rzucony, gdy dane wejściowe są w nieobsługiwanym formacie. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
Pobiera wykres z określonego skoroszytu Excel i dodaje go na koniec podanej kolekcji kształtów w określonych współrzędnych.

### Returns

Wykres, który został dodany do kolekcji kształtów.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection) | Kolekcja kształtów, do której wykres zostanie dodany. |
| x | **float** | Współrzędna X określająca położenie wykresu. |
| y | **float** | Współrzędna Y określająca położenie wykresu. |
| workbook_path | **str** | Ścieżka do pliku skoroszytu zawierającego wykres. |
| worksheet_name | **str** | Nazwa arkusza zawierającego wykres. |
| chart_name | **str** | Nazwa wykresu, który ma zostać dodany. |
| embed_workbook | **bool** | Jeśli `true`, skoroszyt zostanie osadzony w wykresie; <br/><br/>            jeśli `false`, wykres będzie odwoływał się do zewnętrznego skoroszytu. |

### Exceptions

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucony, gdy którykolwiek wymagany parametr jest None, pusty lub gdy wykres nie zostanie znaleziony w skoroszycie. |
| **RuntimeError(Proxy error(IOException))** | Rzucony, gdy podczas dostępu do pliku wystąpi błąd I/O. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Rzucony, gdy dane wejściowe są w nieobsługiwanym formacie. |



### See Also
* klasa [`ExcelWorkbookImporter`](/slides/python-net/pl/aspose.slides.importing/excelworkbookimporter)
* klasa [`IExcelDataWorkbook`](/slides/python-net/pl/aspose.slides.excel/iexceldataworkbook)
* klasa [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection)
* moduł [`aspose.slides.importing`](/slides/python-net/pl/aspose.slides.importing)
* biblioteka [`Aspose.Slides`](/slides/python-net)