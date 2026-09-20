---
title: add_from_html method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Menambahkan teks dari string html yang ditentukan ke dalam koleksi.


```python
def add_from_html(self, text):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | **str** | HTML text. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Menambahkan teks dari string html yang ditentukan ke dalam koleksi.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | **str** | HTML text. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/id/aspose.slides.importing/iexternalresourceresolver) | Resolver callback object which resolves URIs and fetches referrenced objects. |
| uri | **str** | URI for adding HTML document. Used for resolving relative links. |

### Catatan

Menentukan resolver dapat berpotensi memperkenalkan kerentanan. Gunakan dengan hati-hati.



### Lihat Juga
* kelas [`IExternalResourceResolver`](/slides/python-net/id/aspose.slides.importing/iexternalresourceresolver)
* kelas [`ParagraphCollection`](/slides/python-net/id/aspose.slides/paragraphcollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)