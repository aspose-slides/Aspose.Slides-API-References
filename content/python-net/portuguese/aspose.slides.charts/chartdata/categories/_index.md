---
title: categories property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/chartdata/categories/
weight: 70
---
## categories propriedade
Obtém as categorias primárias (ou ambas as categorias primárias e secundárias 
            se [`ChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/use_secondary_categories) propriedade for falsa).
            Somente leitura [`IChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection).


### Observações

Se [`ChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/use_secondary_categories) propriedade for falsa então [`ChartData.secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/secondary_categories) 
            propriedade retorna None e os dados nesta [`ChartData.categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/categories) propriedade são usados tanto para séries primárias 
            e secundárias.
            Se [`ChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/use_secondary_categories) propriedade for verdadeira então os dados na [`ChartData.secondary_categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/secondary_categories) 
            propriedade são usados para séries secundárias e os dados nesta [`ChartData.categories`](/slides/python-net/pt/aspose.slides.charts/chartdata/categories) propriedade são usados 
            para séries primárias.

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