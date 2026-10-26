---
title: categories property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## categories proprietà
Restituisce le categorie primarie (o sia le categorie primarie che quelle secondarie 
            se la proprietà [`IChartData.use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/use_secondary_categories) è falsa).
            Solo lettura [`IChartCategoryCollection`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection).

### Osservazioni
Se la proprietà [`IChartData.use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/use_secondary_categories) è falsa, allora la proprietà [`IChartData.secondary_categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/secondary_categories) 
            restituisce None e i dati in questa proprietà [`IChartData.categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/categories) sono usati sia per le serie primarie 
            che per quelle secondarie.
Se la proprietà [`IChartData.use_secondary_categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/use_secondary_categories) è vera, allora i dati nella proprietà [`IChartData.secondary_categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/secondary_categories) 
            sono usati per le serie secondarie e i dati in questa proprietà [`IChartData.categories`](/slides/python-net/it/aspose.slides.charts/ichartdata/categories) sono usati 
            per le serie primarie.

### Definizione:
```python
@property
def categories(self):
    ...
```

### Vedi anche
* classe [`IChartCategoryCollection`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection)
* classe [`IChartData`](/slides/python-net/it/aspose.slides.charts/ichartdata)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)