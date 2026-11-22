---
title: secondary_categories property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/ichartdata/secondary_categories/
weight: 130
---
## secondary_categories propriedade
Obtém as categorias secundárias se a propriedade [`IChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/use_secondary_categories) for true.
Somente leitura [`IChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection).


### Observações

Se a propriedade [`IChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/use_secondary_categories) for false, então esta propriedade [`IChartData.secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/secondary_categories) 
            propriedade retorna None e os dados na propriedade [`IChartData.categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/categories) são usados tanto para a série primária 
            e série secundária.
Se a propriedade [`IChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/use_secondary_categories) for true, então os dados em 
            esta propriedade [`IChartData.secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/secondary_categories) é usada para a série secundária e os dados 
            na propriedade [`IChartData.categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/categories) são usados para a série primária.

### Definição:
```python
@property
def secondary_categories(self):
    ...
```


### Veja Também
* classe [`IChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection)
* classe [`IChartData`](/slides/python-net/pt/aspose.slides.charts/ichartdata)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)