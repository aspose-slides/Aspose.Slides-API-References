---
title: series_groups property
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups properti
Mendapatkan grup seri.
            Hanya baca [`IChartSeriesGroupCollection`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroupcollection).

### Catatan

1) Setiap grup seri berisi seri dengan tipe yang dapat digabungkan. Grup tipe seri yang dapat digabungkan didefinisikan dan dijelaskan dengan enum CombinableSeriesTypesGroup.
            Juga setiap grup seri berisi seri yang dipetakan baik pada sumbu utama maupun pada sumbu sekunder (tidak keduanya dalam satu grup).
            Jadi, prinsip pengelompokan seri adalah pengelompokan berdasarkan grup tipe yang disebutkan di atas dan berdasarkan tipe plot utama/sekunder.
            
            2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("properti grup seri").
            "Series group properties" in ChartSeriesGroup class is baca/tulis.
            Setiap "series group properties" dapat memiliki proyeksi hanya baca dalam ChartSeries class.

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