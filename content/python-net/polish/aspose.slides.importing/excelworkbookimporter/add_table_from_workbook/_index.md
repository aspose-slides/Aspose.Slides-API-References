---
title: add_table_from_workbook method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
Pobiera tabelę z określonego skoroszytu Excel i dodaje ją na koniec podanej kolekcji kształtów w podanych współrzędnych.

### Returns

Tabela, która została dodana do kolekcji kształtów.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection) | Kolekcja kształtów, do której tabela zostanie dodana. |
| x | **float** | Współrzędna X służąca do pozycjonowania tabeli. |
| y | **float** | Współrzędna Y służąca do pozycjonowania tabeli. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/pl/aspose.slides.excel/iexceldataworkbook) | Skoroszyt Excel. |
| worksheet_name | **str** | Nazwa arkusza zawierającego tabelę. |
| cell_range | **str** | Zakres komórek definiujący tabelę (na przykład "A1:D10"). |

### Exceptions

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, gdy którykolwiek wymagany parametr jest None lub pusty, lub gdy określony arkusz lub zakres komórek jest nieprawidłowy. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Rzucany, gdy dane wejściowe są w nieobsługiwanym formacie. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
Pobiera tabelę z określonego pliku skoroszytu Excel i dodaje ją na koniec podanej kolekcji kształtów w podanych współrzędnych.

### Returns

Tabela, która została dodana do kolekcji kształtów.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection) | Kolekcja kształtów, do której tabela zostanie dodana. |
| x | **float** | Współrzędna X służąca do pozycjonowania tabeli. |
| y | **float** | Współrzędna Y służąca do pozycjonowania tabeli. |
| workbook_path | **str** | Ścieżka do pliku skoroszytu Excel. |
| worksheet_name | **str** | Nazwa arkusza zawierającego tabelę. |
| cell_range | **str** | Zakres komórek definiujący tabelę (na przykład "A1:D10"). |

### Exceptions

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, gdy którykolwiek wymagany parametr jest None lub pusty, lub gdy określony arkusz lub zakres komórek jest nieprawidłowy. |
| **RuntimeError(Proxy error(IOException))** | Rzucany, gdy podczas dostępu do pliku skoroszytu wystąpi błąd I/O. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Rzucany, gdy dane wejściowe są w nieobsługiwanym formacie. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
Pobiera tabelę z określonego pliku skoroszytu Excel i dodaje ją na koniec podanej kolekcji kształtów w podanych współrzędnych.

### Returns

Tabela, która została dodana do kolekcji kształtów.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection) | Kolekcja kształtów, do której tabela zostanie dodana. |
| x | **float** | Współrzędna X służąca do pozycjonowania tabeli. |
| y | **float** | Współrzędna Y służąca do pozycjonowania tabeli. |
| workbook_stream | **io.RawIOBase** | Strumień zawierający dane skoroszytu. |
| worksheet_name | **str** | Nazwa arkusza zawierającego tabelę. |
| cell_range | **str** | Zakres komórek definiujący tabelę (na przykład "A1:D10"). |

### Exceptions

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, gdy którykolwiek wymagany parametr jest None lub pusty, lub gdy określony arkusz lub zakres komórek jest nieprawidłowy. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Rzucany, gdy dane wejściowe są w nieobsługiwanym formacie. |



### See Also
* klasa [`ExcelWorkbookImporter`](/slides/python-net/pl/aspose.slides.importing/excelworkbookimporter)
* klasa [`IExcelDataWorkbook`](/slides/python-net/pl/aspose.slides.excel/iexceldataworkbook)
* klasa [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection)
* klasa [`ITable`](/slides/python-net/pl/aspose.slides/itable)
* moduł [`aspose.slides.importing`](/slides/python-net/pl/aspose.slides.importing)
* biblioteka [`Aspose.Slides`](/slides/python-net)