---
title: get_SeriesGroups()
second_title: Aspose.Slides untuk Referensi API C++
description: Mendapatkan grup seri. Hanya-baca IChartSeriesGroupCollection.
type: docs
weight: 27
url: /id/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() metode

Mendapatkan grup seri. Hanya-baca [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## Catatan

1) Setiap grup seri berisi seri dengan tipe yang dapat digabungkan. Grup tipe seri yang dapat digabungkan didefinisikan dan dijelaskan dengan enum CombinableSeriesTypesGroup. Juga setiap grup seri berisi seri yang dipetakan baik pada sumbu utama maupun pada sumbu sekunder (tidak keduanya dalam satu grup). Jadi, prinsip pengelompokan seri adalah pengelompokan berdasarkan grup tipe yang disebutkan di atas dan berdasarkan tipe pemetaan utama/sekunder.

2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("properti grup seri"). "properti grup seri" dalam kelas [ChartSeriesGroup](../../chartseriesgroup/) bersifat baca/tulis. Setiap "properti grup seri" dapat memiliki proyeksi hanya-baca dalam kelas [ChartSeries](../../chartseries/).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Kelas [IChartData](../)
* Ruang nama [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)