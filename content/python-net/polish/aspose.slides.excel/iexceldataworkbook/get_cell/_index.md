---
title: get_cell method
second_title: Aspose.Slides dla Pythona poprzez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.excel/iexceldataworkbook/get_cell/
weight: 10
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Pobiera komórkę z określonego arkusza, używając jego indeksu i nazwy komórki w stylu Excel (np. "B2").

### Zwraca

Komórka w określonej lokalizacji.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| worksheet_index | **int** | Indeks arkusza zaczynający się od zera. |
| cell_name | **str** | Odwołanie do komórki w stylu Excel (np. "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Pobiera komórkę z określonego arkusza, używając nazwy komórki w stylu Excel (np. "B2").

### Zwraca

Komórka w określonej lokalizacji.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| worksheet_name | **str** | Nazwa arkusza. |
| cell_name | **str** | Odwołanie do komórki w stylu Excel (np. "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Pobiera komórkę z określonego arkusza, używając jego indeksu oraz współrzędnych komórki.

### Zwraca

Komórka w określonej lokalizacji.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| worksheet_index | **int** | Indeks arkusza zaczynający się od zera. |
| row | **int** | Indeks wiersza komórki zaczynający się od zera. |
| column | **int** | Indeks kolumny komórki zaczynający się od zera. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Pobiera komórkę z określonego arkusza, używając jego nazwy oraz współrzędnych komórki.

### Zwraca

Komórka w określonej lokalizacji.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| worksheet_name | **str** | Nazwa arkusza. |
| row | **int** | Indeks wiersza komórki zaczynający się od zera. |
| column | **int** | Indeks kolumny komórki zaczynający się od zera. |



### Zobacz także
* klasa [`IExcelDataCell`](/slides/python-net/pl/aspose.slides.excel/iexceldatacell)
* klasa [`IExcelDataWorkbook`](/slides/python-net/pl/aspose.slides.excel/iexceldataworkbook)
* moduł [`aspose.slides.excel`](/slides/python-net/pl/aspose.slides.excel)
* biblioteka [`Aspose.Slides`](/slides/python-net)