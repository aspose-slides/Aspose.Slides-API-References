---
title: insert_from_html method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

### Mengembalikan

Slide yang ditambahkan



```python
def insert_from_html(self, index, html_text):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Posisi untuk disisipkan. |
| html_text | **str** | Html untuk ditambahkan. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

### Mengembalikan

Slide yang ditambahkan



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Posisi untuk disisipkan. |
| html_stream | **io.RawIOBase** | Objek Stream yang akan digunakan sebagai sumber file HTML. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

### Mengembalikan

Slide yang ditambahkan



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Posisi untuk disisipkan. |
| html_text | **str** | Html untuk ditambahkan. |
| use_slide_with_index_as_start | **bool** | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan.<br/><br/>            Jika **true** , maka penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan.<br/><br/>            Jika **false** , maka data akan ditambahkan ke slide yang dibuat. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

### Mengembalikan

Slide yang ditambahkan



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Posisi untuk disisipkan. |
| html_stream | **io.RawIOBase** | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| use_slide_with_index_as_start | **bool** | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan.<br/><br/>            Jika **true** , maka penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan.<br/><br/>            Jika **false** , maka data akan ditambahkan ke slide yang dibuat. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

### Mengembalikan

Slide yang ditambahkan.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Posisi untuk disisipkan. |
| html_text | **str** | Html untuk ditambahkan. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/id/aspose.slides.importing/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini None semua objek eksternal akan diabaikan. |
| uri | **str** | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

### Mengembalikan

Slide yang ditambahkan.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Posisi untuk disisipkan. |
| html_stream | **io.RawIOBase** | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/id/aspose.slides.importing/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini None semua objek eksternal akan diabaikan. |
| uri | **str** | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

### Mengembalikan

Slide yang ditambahkan.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Posisi untuk disisipkan. |
| html_text | **str** | Html untuk ditambahkan. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/id/aspose.slides.importing/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini None semua objek eksternal akan diabaikan. |
| uri | **str** | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |
| use_slide_with_index_as_start | **bool** | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan.<br/><br/>            Jika **true** , maka penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan.<br/><br/>            Jika **false** , maka data akan ditambahkan ke slide yang dibuat. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

### Mengembalikan

Slide yang ditambahkan.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Posisi untuk disisipkan. |
| html_stream | **io.RawIOBase** | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/id/aspose.slides.importing/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini None semua objek eksternal akan diabaikan. |
| uri | **str** | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |
| use_slide_with_index_as_start | **bool** | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan.<br/><br/>            Jika **true** , maka penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan.<br/><br/>            Jika **false** , maka data akan ditambahkan ke slide yang dibuat. |



### Lihat Juga
* kelas [`IExternalResourceResolver`](/slides/python-net/id/aspose.slides.importing/iexternalresourceresolver)
* kelas [`ISlideCollection`](/slides/python-net/id/aspose.slides/islidecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)