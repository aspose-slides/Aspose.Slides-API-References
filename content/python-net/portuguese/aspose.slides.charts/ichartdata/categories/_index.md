---
title: categories property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/ichartdata/categories/
weight: 80
---
## categories propriedade
Obtém as categorias primárias (ou tanto as categorias primárias quanto as secundárias se a [`IChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/use_secondary_categories) propriedade for false). Somente leitura [`IChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection).

### Observações

Se a [`IChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/use_secondary_categories) propriedade for false então a [`IChartData.secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/secondary_categories) propriedade retorna None e os dados nesta [`IChartData.categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/categories) propriedade são usados tanto para séries primárias quanto para séries secundárias. Se a [`IChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/use_secondary_categories) propriedade for true então os dados na [`IChartData.secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/secondary_categories) propriedade são usados para séries secundárias e os dados nesta [`IChartData.categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/categories) propriedade são usados para séries primárias.

### Definição:
```python
@property
def categories(self):
    ...
```

### Veja também
* classe [`IChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection)
* classe [`IChartData`](/slides/python-net/pt/aspose.slides.charts/ichartdata)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)