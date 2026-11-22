---
title: secondary_categories property
second_title: Aspose.Slides Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartdata/secondary_categories/
weight: 130
---
## secondary_categories özelliği
[`ChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/use_secondary_categories) özelliği true ise ikincil kategorileri alır.
Salt okunur [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection).

### Açıklamalar

Eğer [`ChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/use_secondary_categories) özelliği false ise bu [`ChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/secondary_categories) özelliği None döndürür ve [`ChartData.categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/categories) özelliğindeki veri hem birincil hem de ikincil seriler için kullanılır.
Eğer [`ChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/use_secondary_categories) özelliği true ise bu [`ChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/secondary_categories) özelliğindeki veri ikincil seri için ve [`ChartData.categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/categories) özelliğindeki veri birincil seri için kullanılır.

### Tanım:
```python
@property
def secondary_categories(self):
    ...
```

### Ayrıca Bakınız
* sınıf [`ChartData`](/slides/python-net/tr/aspose.slides.charts/chartdata)
* sınıf [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)