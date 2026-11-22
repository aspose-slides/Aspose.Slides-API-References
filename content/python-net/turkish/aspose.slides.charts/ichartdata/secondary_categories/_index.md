---
title: secondary_categories property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartdata/secondary_categories/
weight: 130
---
## secondary_categories özelliği
[`IChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/use_secondary_categories) özelliği doğruysa ikincil kategorileri alır.
            Salt okunur [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection).

### Açıklamalar

Eğer [`IChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/use_secondary_categories) özelliği false ise bu [`IChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/secondary_categories) 
            özellik None döndürür ve [`IChartData.categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/categories) özelliğindeki veri hem birincil 
            hem de ikincil seriler için kullanılır.
            Eğer [`IChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/use_secondary_categories) özelliği true ise bu [`IChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/secondary_categories) 
            özelliğindeki veri ikincil seriler için ve [`IChartData.categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/categories) 
            özelliğindeki veri birincil seriler için kullanılır.

### Tanım:
```python
@property
def secondary_categories(self):
    ...
```

### Ayrıca Bakınız
* sınıf [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection)
* sınıf [`IChartData`](/slides/python-net/tr/aspose.slides.charts/ichartdata)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)