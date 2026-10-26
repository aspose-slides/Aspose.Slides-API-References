---
title: secondary_categories property
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/chartdata/secondary_categories/
weight: 120
---
## secondary_categories proprietà
Restituisce le categorie secondarie se la proprietà [`ChartData.use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/chartdata/use_secondary_categories) è vera.
Solo lettura [`IChartCategoryCollection`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection).


### Osservazioni

Se la proprietà [`ChartData.use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/chartdata/use_secondary_categories) è falsa, allora questa proprietà [`ChartData.secondary_categories`](/slides/python-net/it/aspose.slides.charts/chartdata/secondary_categories) restituisce None e i dati nella proprietà [`ChartData.categories`](/slides/python-net/it/aspose.slides.charts/chartdata/categories) sono usati sia per la serie primaria che per la serie secondaria.
Se la proprietà [`ChartData.use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/chartdata/use_secondary_categories) è vera, i dati in questa proprietà [`ChartData.secondary_categories`](/slides/python-net/it/aspose.slides.charts/chartdata/secondary_categories) sono usati per la serie secondaria e i dati nella proprietà [`ChartData.categories`](/slides/python-net/it/aspose.slides.charts/chartdata/categories) sono usati per la serie primaria.

### Definizione:
```python
@property
def secondary_categories(self):
    ...
```


### Vedi anche
* classe [`ChartData`](/slides/python-net/it/aspose.slides.charts/chartdata)
* classe [`IChartCategoryCollection`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)