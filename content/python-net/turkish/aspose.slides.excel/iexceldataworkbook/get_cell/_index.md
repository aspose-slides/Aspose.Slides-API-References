---
title: get_cell method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.excel/iexceldataworkbook/get_cell/
weight: 10
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Belirtilen çalışma sayfasından, dizini ve Excel tarzı hücre adı (örn. "B2") kullanarak bir hücre alır.

### Döndürür

Belirtilen konumdaki hücre.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| worksheet_index | **int** | Çalışma sayfasının sıfır tabanlı indeksi. |
| cell_name | **str** | Excel tarzı hücre referansı (örn. "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Belirtilen çalışma sayfasından, Excel tarzı hücre adı (örn. "B2") kullanarak bir hücre alır.

### Döndürür

Belirtilen konumdaki hücre.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| worksheet_name | **str** | Çalışma sayfasının adı. |
| cell_name | **str** | Excel tarzı hücre referansı (örn. "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Belirtilen çalışma sayfasından, dizini ve hücre koordinatlarını kullanarak bir hücre alır.

### Döndürür

Belirtilen konumdaki hücre.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| worksheet_index | **int** | Çalışma sayfasının sıfır tabanlı indeksi. |
| row | **int** | Hücrenin sıfır tabanlı satır indeksi. |
| column | **int** | Hücrenin sıfır tabanlı sütun indeksi. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Belirtilen çalışma sayfasından, adı ve hücre koordinatlarını kullanarak bir hücre alır.

### Döndürür

Belirtilen konumdaki hücre.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| worksheet_name | **str** | Çalışma sayfasının adı. |
| row | **int** | Hücrenin sıfır tabanlı satır indeksi. |
| column | **int** | Hücrenin sıfır tabanlı sütun indeksi. |



### Ayrıca Bakınız
* sınıf [`IExcelDataCell`](/slides/python-net/tr/aspose.slides.excel/iexceldatacell)
* sınıf [`IExcelDataWorkbook`](/slides/python-net/tr/aspose.slides.excel/iexceldataworkbook)
* modül [`aspose.slides.excel`](/slides/python-net/tr/aspose.slides.excel)
* kütüphane [`Aspose.Slides`](/slides/python-net)