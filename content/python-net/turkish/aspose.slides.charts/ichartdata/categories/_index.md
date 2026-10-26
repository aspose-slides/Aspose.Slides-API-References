---
title: categories property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## kategoriler özelliği
Birincil kategorileri alır (veya [`IChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/use_secondary_categories) özelliği false ise birincil ve ikincil kategorileri birlikte alır). Salt okunur [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection).

### Açıklamalar

Eğer [`IChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/use_secondary_categories) özelliği false ise [`IChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/secondary_categories) özelliği None döndürür ve bu [`IChartData.categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/categories) özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. Eğer [`IChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/use_secondary_categories) özelliği true ise [`IChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/secondary_categories) özelliğindeki veri ikincil seri için kullanılır ve bu [`IChartData.categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/categories) özelliğindeki veri birincil seri için kullanılır.

### Tanım:
```python
@property
def categories(self):
    ...
```

### Ayrıca Bakınız
* sınıf [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection)
* sınıf [`IChartData`](/slides/python-net/tr/aspose.slides.charts/ichartdata)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)