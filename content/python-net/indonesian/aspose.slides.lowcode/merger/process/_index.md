---
title: process method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi.


```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| input_file_names | **List[str]** | Sebuah array dari nama file presentasi masukan. |
| output_file_name | **str** | Nama file keluaran dari file presentasi gabungan yang dihasilkan. |

### Eksepsi

| Eksepsi | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan ketika nama file masukan tidak valid atau format tidak cocok. |


## process(input_file_names, output_stream) {#liststr-iorawiobase}
Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi.


```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| input_file_names | **List[str]** | Sebuah array dari nama file presentasi masukan. |
| output_stream | **io.RawIOBase** | Stream keluaran. |

### Eksepsi

| Eksepsi | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan ketika nama file masukan tidak valid atau format tidak cocok. |


## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi.


```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| input_file_names | **List[str]** | Sebuah array dari nama file presentasi masukan. |
| output_file_name | **str** | Nama file keluaran dari file presentasi gabungan yang dihasilkan. |
| options | [`ISaveOptions`](/slides/python-net/id/aspose.slides.export/isaveoptions) | Opsi tambahan yang menentukan bagaimana presentasi gabungan disimpan. |

### Eksepsi

| Eksepsi | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan ketika nama file masukan tidak valid atau format tidak cocok. |


## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi.


```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| input_file_names | **List[str]** | Sebuah array dari nama file presentasi masukan. |
| output_stream | **io.RawIOBase** | Stream keluaran. |
| options | [`ISaveOptions`](/slides/python-net/id/aspose.slides.export/isaveoptions) | Opsi tambahan yang menentukan bagaimana presentasi gabungan disimpan. |

### Eksepsi

| Eksepsi | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan ketika nama file masukan tidak valid atau format tidak cocok. |



### Lihat Juga
* kelas [`ISaveOptions`](/slides/python-net/id/aspose.slides.export/isaveoptions)
* kelas [`Merger`](/slides/python-net/id/aspose.slides.lowcode/merger)
* modul [`aspose.slides.lowcode`](/slides/python-net/id/aspose.slides.lowcode)
* perpustakaan [`Aspose.Slides`](/slides/python-net)