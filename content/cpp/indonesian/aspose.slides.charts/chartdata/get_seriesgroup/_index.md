---
title: get_SeriesGroup()
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 222
url: /id/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) metode




```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) metode


Mengembalikan grup seri pada indeks yang ditentukan.

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## Catatan


1) Setiap grup seri berisi seri dengan tipe yang dapat digabungkan. Grup tipe seri yang dapat digabungkan didefinisikan dan dijelaskan dengan enum CombinableSeriesTypesGroup. Selain itu, setiap grup seri berisi seri yang dipetakan baik pada sumbu utama maupun pada sumbu sekunder (tidak keduanya dalam satu grup). Jadi, prinsip pengelompokan seri adalah pengelompokan berdasarkan grup tipe yang disebutkan di atas dan berdasarkan tipe plot utama/sekunder. 2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("series group properties"). "Series group properties" dalam kelas [ChartSeriesGroup](../../chartseriesgroup/) adalah baca/tulis. Setiap "series group properties" dapat memiliki proyeksi baca-saja dalam kelas [ChartSeries](../../chartseries/).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChartSeriesGroup](../../ichartseriesgroup/)
* Kelas [IChartSeries](../../ichartseries/)
* Kelas [ChartData](../)
* Ruang nama [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)