---
title: categories property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartdata/categories/
weight: 80
---
## categories özelliği
Birincil kategorileri alır (veya [`IChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/use_secondary_categories) özelliği false ise hem birincil hem ikincil kategorileri alır).
            Salt-okunur [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection).

### Açıklamalar

Eğer [`IChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/use_secondary_categories) özelliği false ise [`IChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/secondary_categories) özelliği None döndürür ve bu [`IChartData.categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/categories) özelliğindeki veri hem birincil hem ikincil seriler için kullanılır.
            Eğer [`IChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/use_secondary_categories) özelliği true ise [`IChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/secondary_categories) özelliğindeki veri ikincil seriler için ve bu [`IChartData.categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/categories) özelliğindeki veri birincil seriler için kullanılır.

### Tanım:
```python
@property
def categories(self):
    ...
```

### İlgili
* sınıf [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection)
* sınıf [`IChartData`](/slides/python-net/tr/aspose.slides.charts/ichartdata)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)