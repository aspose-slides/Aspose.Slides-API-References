---
title: add method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/customxmlpartcollection/add/
weight: 10
---
## add(self, xml_string) {#str}
Menambahkan bagian xml khusus baru.

### Mengembalikan

Bagian xml khusus dibuat.



```python
def add(self, xml_string):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| xml_string | **str** | String xml dari bagian baru yang akan ditambahkan. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString bernilai `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString kosong atau xml-data tidak valid. |


## add(self, xml_data) {#bytes}
Menambahkan bagian xml khusus baru.

### Mengembalikan

Bagian xml khusus dibuat.



```python
def add(self, xml_data):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| xml_data | **bytes** | Data xml dari bagian baru yang akan ditambahkan. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData bernilai `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData kosong atau tidak valid. |


## add(self, input_stream) {#iorawiobase}
Menambahkan bagian xml khusus baru.

### Mengembalikan

Bagian xml khusus dibuat.



```python
def add(self, input_stream):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | inputStream dengan data xml dari bagian baru yang akan ditambahkan. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream bernilai `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Data dalam inputStream kosong atau tidak valid. |



### Lihat Juga
* kelas [`CustomXmlPartCollection`](/slides/python-net/id/aspose.slides/customxmlpartcollection)
* kelas [`ICustomXmlPart`](/slides/python-net/id/aspose.slides/icustomxmlpart)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)