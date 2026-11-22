---
title: categories property
second_title: Aspose.Slides untuk Python melalui .NET Referensi API
description: 
type: docs
url: /id/aspose.slides.charts/chartdata/categories/
weight: 80
---
## properti kategori
Mendapatkan kategori utama (atau baik kategori utama maupun sekunder jika properti [`ChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/use_secondary_categories) bernilai false).
Hanya baca [`IChartCategoryCollection`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection).

### Catatan
Jika properti [`ChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/use_secondary_categories) bernilai false maka [`ChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/secondary_categories) 
            properti mengembalikan None dan data pada properti [`ChartData.categories`](/slides/python-net/id/aspose.slides.charts/chartdata/categories) ini digunakan baik untuk seri utama 
            dan sekunder.
Jika properti [`ChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/use_secondary_categories) bernilai true maka data pada properti [`ChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/secondary_categories) 
            properti digunakan untuk seri sekunder dan data pada properti [`ChartData.categories`](/slides/python-net/id/aspose.slides.charts/chartdata/categories) ini digunakan 
            untuk seri utama.

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
* library [`Aspose.Slides`](/slides/python-net)