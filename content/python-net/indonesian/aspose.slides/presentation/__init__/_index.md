---
title: Presentation constructor
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
Konstruktor ini membuat presentasi baru dari awal.
            Presentasi yang dibuat memiliki satu slide kosong.


```python
def __init__(self):
    ...
```



## __init__(self, load_options) {#loadoptions}
Konstruktor ini membuat presentasi baru dari awal.
            Presentasi yang dibuat memiliki satu slide kosong.


```python
def __init__(self, load_options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/id/aspose.slides/loadoptions) | Opsi muat tambahan. |


## __init__(self, stream) {#iorawiobase}
Konstruktor ini adalah mekanisme utama untuk membaca Presentasi yang ada.


```python
def __init__(self, stream):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | **io.RawIOBase** | Aliran masukan. |


## __init__(self, file) {#str}
Konstruktor ini mendapatkan jalur berkas sumber dari mana
             isi Presentasi dibaca.


```python
def __init__(self, file):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file | **str** | Berkas masukan. |

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilempar ketika berkas masukan memiliki panjang nol |


## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
Konstruktor ini adalah mekanisme utama untuk membaca Presentasi yang ada.


```python
def __init__(self, stream, load_options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | **io.RawIOBase** | Aliran masukan. |
| load_options | [`LoadOptions`](/slides/python-net/id/aspose.slides/loadoptions) | Opsi muat tambahan. |


## __init__(self, file, load_options) {#str-loadoptions}
Konstruktor ini mendapatkan jalur berkas sumber dari mana
            isi Presentasi dibaca.


```python
def __init__(self, file, load_options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file | **str** | Berkas masukan. |
| load_options | [`LoadOptions`](/slides/python-net/id/aspose.slides/loadoptions) | Opsi muat tambahan. |

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilempar ketika berkas masukan memiliki panjang nol |



### Lihat Juga
* kelas [`LoadOptions`](/slides/python-net/id/aspose.slides/loadoptions)
* kelas [`Presentation`](/slides/python-net/id/aspose.slides/presentation)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)