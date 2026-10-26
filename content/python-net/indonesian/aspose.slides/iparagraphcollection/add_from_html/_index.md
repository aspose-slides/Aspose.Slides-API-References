---
title: add_from_html method
second_title: Aspose.Slides untuk Python melalui .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Menambahkan teks dari string html yang ditentukan ke koleksi.


```python
def add_from_html(self, text):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | **str** | Teks HTML. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Menambahkan teks dari string html yang ditentukan ke koleksi.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | **str** | Teks HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/id/aspose.slides.importing/iexternalresourceresolver) | Objek callback Resolver yang menyelesaikan URI dan mengambil objek yang dirujuk. |
| uri | **str** | URI untuk menambahkan dokumen HTML. Digunakan untuk menyelesaikan tautan relatif. |

### Catatan

Menentukan resolver dapat berpotensi memperkenalkan kerentanan. Gunakan dengan hati-hati.



### Lihat Juga
* kelas [`IExternalResourceResolver`](/slides/python-net/id/aspose.slides.importing/iexternalresourceresolver)
* kelas [`IParagraphCollection`](/slides/python-net/id/aspose.slides/iparagraphcollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)