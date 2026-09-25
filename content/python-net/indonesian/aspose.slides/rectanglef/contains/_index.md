---
title: contains method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
Menentukan apakah titik yang ditentukan berada di dalam persegi panjang ini.

### Returns

`True` jika titik berada di dalam persegi panjang ini; jika tidak, `False`.



```python
def contains(self, point):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/id/aspose.slides/pointf) | Titik yang akan diuji. Objek apa pun dengan atribut `x` dan `y` diterima. |

### Exceptions

| Pengecualian | Deskripsi |
| :- | :- |
| **TypeError** | Jumlah argumen salah. |


## contains(self, rect) {#rectanglef}
Menentukan apakah wilayah persegi panjang yang diwakili oleh `rect` sepenuhnya berada di dalam persegi panjang ini.

### Returns

`True` jika wilayah persegi panjang yang diwakili oleh `rect` sepenuhnya berada di dalam persegi panjang ini; jika tidak, `False`.



```python
def contains(self, rect):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef) | Persegi panjang yang akan diuji. Objek apa pun dengan atribut `x`, `y`, `width` dan `height` diterima. |

### Exceptions

| Pengecualian | Deskripsi |
| :- | :- |
| **TypeError** | Jumlah argumen salah. |


## contains(self, x, y) {#float-float}
Menentukan apakah titik yang ditentukan berada di dalam persegi panjang ini.

### Returns

`True` jika titik yang didefinisikan oleh `x` dan `y` berada di dalam persegi panjang ini; jika tidak, `False`.



```python
def contains(self, x, y):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat x dari titik yang akan diuji. |
| y | **float** | Koordinat y dari titik yang akan diuji. |

### Exceptions

| Pengecualian | Deskripsi |
| :- | :- |
| **TypeError** | Jumlah argumen salah. |



### Lihat Juga
* kelas [`PointF`](/slides/python-net/id/aspose.slides/pointf)
* kelas [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)