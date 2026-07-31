---
title: get_PathTypes()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan sebuah array nilai byte yang menentukan tipe setiap titik dalam jalur elemen.
type: docs
weight: 27
url: /id/aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() metode

Mengembalikan sebuah array nilai byte yang menentukan tipe setiap titik dalam jalur elemen.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```

## Keterangan

**0** Menunjukkan bahwa titik tersebut adalah awal dari sebuah gambar.

**1** Menunjukkan bahwa titik tersebut adalah salah satu dari dua titik akhir sebuah garis.

**3** Menunjukkan bahwa titik tersebut adalah titik akhir atau titik kontrol dari sebuah spline Bezier kubik.

**7** Menyembunyikan semua bit kecuali tiga bit urutan rendah, yang menunjukkan tipe titik.

**16** Menentukan bahwa segmen yang bersangkutan berisi garis putus-putus.

**32** Menentukan bahwa titik tersebut adalah penanda.

**128** Menentukan bahwa titik tersebut adalah titik terakhir dalam subpath tertutup (gambar).

**129** Menunjukkan titik data yang sekaligus merupakan titik akhir segmen garis dan titik terakhir dari sebuah subpath tertutup.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ShapeElement](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)