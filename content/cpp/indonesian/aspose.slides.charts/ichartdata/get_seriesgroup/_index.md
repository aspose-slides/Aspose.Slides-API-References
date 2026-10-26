---
title: get_SeriesGroup()
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 222
url: /id/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) metode

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) metode

Mengembalikan grup seri pada indeks yang ditentukan.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## Catatan

1) Setiap grup seri berisi seri dengan tipe yang dapat dikombinasikan. Grup tipe seri yang dapat dikombinasikan didefinisikan dan dijelaskan dengan CombinableSeriesTypesGroup enum. Juga setiap grup seri berisi seri yang dipetakan baik pada sumbu utama maupun pada sumbu sekunder (tidak keduanya dalam satu grup). Jadi, prinsip pengelompokan seri adalah pengelompokan berdasarkan grup tipe yang disebutkan di atas dan berdasarkan tipe pemetaan utama/sekunder. 2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("series group properties"). "Series group properties" dalam kelas [ChartSeriesGroup](../../chartseriesgroup/) bersifat read/write. Setiap "series group properties" dapat memiliki proyeksi hanya-baca di kelas [ChartSeries](../../chartseries/).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChartSeriesGroup](../../ichartseriesgroup/)
* Kelas [IChartSeries](../../ichartseries/)
* Kelas [IChartData](../)
* Ruang nama [Aspose::Slides::Charts](../../)
* Perpustakaan [Aspose.Slides](../../../)