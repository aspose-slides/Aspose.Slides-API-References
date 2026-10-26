---
title: categories property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chartdata/categories/
weight: 70
---
## categories properti
Mendapatkan kategori utama (atau kedua kategori utama dan sekunder jika properti [`ChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/use_secondary_categories) bernilai false). Hanya-baca [`IChartCategoryCollection`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection).

### Catatan
Jika properti [`ChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/use_secondary_categories) bernilai false maka properti [`ChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/secondary_categories) mengembalikan None dan data dalam properti [`ChartData.categories`](/slides/python-net/id/aspose.slides.charts/chartdata/categories) ini digunakan baik untuk seri utama maupun sekunder. 
Jika properti [`ChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/use_secondary_categories) bernilai true maka data dalam properti [`ChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/secondary_categories) digunakan untuk seri sekunder dan data dalam properti [`ChartData.categories`](/slides/python-net/id/aspose.slides.charts/chartdata/categories) ini digunakan untuk seri utama.

### Definisi:
```python
@property
def categories(self):
    ...
```

### Lihat Juga
* kelas [`ChartData`](/slides/python-net/id/aspose.slides.charts/chartdata)
* kelas [`IChartCategoryCollection`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)