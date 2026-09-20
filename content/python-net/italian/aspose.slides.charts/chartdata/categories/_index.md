---
title: categories property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/chartdata/categories/
weight: 70
---
## proprietà categorie
Restituisce le categorie primarie (o sia le categorie primarie che secondarie 
            se la proprietà [`ChartData.use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/chartdata/use_secondary_categories) è false). 
            Solo lettura [`IChartCategoryCollection`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection).

### Osservazioni

Se la proprietà [`ChartData.use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/chartdata/use_secondary_categories) è false allora [`ChartData.secondary_categories`](/slides/python-net/it/aspose.slides.charts/chartdata/secondary_categories) 
            la proprietà restituisce None e i dati in questa proprietà [`ChartData.categories`](/slides/python-net/it/aspose.slides.charts/chartdata/categories) sono usati sia per le serie primarie 
            e secondarie.
Se la proprietà [`ChartData.use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/chartdata/use_secondary_categories) è true allora i dati in [`ChartData.secondary_categories`](/slides/python-net/it/aspose.slides.charts/chartdata/secondary_categories) 
            la proprietà è usata per le serie secondarie e i dati in questa proprietà [`ChartData.categories`](/slides/python-net/it/aspose.slides.charts/chartdata/categories) sono usati 
            per le serie primarie.

### Definizione:
```python
@property
def categories(self):
    ...
```

### Vedi anche
* classe [`ChartData`](/slides/python-net/it/aspose.slides.charts/chartdata)
* classe [`IChartCategoryCollection`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)