---
title: secondary_categories property
second_title: Aspose.Slides untuk Python melalui Referensi API .NET
description: 
type: docs
url: /id/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories properti
Gets the secondary categories if [`IChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/use_secondary_categories) properti is true.
            Hanya-baca [`IChartCategoryCollection`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection).

### Keterangan

Jika properti [`IChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/use_secondary_categories) bernilai false maka properti [`IChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/secondary_categories) 
            mengembalikan None dan data dalam properti [`IChartData.categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/categories) digunakan baik untuk seri utama 
            dan sekunder.
            Jika properti [`IChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/use_secondary_categories) bernilai true maka data dalam 
            properti [`IChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/secondary_categories) ini digunakan untuk seri sekunder dan data 
            dalam properti [`IChartData.categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/categories) digunakan untuk seri utama.

### Definisi:
```python
@property
def secondary_categories(self):
    ...
```

### Lihat Juga
* kelas [`IChartCategoryCollection`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection)
* kelas [`IChartData`](/slides/python-net/id/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)