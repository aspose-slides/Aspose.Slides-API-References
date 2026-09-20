---
title: secondary_categories property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chartdata/secondary_categories/
weight: 120
---
## secondary_categories properti
Mendapatkan kategori sekunder jika properti [`ChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/use_secondary_categories) bernilai true.
            Hanya-baca [`IChartCategoryCollection`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection).

### Catatan

Jika properti [`ChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/use_secondary_categories) bernilai false maka [`ChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/secondary_categories) 
            properti mengembalikan None dan data pada properti [`ChartData.categories`](/slides/python-net/id/aspose.slides.charts/chartdata/categories) digunakan baik untuk utama 
            dan seri sekunder.
Jika properti [`ChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/use_secondary_categories) bernilai true maka data pada 
            properti [`ChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/secondary_categories) ini digunakan untuk seri sekunder dan data 
            pada properti [`ChartData.categories`](/slides/python-net/id/aspose.slides.charts/chartdata/categories) digunakan untuk seri utama.

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