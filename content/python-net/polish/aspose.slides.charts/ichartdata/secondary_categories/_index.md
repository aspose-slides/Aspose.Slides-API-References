---
title: secondary_categories property
second_title: Aspose.Slides dla Pythona via .NET - Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories właściwość
Pobiera drugorzędne kategorie, jeśli właściwość [`IChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories) jest prawdziwa.
            Tylko do odczytu [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection).

### Uwagi

Jeśli właściwość [`IChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories) jest fałszywa, to ta właściwość [`IChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/secondary_categories) zwraca None i dane w właściwość [`IChartData.categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/categories) są używane zarówno dla serii głównej, jak i pomocniczej.
Jeśli właściwość [`IChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories) jest prawdziwa, to dane w tej właściwość [`IChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/secondary_categories) są używane dla serii pomocniczej, a dane w właściwość [`IChartData.categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/categories) są używane dla serii głównej.

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