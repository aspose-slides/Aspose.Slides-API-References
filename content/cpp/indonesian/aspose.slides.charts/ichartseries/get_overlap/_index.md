---
title: get_Overlap()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan seberapa banyak batang dan kolom saling tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). Ini adalah properti bukan hanya dari seri ini tetapi dari semua seri dalam grup seri induk. Ini merupakan proyeksi properti yang sesuai dalam grup seri induk, sehingga properti ini bersifat baca-saja. Untuk mengubah nilai, gunakan properti get_ParentSeriesGroup()->get(set)_Overlap() baca/tulis. Baca-saja int8_t.
type: docs
weight: 690
url: /id/aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() metode


Menentukan berapa banyak batang dan kolom saling tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). Ini adalah properti bukan hanya dari seri ini tetapi dari semua seri dalam grup seri induk. Ini merupakan proyeksi properti yang sesuai dalam grup seri induk, sehingga properti ini bersifat baca-saja. Untuk mengubah nilai, gunakan properti [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() baca/tulis. Baca-saja **int8_t**.

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## Catatan


Overlap menentukan tingkat tumpang tindih atau jarak antara batang dan kolom sebagai persentase dari lebar mereka:
* -100%: Jarak maksimum (batang sepenuhnya terpisah).
* 0%: Batang ditempatkan berdampingan tanpa tumpang tindih atau jarak.
* 100%: Tumpang tindih maksimum (batang sepenuhnya tumpang tindih satu sama lain). Ini merupakan proyeksi properti [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap().


## Lihat Juga

* Kelas [IChartSeries](../)
* Ruang nama [Aspose::Slides::Charts](../../)
* Pustaka [Aspose.Slides](../../../)