---
title: categories property
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## categories propriedade
Obtém as categorias principais (ou tanto as categorias principais quanto as secundárias 
            se a propriedade [`IChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/use_secondary_categories) for falsa).
            Somente leitura [`IChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection).

### Observações

Se a propriedade [`IChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/use_secondary_categories) for falsa então a propriedade [`IChartData.secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/secondary_categories) 
            retorna None e os dados nesta propriedade [`IChartData.categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/categories) são usados tanto para as séries principais 
            quanto para as séries secundárias.
Se a propriedade [`IChartData.use_secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/use_secondary_categories) for verdadeira então os dados na propriedade [`IChartData.secondary_categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/secondary_categories) 
            são usados para as séries secundárias e os dados nesta propriedade [`IChartData.categories`](/slides/python-net/pt/aspose.slides.charts/ichartdata/categories) são usados 
            para as séries principais.

### Definição:
```python
@property
def categories(self):
    ...
```

### Ver também
* classe [`IChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection)
* classe [`IChartData`](/slides/python-net/pt/aspose.slides.charts/ichartdata)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)