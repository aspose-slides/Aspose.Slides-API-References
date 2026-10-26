---
title: contains method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
Menentukan apakah titik yang ditentukan berada dalam persegi panjang ini.

### Mengembalikan

`True` jika titik berada dalam persegi panjang ini; jika tidak, `False`.



```python
def contains(self, point):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/id/aspose.slides/point) | Titik yang akan diuji. Setiap objek dengan atribut `x` dan `y` diterima. |

### Pengecualian

| Exception | Description |
| :- | :- |
| **TypeError** | Jumlah argumen salah. |


## contains(self, rect) {#rectangle}
Menentukan apakah daerah persegi panjang yang direpresentasikan oleh `rect` sepenuhnya berada dalam persegi panjang ini.

### Mengembalikan

`True` jika daerah persegi panjang yang direpresentasikan oleh `rect` sepenuhnya berada dalam persegi panjang ini; jika tidak, `False`.



```python
def contains(self, rect):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/id/aspose.slides/rectangle) | Persegi panjang yang akan diuji. Setiap objek dengan atribut `x`, `y`, `width` dan `height` diterima. |

### Pengecualian

| Exception | Description |
| :- | :- |
| **TypeError** | Jumlah argumen salah. |


## contains(self, x, y) {#int-int}
Menentukan apakah titik yang ditentukan berada dalam persegi panjang ini.

### Mengembalikan

`True` jika titik yang didefinisikan oleh `x` dan `y` berada dalam persegi panjang ini; jika tidak, `False`.



```python
def contains(self, x, y):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **int** | Koordinat x dari titik yang akan diuji. |
| y | **int** | Koordinat y dari titik yang akan diuji. |

### Pengecualian

| Exception | Description |
| :- | :- |
| **TypeError** | Jumlah argumen salah. |



### Lihat Juga
* kelas [`Point`](/slides/python-net/id/aspose.slides/point)
* kelas [`Rectangle`](/slides/python-net/id/aspose.slides/rectangle)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)