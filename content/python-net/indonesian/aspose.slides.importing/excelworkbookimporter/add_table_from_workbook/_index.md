---
title: add_table_from_workbook method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
Mengambil tabel dari buku kerja Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

### Mengembalikan

Tabel yang telah ditambahkan ke koleksi shape.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection) | Koleksi shape tempat tabel akan ditambahkan. |
| x | **float** | Koordinat X untuk menempatkan tabel. |
| y | **float** | Koordinat Y untuk menempatkan tabel. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/id/aspose.slides.excel/iexceldataworkbook) | Buku kerja Excel. |
| worksheet_name | **str** | Nama lembar kerja yang berisi tabel. |
| cell_range | **str** | Rentang sel yang mendefinisikan tabel (misalnya, "A1:D10"). |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilempar ketika ada parameter yang diperlukan bernilai None atau kosong, atau ketika lembar kerja atau rentang sel yang ditentukan tidak valid. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Dilempar ketika data masukan berada dalam format yang tidak didukung. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
Mengambil tabel dari file buku kerja Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

### Mengembalikan

Tabel yang telah ditambahkan ke koleksi shape.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection) | Koleksi shape tempat tabel akan ditambahkan. |
| x | **float** | Koordinat X untuk menempatkan tabel. |
| y | **float** | Koordinat Y untuk menempatkan tabel. |
| workbook_path | **str** | Jalur ke file buku kerja Excel. |
| worksheet_name | **str** | Nama lembar kerja yang berisi tabel. |
| cell_range | **str** | Rentang sel yang mendefinisikan tabel (misalnya, "A1:D10"). |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilempar ketika ada parameter yang diperlukan bernilai None atau kosong, atau ketika lembar kerja atau rentang sel yang ditentukan tidak valid. |
| **RuntimeError(Proxy error(IOException))** | Dilempar ketika terjadi kesalahan I/O saat mengakses file buku kerja. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Dilempar ketika data masukan berada dalam format yang tidak didukung. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
Mengambil tabel dari file buku kerja Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

### Mengembalikan

Tabel yang telah ditambahkan ke koleksi shape.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection) | Koleksi shape tempat tabel akan ditambahkan. |
| x | **float** | Koordinat X untuk menempatkan tabel. |
| y | **float** | Koordinat Y untuk menempatkan tabel. |
| workbook_stream | **io.RawIOBase** | Aliran yang berisi data buku kerja. |
| worksheet_name | **str** | Nama lembar kerja yang berisi tabel. |
| cell_range | **str** | Rentang sel yang mendefinisikan tabel (misalnya, "A1:D10"). |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilempar ketika ada parameter yang diperlukan bernilai None atau kosong, atau ketika lembar kerja atau rentang sel yang ditentukan tidak valid. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Dilempar ketika data masukan berada dalam format yang tidak didukung. |



### Lihat Juga
* kelas [`ExcelWorkbookImporter`](/slides/python-net/id/aspose.slides.importing/excelworkbookimporter)
* kelas [`IExcelDataWorkbook`](/slides/python-net/id/aspose.slides.excel/iexceldataworkbook)
* kelas [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection)
* kelas [`ITable`](/slides/python-net/id/aspose.slides/itable)
* modul [`aspose.slides.importing`](/slides/python-net/id/aspose.slides.importing)
* pustaka [`Aspose.Slides`](/slides/python-net)