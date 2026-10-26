---
title: categories property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## properti kategori
Mendapatkan kategori utama (atau kedua kategori utama dan sekunder jika properti [`IChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/use_secondary_categories) bernilai false).
Hanya-baca [`IChartCategoryCollection`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection).

### Catatan
Jika properti [`IChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/use_secondary_categories) bernilai false maka properti [`IChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/secondary_categories) mengembalikan None dan data dalam properti [`IChartData.categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/categories) ini digunakan baik untuk seri utama maupun sekunder.
Jika properti [`IChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/use_secondary_categories) bernilai true maka data dalam properti [`IChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/secondary_categories) digunakan untuk seri sekunder dan data dalam properti [`IChartData.categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/categories) ini digunakan untuk seri utama.

### Definisi:
```python
@property
def categories(self):
    ...
```

### Lihat Juga
* kelas [`IChartCategoryCollection`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection)
* kelas [`IChartData`](/slides/python-net/id/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)