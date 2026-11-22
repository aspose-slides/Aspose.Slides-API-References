---
title: secondary_categories property
second_title: Aspose.Slides dla Pythona przez .NET - odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartdata/secondary_categories/
weight: 130
---
## secondary_categories właściwość
Pobiera drugorzędne kategorie, jeśli [`IChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories) właściwość ma wartość true.
Tylko do odczytu [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection).

### Uwagi

Jeśli [`IChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories) właściwość ma wartość false, to ta [`IChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/secondary_categories) właściwość zwraca None, a dane w [`IChartData.categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/categories) właściwość są używane zarówno dla serii głównej, jak i drugorzędnej.  
Jeśli [`IChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories) właściwość ma wartość true, to dane w tej [`IChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/secondary_categories) właściwość są używane dla serii drugorzędnej, a dane w [`IChartData.categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/categories) właściwość są używane dla serii głównej.

### Definicja:
```python
@property
def secondary_categories(self):
    ...
```

### Zobacz także
* klasa [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection)
* klasa [`IChartData`](/slides/python-net/pl/aspose.slides.charts/ichartdata)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)