---
title: series_groups property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups properti
Mendapatkan grup seri.
            Hanya baca [`IChartSeriesGroupCollection`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroupcollection).

### Catatan

1) Setiap grup seri berisi seri dengan tipe yang dapat digabungkan. Grup tipe seri yang dapat digabungkan didefinisikan dan dijelaskan dengan enum CombinableSeriesTypesGroup. Selain itu, setiap grup seri berisi seri yang dipetakan pada sumbu utama atau pada sumbu sekunder (tidak keduanya dalam satu grup). Jadi, prinsip pengelompokan seri adalah pengelompokan berdasarkan grup tipe yang disebutkan di atas dan berdasarkan tipe pemetaan utama/sekunder.
            
            2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("properti grup seri"). "Properti grup seri" di kelas ChartSeriesGroup adalah baca/tulis. Setiap "Properti grup seri" dapat memiliki proyeksi hanya-baca di kelas ChartSeries.

### Definisi:
```python
@property
def series_groups(self):
    ...
```

### Lihat Juga
* kelas [`IChartData`](/slides/python-net/id/aspose.slides.charts/ichartdata)
* kelas [`IChartSeriesGroupCollection`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroupcollection)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)