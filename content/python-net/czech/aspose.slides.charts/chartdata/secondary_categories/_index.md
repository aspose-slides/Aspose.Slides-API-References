---
title: secondary_categories property
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chartdata/secondary_categories/
weight: 120
---
## secondary_categories vlastnost
Získává sekundární kategorie, pokud je [`ChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/use_secondary_categories) vlastnost true.
Pouze pro čtení [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection).

### Poznámky

If [`ChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/use_secondary_categories) vlastnost is false then this [`ChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/secondary_categories) 
            vlastnost vrátí None a data v [`ChartData.categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/categories) vlastnost jsou použita jak pro primární, tak pro sekundární sérii.
            If [`ChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/use_secondary_categories) vlastnost is true then data in 
            this [`ChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/secondary_categories) vlastnost je použita pro sekundární sérii a data 
            in [`ChartData.categories`](/slides/python-net/cs/aspose.slides.charts/chartdata/categories) vlastnost je použita pro primární sérii.

### Definice:
```python
@property
def secondary_categories(self):
    ...
```

### Další související
* třída [`ChartData`](/slides/python-net/cs/aspose.slides.charts/chartdata)
* třída [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)