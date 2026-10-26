---
title: categories property
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## categories vlastnost
Získá primární kategorie (nebo jak primární, tak sekundární kategorie, pokud je [`IChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories) vlastnost false). Pouze ke čtení [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection).

### Poznámky
Pokud je [`IChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories) vlastnost false, pak [`IChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/secondary_categories) vlastnost vrací None a data v této [`IChartData.categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/categories) vlastnost jsou použita jak pro primární, tak pro sekundární řady. Pokud je [`IChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories) vlastnost true, pak data v [`IChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/secondary_categories) vlastnost jsou použita pro sekundární řady a data v této [`IChartData.categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/categories) vlastnost jsou použita pro primární řady.

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