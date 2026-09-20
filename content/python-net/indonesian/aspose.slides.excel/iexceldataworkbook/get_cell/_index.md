---
title: get_cell method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.excel/iexceldataworkbook/get_cell/
weight: 10
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Mengambil sebuah sel dari lembar kerja yang ditentukan menggunakan indeksnya dan nama sel bergaya Excel (mis., "B2").

### Mengembalikan

Sel pada lokasi yang ditentukan.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| worksheet_index | **int** | Indeks berbasis nol dari lembar kerja. |
| cell_name | **str** | Referensi sel bergaya Excel (mis., "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Mengambil sebuah sel dari lembar kerja yang ditentukan menggunakan nama sel bergaya Excel (mis., "B2").

### Mengembalikan

Sel pada lokasi yang ditentukan.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| worksheet_name | **str** | Nama lembar kerja. |
| cell_name | **str** | Referensi sel bergaya Excel (mis., "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Mengambil sebuah sel dari lembar kerja yang ditentukan menggunakan indeksnya dan koordinat sel.

### Mengembalikan

Sel pada lokasi yang ditentukan.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| worksheet_index | **int** | Indeks berbasis nol dari lembar kerja. |
| row | **int** | Indeks baris berbasis nol dari sel. |
| column | **int** | Indeks kolom berbasis nol dari sel. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Mengambil sebuah sel dari lembar kerja yang ditentukan menggunakan namanya dan koordinat sel.

### Mengembalikan

Sel pada lokasi yang ditentukan.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| worksheet_name | **str** | Nama lembar kerja. |
| row | **int** | Indeks baris berbasis nol dari sel. |
| column | **int** | Indeks kolom berbasis nol dari sel. |



### Lihat Juga
* kelas [`IExcelDataCell`](/slides/python-net/id/aspose.slides.excel/iexceldatacell)
* kelas [`IExcelDataWorkbook`](/slides/python-net/id/aspose.slides.excel/iexceldataworkbook)
* modul [`aspose.slides.excel`](/slides/python-net/id/aspose.slides.excel)
* pustaka [`Aspose.Slides`](/slides/python-net)