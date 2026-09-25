---
title: from_argb method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
Membuat warna dari nilai ARGB 32-bit.

### Mengembalikan

Warna yang dibuat dari nilai yang ditentukan.



```python
@staticmethod
def from_argb(argb):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| argb | **int** | Sebuah nilai yang menentukan nilai ARGB 32-bit (bertanda atau tak bertanda). |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **ValueError** | Nilai komponen kurang dari 0 atau lebih dari 255. |
| **TypeError** | Jumlah atau tipe argumen salah. |


## from_argb(alpha, base_color) {#int-color}
Membuat warna dari nilai alpha dan warna dasar yang ditentukan.

### Mengembalikan

Warna yang dibuat dari nilai yang ditentukan.



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| alpha | **int** | Nilai komponen alpha. Nilai yang valid antara 0 sampai 255. |
| base_color | [`Color`](/slides/python-net/id/aspose.slides/color) | Warna yang digunakan untuk membuat warna baru. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **ValueError** | Nilai komponen kurang dari 0 atau lebih dari 255. |
| **TypeError** | Jumlah atau tipe argumen salah. |


## from_argb(red, green, blue) {#int-int-int}
Membuat warna tidak transparan (alpha 255) dari nilai merah, hijau, dan biru yang ditentukan.

### Mengembalikan

Warna yang dibuat dari nilai yang ditentukan.



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| red | **int** | Nilai komponen merah. Nilai yang valid antara 0 sampai 255. |
| green | **int** | Nilai komponen hijau. Nilai yang valid antara 0 sampai 255. |
| blue | **int** | Nilai komponen biru. Nilai yang valid antara 0 sampai 255. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **ValueError** | Nilai komponen kurang dari 0 atau lebih dari 255. |
| **TypeError** | Jumlah atau tipe argumen salah. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
Membuat warna dari empat nilai komponen ARGB (alpha, merah, hijau, dan biru).

### Mengembalikan

Warna yang dibuat dari nilai yang ditentukan.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| alpha | **int** | Nilai komponen alpha. Nilai yang valid antara 0 sampai 255. |
| red | **int** | Nilai komponen merah. Nilai yang valid antara 0 sampai 255. |
| green | **int** | Nilai komponen hijau. Nilai yang valid antara 0 sampai 255. |
| blue | **int** | Nilai komponen biru. Nilai yang valid antara 0 sampai 255. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **ValueError** | Nilai komponen kurang dari 0 atau lebih dari 255. |
| **TypeError** | Jumlah atau tipe argumen salah. |



### Lihat Juga
* kelas [`Color`](/slides/python-net/id/aspose.slides/color)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)