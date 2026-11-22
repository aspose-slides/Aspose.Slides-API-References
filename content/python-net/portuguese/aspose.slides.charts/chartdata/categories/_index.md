---
title: categories property
second_title: Aspose.Slides para Python via API de Referência .NET
description: 
type: docs
url: /pt/aspose.slides.charts/chartdata/categories/
weight: 80
---
## categories propriedade
Obtém as categorias principais (ou tanto as categorias principais quanto as secundárias se a propriedade [`ChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/use_secondary_categories) for falsa). Somente leitura [`IChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection).

### Observações

Se a propriedade [`ChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/use_secondary_categories) for falsa então a propriedade [`ChartData.secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/secondary_categories) retornará None e os dados nesta propriedade [`ChartData.categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/categories) são usados tanto para a série principal quanto para a série secundária. Se a propriedade [`ChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/use_secondary_categories) for verdadeira então os dados na propriedade [`ChartData.secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/secondary_categories) são usados para a série secundária e os dados nesta propriedade [`ChartData.categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/categories) são usados para a série principal.

### Definição:
```python
@property
def categories(self):
    ...
```

### Veja Também
* classe [`ChartData`](/slides/python-net/pt/aspose.slides.charts/chartdata)
* classe [`IChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)