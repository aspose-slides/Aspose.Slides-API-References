---
title: get_PieSplitBy()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan cara menentukan titik data mana yang berada di lingkaran atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Ini adalah properti tidak hanya dari seri ini tetapi dari semua seri dalam grup seri induk - ini merupakan proyeksi properti grup yang sesuai. Oleh karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti get_ParentSeriesGroup()->get(set)_PieSplitBy() baca/tulis untuk mengubah nilai. Hanya-baca PieSplitType.
type: docs
weight: 755
url: /id/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() metode

Menentukan cara menentukan titik data mana yang berada di lingkaran atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Ini adalah properti bukan hanya dari seri ini tetapi dari semua seri dalam grup seri induk - ini merupakan proyeksi properti grup yang sesuai. Dan karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() properti baca/tulis untuk mengubah nilai. Hanya-baca [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## Keterangan

1) Ini adalah proyeksi properti [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Jika nilai properti adalah [PieSplitType::Custom](../../piesplittype/) maka Anda dapat menentukan informasi pemisahan kustom dengan properti [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Lihat Juga

* Enum [PieSplitType](../../piesplittype/)
* Class [ChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)