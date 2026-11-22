---
title: categories property
second_title: Aspose.Slides dla Pythona – referencja API .NET
description: 
type: docs
url: /pl/aspose.slides.charts/ichartdata/categories/
weight: 80
---
## categories właściwość
Pobiera główne kategorie (lub zarówno główne, jak i dodatkowe kategorie, jeśli [`IChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories) właściwość jest fałsz).  
Tylko do odczytu [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection).

### Uwagi
Jeśli [`IChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories) właściwość jest fałsz, wtedy [`IChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/secondary_categories) właściwość zwraca None i dane w tej [`IChartData.categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/categories) właściwości są używane zarówno dla głównej, jak i dodatkowej serii.  
Jeśli [`IChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories) właściwość jest prawda, wtedy dane w [`IChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/secondary_categories) właściwość są używane dla dodatkowej serii i dane w tej [`IChartData.categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/categories) właściwość są używane dla głównej serii.

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