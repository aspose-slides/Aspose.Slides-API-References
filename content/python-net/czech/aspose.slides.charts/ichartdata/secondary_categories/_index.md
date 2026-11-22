---
title: secondary_categories property
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartdata/secondary_categories/
weight: 130
---
## secondary_categories vlastnost
Získá sekundární kategorie, pokud je vlastnost [`IChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories) pravda.
            Pouze pro čtení [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection).

### Poznámky

If [`IChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories) property is false then this [`IChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/secondary_categories) 
            property return None and data in [`IChartData.categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/categories) property is used both for primary 
            and secondary series.
            If [`IChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories) property is true then data in 
            this [`IChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/secondary_categories) property is used for secondary series and data 
            in [`IChartData.categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/categories) property is used for primary series.

### Definice:
```python
@property
def secondary_categories(self):
    ...
```

### Viz také
* třída [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection)
* třída [`IChartData`](/slides/python-net/cs/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)