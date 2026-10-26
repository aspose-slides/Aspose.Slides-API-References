---
title: Hyperlink constructor
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
Membuat sebuah instance dari hyperlink.


```python
def __init__(self, url):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| url | **str** | URL hyperlink. |


## __init__(self, slide) {#islide}
Membuat sebuah instance dari hyperlink yang mengarah ke slide tertentu.
Catatan: hyperlink yang dibuat harus ditetapkan ke objek dari presentasi yang sama, jika tidak tautan akan disimpan sebagai NoAction.


```python
def __init__(self, slide):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | Slide tujuan. |


## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
Membuat sebuah instance dari hyperlink menggunakan hyperlink lain sebagai sumber, dengan mengganti properti sekunder.


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/id/aspose.slides/hyperlink) | Hyperlink sumber |
| target_frame | **str** | Bingkai tujuan |
| tooltip | **str** | Teks tooltip |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |



### Lihat Juga
* kelas [`Hyperlink`](/slides/python-net/id/aspose.slides/hyperlink)
* kelas [`ISlide`](/slides/python-net/id/aspose.slides/islide)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)