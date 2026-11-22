---
title: secondary_categories property
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides.charts/chartdata/secondary_categories/
weight: 130
---
## secondary_categories vlastnost
Získá sekundární kategorie, pokud je [`ChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/use_secondary_categories) vlastnost true.
            Pouze pro čtení [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection).

### Poznámky

Pokud je [`ChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/use_secondary_categories) vlastnost false, pak tato [`ChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/secondary_categories) 
            vlastnost vrací None a data v [`ChartData.categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/categories) vlastnost jsou použita jak pro primární 
            a sekundární řady.
            Pokud je [`ChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/use_secondary_categories) vlastnost true, pak data v 
            této [`ChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/secondary_categories) vlastnost jsou použita pro sekundární řady a data 
            v [`ChartData.categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/categories) vlastnost jsou použita pro primární řady.

### Definice:
```python
@property
def secondary_categories(self):
    ...
```

### Viz také
* třída [`ChartData`](/slides/python-net/cs/aspose.slides.charts/chartdata)
* třída [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)