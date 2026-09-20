---
title: categories property
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chartdata/categories/
weight: 70
---
## kategorie vlastnost
Získá primární kategorie (nebo jak primární, tak sekundární kategorie 
            pokud je [`ChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/use_secondary_categories) vlastnost false).
            Pouze pro čtení [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection).

### Poznámky

Pokud je [`ChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/use_secondary_categories) vlastnost false, pak [`ChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/secondary_categories) vlastnost vrátí None a data v této [`ChartData.categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/categories) vlastnost jsou použita jak pro primární, tak pro sekundární řady.
            Pokud je [`ChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/use_secondary_categories) vlastnost true, pak data v [`ChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/secondary_categories) vlastnost jsou použita pro sekundární řady a data v této [`ChartData.categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/categories) vlastnost jsou použita pro primární řady.

### Definice:
```python
@property
def categories(self):
    ...
```

### Viz také
* třída [`ChartData`](/slides/python-net/cs/aspose.slides.charts/chartdata)
* třída [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)