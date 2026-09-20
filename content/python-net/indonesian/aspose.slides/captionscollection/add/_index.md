---
title: add method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/captionscollection/add/
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
| file_path | **str** | Jalur ke berkas WebVTT. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Dilemparkan jika `file_path` bernilai `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan jika `file_path` kosong. |


## add(self, label, stream) {#str-iorawiobase}
Menambahkan caption tertutup WebVTT ke akhir koleksi dari sebuah aliran.

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

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Dilemparkan jika `stream` bernilai `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan jika data masukan tidak dalam format WebVTT. |



### Lihat Juga
* class [`CaptionsCollection`](/slides/python-net/id/aspose.slides/captionscollection)
* class [`ICaptions`](/slides/python-net/id/aspose.slides/icaptions)
* module [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)