---
title: add_from_html method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/slidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

### Mengembalikan

Slide yang ditambahkan



```python
def add_from_html(self, html_text):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_text | **str** | Html untuk ditambahkan. |


## add_from_html(self, html_stream) {#iorawiobase}
Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

### Mengembalikan

Slide yang ditambahkan



```python
def add_from_html(self, html_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Objek Stream yang akan digunakan sebagai sumber file HTML. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

### Mengembalikan

Slide yang ditambahkan.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_text | **str** | Html untuk ditambahkan. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/id/aspose.slides.importing/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini None semua objek eksternal akan diabaikan. |
| uri | **str** | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

### Mengembalikan

Slide yang ditambahkan.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/id/aspose.slides.importing/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini None semua objek eksternal akan diabaikan. |
| uri | **str** | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |



### Lihat Juga
* kelas [`IExternalResourceResolver`](/slides/python-net/id/aspose.slides.importing/iexternalresourceresolver)
* kelas [`SlideCollection`](/slides/python-net/id/aspose.slides/slidecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)