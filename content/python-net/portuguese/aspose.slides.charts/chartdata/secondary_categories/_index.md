---
title: secondary_categories property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/chartdata/secondary_categories/
weight: 120
---
## secondary_categories propriedade
Obtém as categorias secundárias se a propriedade [`ChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/use_secondary_categories) for verdadeira.
            Somente leitura [`IChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection).

### Observações

Se a propriedade [`ChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/use_secondary_categories) for falsa então esta [`ChartData.secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/secondary_categories) 
            propriedade retorna None e os dados na propriedade [`ChartData.categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/categories) são usados tanto para a série primária 
            e série secundária.
            Se a propriedade [`ChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/use_secondary_categories) for verdadeira então os dados na 
            esta [`ChartData.secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/secondary_categories) propriedade é usada para a série secundária e os dados 
            na propriedade [`ChartData.categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/categories) é usada para a série primária.

### Definição:
```python
@property
def secondary_categories(self):
    ...
```

### Veja Também
* classe [`ChartData`](/slides/python-net/pt/aspose.slides.charts/chartdata)
* classe [`IChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)