---
title: series_groups property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups properti
Mendapatkan grup seri.
            Hanya baca [`IChartSeriesGroupCollection`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroupcollection).

### Catatan

1) Setiap grup seri berisi seri dengan tipe yang dapat digabungkan. Grup tipe seri yang dapat digabungkan didefinisikan dan dijelaskan dengan enum CombinableSeriesTypesGroup. Juga setiap grup seri berisi seri yang dipetakan baik pada sumbu utama maupun pada sumbu sekunder (tidak keduanya dalam satu grup). Jadi, prinsip pengelompokan seri adalah pengelompokan berdasarkan grup tipe yang disebutkan di atas dan berdasarkan tipe plot utama/sekunder.

2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("Properti grup seri"). "Properti grup seri" di kelas ChartSeriesGroup adalah baca/tulis. Setiap Properti grup seri dapat memiliki proyeksi hanya baca di kelas ChartSeries.

### Definisi:
```python
@property
def series_groups(self):
    ...
```

### Lihat Juga
* kelas [`ChartData`](/slides/python-net/id/aspose.slides.charts/chartdata)
* kelas [`IChartSeriesGroupCollection`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroupcollection)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* perpustakaan [`Aspose.Slides`](/slides/python-net)