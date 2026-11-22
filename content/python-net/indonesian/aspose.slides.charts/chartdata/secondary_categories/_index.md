---
title: secondary_categories property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chartdata/secondary_categories/
weight: 130
---
## secondary_categories properti
Mendapatkan kategori sekunder jika [`ChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/use_secondary_categories) properti bernilai true.
            Hanya-baca [`IChartCategoryCollection`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection).

### Keterangan

Jika [`ChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/use_secondary_categories) properti bernilai false maka [`ChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/secondary_categories) 
            properti mengembalikan None dan data dalam [`ChartData.categories`](/slides/python-net/id/aspose.slides.charts/chartdata/categories) properti digunakan untuk seri primer 
            dan sekunder.
            Jika [`ChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/use_secondary_categories) properti bernilai true maka data dalam 
            [`ChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/secondary_categories) properti ini digunakan untuk seri sekunder dan data 
            dalam [`ChartData.categories`](/slides/python-net/id/aspose.slides.charts/chartdata/categories) properti digunakan untuk seri primer.

### Definisi:
```python
@property
def secondary_categories(self):
    ...
```

### Lihat Juga
* kelas [`ChartData`](/slides/python-net/id/aspose.slides.charts/chartdata)
* kelas [`IChartCategoryCollection`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* perpustakaan [`Aspose.Slides`](/slides/python-net)