---
title: secondary_categories property
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories proprietà
Restituisce le categorie secondarie se la proprietà [`IChartData.use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/use_secondary_categories) è true.
            Solo lettura [`IChartCategoryCollection`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection).

### Osservazioni

Se la proprietà [`IChartData.use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/use_secondary_categories) è false allora questa proprietà [`IChartData.secondary_categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/secondary_categories) restituisce None e i dati nella proprietà [`IChartData.categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/categories) sono usati sia per le serie primarie che secondarie.
            Se la proprietà [`IChartData.use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/use_secondary_categories) è true, i dati nella proprietà [`IChartData.secondary_categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/secondary_categories) sono usati per le serie secondarie e i dati nella proprietà [`IChartData.categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/categories) sono usati per le serie primarie.

### Definizione:
```python
@property
def secondary_categories(self):
    ...
```

### Vedi anche
* classe [`IChartCategoryCollection`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection)
* classe [`IChartData`](/slides/python-net/it/aspose.slides.charts/ichartdata)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)