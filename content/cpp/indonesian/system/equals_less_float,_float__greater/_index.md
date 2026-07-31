---
title: Equals< float, float >()
second_title: Referensi API Aspose.Slides untuk C++
description: "Spesialisasi untuk nilai titik mengambang presisi tunggal. Meskipun dua NaN titik mengambang didefinisikan oleh IEC 60559:1989 untuk selalu dibandingkan tidak sama, kontrak untuk System.Object.Equals mengharuskan bahwa override harus memenuhi persyaratan untuk operator ekivalensi. Oleh karena itu, System.Double.Equals dan System.Single.Equals mengembalikan True saat membandingkan dua NaN, sementara operator kesetaraan mengembalikan False dalam kasus itu, sebagaimana diwajibkan oleh standar."
type: docs
weight: 2705
url: /id/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) fungsi

Spesialisasi untuk nilai titik mengambang presisi tunggal. Meskipun dua NaN titik mengambang didefinisikan oleh IEC 60559:1989 untuk selalu dibandingkan tidak sama, kontrak untuk [System.Object.Equals](../object/equals/) mengharuskan bahwa override harus memenuhi persyaratan untuk operator ekivalensi. Oleh karena itu, System.Double.Equals dan System.Single.Equals mengembalikan True saat membandingkan dua NaN, sementara operator kesetaraan mengembalikan False dalam kasus itu, sebagaimana diwajibkan oleh standar.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | const **float**\& | Komparan pertama |
| b | const **float**\& | Komparan kedua |

### Nilai Kembalian

True jika kedua nilai NaN atau sama, jika tidak - false

## Lihat Juga

* Ruang Nama [System](../)
* Pustaka [Aspose.Slides](../../)