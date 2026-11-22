---
title: categories property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartdata/categories/
weight: 80
---
## kategoriler özelliği
Birincil kategorileri alır (veya hem birincil hem ikincil kategorileri 
            eğer [`ChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/use_secondary_categories) özelliği false ise).
            Salt okunur [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection).

### Açıklamalar
Eğer [`ChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/use_secondary_categories) özelliği false ise [`ChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/secondary_categories) 
            özelliği None döndürür ve bu [`ChartData.categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/categories) özelliğindeki veri hem birincil 
            hem ikincil seriler için kullanılır.
            Eğer [`ChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/use_secondary_categories) özelliği true ise [`ChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/secondary_categories) 
            özelliğindeki veri ikincil seriler için, bu [`ChartData.categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/categories) özelliğindeki veri ise 
            birincil seriler için kullanılır.

### Tanım:
```python
@property
def categories(self):
    ...
```

### Ayrıca Bakınız
* sınıf [`ChartData`](/slides/python-net/tr/aspose.slides.charts/chartdata)
* sınıf [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)