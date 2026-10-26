---
title: path_types property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shapeelement/path_types/
weight: 40
---
## path_types properti
Mengembalikan array nilai byte yang menentukan jenis setiap titik dalam jalur elemen. 
            
**0**  Menunjukkan bahwa titik tersebut adalah awal sebuah figur.


**1**  Menunjukkan bahwa titik tersebut adalah salah satu dari dua titik akhir sebuah garis.


**3**  Menunjukkan bahwa titik tersebut adalah titik akhir atau titik kontrol dari sebuah spline Bezier kubik.


**7**  Menyembunyikan semua bit kecuali tiga bit urutan rendah, yang menunjukkan jenis titik.


**16**  Menentukan bahwa segmen yang bersangkutan berupa garis putus-putus.


**32**  Menentukan bahwa titik tersebut adalah penanda.


**128**  Menentukan bahwa titik tersebut adalah titik terakhir dalam subpath tertutup (figur).


**129**  Menunjukkan titik data yang sekaligus merupakan titik akhir segmen garis dan titik terakhir dari subpath tertutup.

### Definisi:
```python
@property
def path_types(self):
    ...
```


### Lihat Juga
* kelas [`ShapeElement`](/slides/python-net/id/aspose.slides/shapeelement)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)