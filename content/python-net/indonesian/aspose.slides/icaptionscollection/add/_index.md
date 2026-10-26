---
title: add method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Menambahkan caption tertutup WebVTT ke akhir koleksi.

### Mengembalikan

Instansi [`ICaptions`](/slides/python-net/id/aspose.slides/icaptions) yang ditambahkan.



```python
def add(self, label, file_path):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| label | **str** | Label caption tertutup. |
| file_path | **str** | Jalur ke file WebVTT. |

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Dilemparkan jika `file_path` bernilai `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan jika `file_path` kosong. |


## add(self, label, stream) {#str-iorawiobase}
Menambahkan caption tertutup WebVTT ke akhir koleksi dari aliran.

### Mengembalikan

Instansi [`ICaptions`](/slides/python-net/id/aspose.slides/icaptions) yang ditambahkan.



```python
def add(self, label, stream):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| label | **str** | Label caption tertutup. |
| stream | **io.RawIOBase** | Aliran masukan yang berisi data dalam format WebVTT. |

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Dilemparkan jika `stream` bernilai `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan jika data masukan tidak dalam format WebVTT. |



### Lihat Juga
* kelas [`ICaptions`](/slides/python-net/id/aspose.slides/icaptions)
* kelas [`ICaptionsCollection`](/slides/python-net/id/aspose.slides/icaptionscollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)