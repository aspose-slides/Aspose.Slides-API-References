---
title: secondary_categories property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories özelliği
[`IChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/use_secondary_categories) özelliği doğru ise ikincil kategorileri alır.
            Salt-okunur [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection).

### Açıklamalar
Eğer [`IChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/use_secondary_categories) özelliği yanlış ise bu [`IChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/secondary_categories) 
            özellik None döndürür ve [`IChartData.categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/categories) özelliğindeki veri hem birincil 
            hem ikincil seriler.
            Eğer [`IChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/use_secondary_categories) özelliği doğru ise veri 
            bu [`IChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/secondary_categories) özelliği ikincil seriler için kullanılır ve veri 
            [`IChartData.categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/categories) özelliğindeki veri birincil seriler için kullanılır.

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