---
title: add_chart_from_workbook method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
Mengambil diagram dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

### Mengembalikan

Diagram yang ditambahkan ke koleksi shape.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Parameter | Type | Deskripsi |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection) | Koleksi shape tempat diagram akan ditambahkan. |
| x | **float** | Koordinat X untuk memposisikan diagram. |
| y | **float** | Koordinat Y untuk memposisikan diagram. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/id/aspose.slides.excel/iexceldataworkbook) | Workbook Excel. |
| worksheet_name | **str** | Nama lembar kerja yang berisi diagram. |
| chart_index | **int** | Indeks berbasis nol dari shape diagram yang akan disisipkan. <br/><br/>            Indeks ini dapat diperoleh menggunakan **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste** method. |
| embed_all_workbook | **bool** | Jika `true`, seluruh workbook akan disematkan dalam diagram; <br/><br/>            jika `false`, hanya data diagram yang akan disematkan. |

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan ketika ada parameter wajib yang None, kosong, atau ketika diagram tidak dapat ditemukan dalam workbook. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
Mengambil diagram dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

### Mengembalikan

Diagram yang ditambahkan ke koleksi shape.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parameter | Type | Deskripsi |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection) | Koleksi shape tempat diagram akan ditambahkan. |
| x | **float** | Koordinat X untuk memposisikan diagram. |
| y | **float** | Koordinat Y untuk memposisikan diagram. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/id/aspose.slides.excel/iexceldataworkbook) | Workbook Excel. |
| worksheet_name | **str** | Nama lembar kerja yang berisi diagram. |
| chart_name | **str** | Nama diagram yang akan ditambahkan. |
| embed_all_workbook | **bool** | Jika `true`, seluruh workbook akan disematkan dalam diagram; <br/><br/>            jika `false`, hanya data diagram yang akan disematkan. |

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan ketika ada parameter wajib yang None, kosong, atau ketika diagram tidak dapat ditemukan dalam workbook. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
Mengambil diagram dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

### Mengembalikan

Diagram yang ditambahkan ke koleksi shape.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parameter | Type | Deskripsi |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection) | Koleksi shape tempat diagram akan ditambahkan. |
| x | **float** | Koordinat X untuk memposisikan diagram. |
| y | **float** | Koordinat Y untuk memposisikan diagram. |
| workbook_stream | **io.RawIOBase** | Aliran yang berisi data workbook. |
| worksheet_name | **str** | Nama lembar kerja yang berisi diagram. |
| chart_name | **str** | Nama diagram yang akan ditambahkan. |
| embed_all_workbook | **bool** | Jika `true`, seluruh workbook akan disematkan dalam diagram; <br/><br/>            jika `false`, hanya data diagram yang akan disematkan. |

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan ketika ada parameter wajib yang None, kosong, atau ketika diagram tidak dapat ditemukan dalam workbook. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Dilemparkan ketika data input berada dalam format yang tidak didukung. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
Mengambil diagram dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

### Mengembalikan

Diagram yang ditambahkan ke koleksi shape.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Parameter | Type | Deskripsi |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection) | Koleksi shape tempat diagram akan ditambahkan. |
| x | **float** | Koordinat X untuk memposisikan diagram. |
| y | **float** | Koordinat Y untuk memposisikan diagram. |
| workbook_path | **str** | Jalur file ke workbook yang berisi diagram. |
| worksheet_name | **str** | Nama lembar kerja yang berisi diagram. |
| chart_name | **str** | Nama diagram yang akan ditambahkan. |
| embed_workbook | **bool** | Jika `true`, workbook akan disematkan dalam diagram; <br/><br/>            jika `false`, diagram akan menaut ke workbook eksternal. |

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan ketika ada parameter wajib yang None, kosong, atau ketika diagram tidak dapat ditemukan dalam workbook. |
| **RuntimeError(Proxy error(IOException))** | Dilemparkan ketika terjadi kesalahan I/O saat mengakses file. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Dilemparkan ketika data input berada dalam format yang tidak didukung. |



### Lihat Juga
* kelas [`ExcelWorkbookImporter`](/slides/python-net/id/aspose.slides.importing/excelworkbookimporter)
* kelas [`IExcelDataWorkbook`](/slides/python-net/id/aspose.slides.excel/iexceldataworkbook)
* kelas [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection)
* modul [`aspose.slides.importing`](/slides/python-net/id/aspose.slides.importing)
* library [`Aspose.Slides`](/slides/python-net)