---
title: secondary_categories property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/ichartdata/secondary_categories/
weight: 130
---
## properti secondary_categories
Mendapatkan kategori sekunder jika properti [`IChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/use_secondary_categories) bernilai true.
            Baca-saja [`IChartCategoryCollection`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection).


### Catatan

Jika [`IChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/use_secondary_categories) properti false maka ini [`IChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/secondary_categories) 
            properti mengembalikan None dan data di [`IChartData.categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/categories) properti digunakan untuk primer 
            dan sekunder seri.
            Jika [`IChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/use_secondary_categories) properti true maka data di 
            ini [`IChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/secondary_categories) properti digunakan untuk seri sekunder dan data 
            di [`IChartData.categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/categories) properti digunakan untuk seri primer.

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
* perpustakaan [`Aspose.Slides`](/slides/python-net)