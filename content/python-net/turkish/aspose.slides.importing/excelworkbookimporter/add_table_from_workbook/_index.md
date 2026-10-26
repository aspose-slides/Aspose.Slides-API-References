---
title: add_table_from_workbook method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
Belirtilen Excel çalışma kitabından bir tablo alır ve verilen şekil koleksiyonunun sonuna belirtilen koordinatlarda ekler.

### Döndürür

Şekil koleksiyonuna eklenen tablo.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection) | Tabloyu ekleyecek şekil koleksiyonu. |
| x | **float** | Tabloyu konumlandırmak için X koordinatı. |
| y | **float** | Tabloyu konumlandırmak için Y koordinatı. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/tr/aspose.slides.excel/iexceldataworkbook) | Excel çalışma kitabı. |
| worksheet_name | **str** | Tabloyu içeren çalışma sayfasının adı. |
| cell_range | **str** | Tabloyu tanımlayan hücre aralığı (örneğin, "A1:D10"). |

### İstisnalar

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Gerekli bir parametre None veya boş olduğunda ya da belirtilen çalışma sayfası ya da hücre aralığı geçersiz olduğunda fırlatılır. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Giriş verileri desteklenmeyen bir formatta olduğunda fırlatılır. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
Belirtilen Excel çalışma kitabı dosyasından bir tablo alır ve verilen şekil koleksiyonunun sonuna belirtilen koordinatlarda ekler.

### Döndürür

Şekil koleksiyonuna eklenen tablo.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection) | Tabloyu ekleyecek şekil koleksiyonu. |
| x | **float** | Tabloyu konumlandırmak için X koordinatı. |
| y | **float** | Tabloyu konumlandırmak için Y koordinatı. |
| workbook_path | **str** | Excel çalışma kitabı dosyasının yolu. |
| worksheet_name | **str** | Tabloyu içeren çalışma sayfasının adı. |
| cell_range | **str** | Tabloyu tanımlayan hücre aralığı (örneğin, "A1:D10"). |

### İstisnalar

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Gerekli bir parametre None veya boş olduğunda ya da belirtilen çalışma sayfası ya da hücre aralığı geçersiz olduğunda fırlatılır. |
| **RuntimeError(Proxy error(IOException))** | Çalışma kitabı dosyasına erişilirken bir G/Ç hatası oluştuğunda fırlatılır. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Giriş verileri desteklenmeyen bir formatta olduğunda fırlatılır. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
Belirtilen Excel çalışma kitabı dosyasından bir tablo alır ve verilen şekil koleksiyonunun sonuna belirtilen koordinatlarda ekler.

### Döndürür

Şekil koleksiyonuna eklenen tablo.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection) | Tabloyu ekleyecek şekil koleksiyonu. |
| x | **float** | Tabloyu konumlandırmak için X koordinatı. |
| y | **float** | Tabloyu konumlandırmak için Y koordinatı. |
| workbook_stream | **io.RawIOBase** | Çalışma kitabı verilerini içeren bir akış. |
| worksheet_name | **str** | Tabloyu içeren çalışma sayfasının adı. |
| cell_range | **str** | Tabloyu tanımlayan hücre aralığı (örneğin, "A1:D10"). |

### İstisnalar

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Gerekli bir parametre None veya boş olduğunda ya da belirtilen çalışma sayfası ya da hücre aralığı geçersiz olduğunda fırlatılır. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Giriş verileri desteklenmeyen bir formatta olduğunda fırlatılır. |



### Ayrıca Bakınız
* sınıf [`ExcelWorkbookImporter`](/slides/python-net/tr/aspose.slides.importing/excelworkbookimporter)
* sınıf [`IExcelDataWorkbook`](/slides/python-net/tr/aspose.slides.excel/iexceldataworkbook)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* sınıf [`ITable`](/slides/python-net/tr/aspose.slides/itable)
* modül [`aspose.slides.importing`](/slides/python-net/tr/aspose.slides.importing)
* kütüphane [`Aspose.Slides`](/slides/python-net)