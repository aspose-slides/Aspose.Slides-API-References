---
title: secondary_categories property
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/chartdata/secondary_categories/
weight: 130
---
## secondary_categories właściwość
Pobiera wtórne kategorie, jeśli właściwość [`ChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories) jest prawda.
            Tylko do odczytu [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection).


### Uwagi

Jeśli właściwość [`ChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories) jest fałsz, wtedy ta właściwość [`ChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/secondary_categories) zwraca None i dane w właściwości [`ChartData.categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/categories) są używane zarówno dla serii podstawowej, jak i wtórnej.
            Jeśli właściwość [`ChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories) jest prawda, wtedy dane w tej właściwości [`ChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/secondary_categories) są używane dla serii wtórnej, a dane w właściwości [`ChartData.categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/categories) są używane dla serii podstawowej.

### Definicja:
```python
@property
def secondary_categories(self):
    ...
```


### Zobacz także
* klasa [`ChartData`](/slides/python-net/pl/aspose.slides.charts/chartdata)
* klasa [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)