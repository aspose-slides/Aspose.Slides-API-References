---
title: categories property
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/chartdata/categories/
weight: 70
---
## kategorie właściwość
Pobiera podstawowe kategorie (lub zarówno podstawowe i drugorzędne kategorie, jeśli [`ChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories) właściwość jest false). Tylko do odczytu [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection).

### Uwagi

Jeśli [`ChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories) właściwość jest false, to [`ChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/secondary_categories) właściwość zwraca None i dane w tej [`ChartData.categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/categories) właściwość są używane zarówno dla podstawowych i drugorzędnych serii. Jeśli [`ChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories) właściwość jest true, to dane w [`ChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/secondary_categories) właściwość są używane dla drugorzędnych serii i dane w tej [`ChartData.categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/categories) właściwość są używane dla podstawowych serii.

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