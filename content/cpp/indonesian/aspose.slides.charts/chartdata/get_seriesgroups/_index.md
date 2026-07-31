---
title: get_SeriesGroups()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan grup seri. Hanya-baca IChartSeriesGroupCollection.
type: docs
weight: 27
url: /id/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() metode


Mendapatkan grup seri. Hanya-baca [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## Catatan


1) Setiap grup seri berisi seri dengan tipe yang dapat digabungkan. Grup tipe seri yang dapat digabungkan didefinisikan dan dijelaskan dengan enum CombinableSeriesTypesGroup. Juga setiap grup seri berisi seri yang dipetakan pada sumbu utama atau pada sumbu sekunder (tidak keduanya dalam satu grup). Jadi, prinsip pengelompokan seri adalah pengelompokan berdasarkan grup tipe yang disebutkan di atas dan berdasarkan tipe pemetaan utama/sekunder.

2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("series group properties"). "Series group properties" dalam kelas [ChartSeriesGroup](../../chartseriesgroup/) bersifat baca/tulis. Setiap "series group properties" dapat memiliki proyeksi hanya-baca dalam kelas [ChartSeries](../../chartseries/).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Kelas [ChartData](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)