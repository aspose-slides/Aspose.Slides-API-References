---
title: categories property
second_title: Aspose.Slides dla Pythona – dokumentacja API .NET
description: 
type: docs
url: /pl/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## categories właściwość
Pobiera podstawowe kategorie (lub zarówno podstawowe, jak i drugorzędne kategorie, jeśli [`IChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories) właściwość jest false). 
Tylko do odczytu [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection).


### Uwagi

Jeśli [`IChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories) właściwość jest false, to [`IChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/secondary_categories) właściwość zwraca None i dane w tej [`IChartData.categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/categories) właściwość są używane zarówno dla podstawowej, jak i drugorzędnej serii. 
Jeśli [`IChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories) właściwość jest true, to dane w [`IChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/secondary_categories) właściwość są używane dla drugorzędnej serii i dane w tej [`IChartData.categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/categories) właściwość są używane dla podstawowej serii.

### Definicja:
```python
@property
def categories(self):
    ...
```


### Zobacz także
* klasa [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection)
* klasa [`IChartData`](/slides/python-net/pl/aspose.slides.charts/ichartdata)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)