---
title: secondary_categories property
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories vlastnost
Získá sekundární kategorie, pokud je vlastnost [`IChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories) true.
            Jen pro čtení [`IChartCategoryCollection`](/slides/python-net/cs/aspose.slides.charts/ichartcategorycollection).


### Poznámky

Pokud je vlastnost [`IChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories) false, pak tato [`IChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/secondary_categories) 
            vlastnost vrací None a data ve vlastnosti [`IChartData.categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/categories) jsou použita jak pro primární 
            a sekundární řady.
Pokud je vlastnost [`IChartData.use_secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/use_secondary_categories) true, pak data v 
            této [`IChartData.secondary_categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/secondary_categories) vlastnost jsou použita pro sekundární řady a data 
            ve vlastnosti [`IChartData.categories`](/slides/python-net/cs/aspose.slides.charts/ichartdata/categories) jsou použita pro primární řady.

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