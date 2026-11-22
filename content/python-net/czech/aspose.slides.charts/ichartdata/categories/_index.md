---
title: categories property
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartdata/categories/
weight: 80
---
## categories vlastnost
Vrací primární categories (nebo jak primární, tak sekundární categories, pokud je [`IChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories) vlastnost false).

Pouze pro čtení [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection).

### Poznámky

Pokud [`IChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories) vlastnost je false pak [`IChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/secondary_categories) vlastnost vrací None a data v této [`IChartData.categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/categories) vlastnosti jsou použita jak pro primární, tak pro sekundární řady. Pokud [`IChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories) vlastnost je true pak data v [`IChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/secondary_categories) vlastnosti jsou použita pro sekundární řadu a data v této [`IChartData.categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/categories) vlastnosti jsou použita pro primární řadu.

### Definice:
```python
@property
def categories(self):
    ...
```

### Viz také
* třída [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection)
* třída [`IChartData`](/slides/python-net/cs/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)