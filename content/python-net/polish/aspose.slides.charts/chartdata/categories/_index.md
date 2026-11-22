---
title: categories property
second_title: Referencja API Aspose.Slides dla Pythona przez .NET
description: 
type: docs
url: /pl/aspose.slides.charts/chartdata/categories/
weight: 80
---
## właściwość categories
Zwraca pierwsze kategorie (lub zarówno pierwsze, jak i drugorzędne kategorie, jeśli [`ChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories) właściwość jest false).  
Tylko do odczytu [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection).

### Uwagi

Jeśli [`ChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories) właściwość jest false, wtedy [`ChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/secondary_categories) 
            właściwość zwraca None i dane w tej [`ChartData.categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/categories) właściwości są używane zarówno dla serii pierwszej, 
            jak i drugorzędnej.  
Jeśli [`ChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories) właściwość jest true, wtedy dane w [`ChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/secondary_categories) 
            właściwości są używane dla serii drugorzędnej, a dane w tej [`ChartData.categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/categories) właściwości są używane 
            dla serii pierwszej.

### Definicja:
```python
@property
def categories(self):
    ...
```

### Zobacz także
* klasa [`ChartData`](/slides/python-net/pl/aspose.slides.charts/chartdata)
* klasa [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)