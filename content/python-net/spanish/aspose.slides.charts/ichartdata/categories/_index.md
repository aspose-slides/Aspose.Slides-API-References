---
title: categories property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## categories propiedad
Obtiene las categorías primarias (o tanto las categorías primarias como secundarias si la propiedad [`IChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/use_secondary_categories) es falsa).
Solo lectura [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection).

### Observaciones
Si la propiedad [`IChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/use_secondary_categories) es falsa entonces la propiedad [`IChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/secondary_categories) devuelve None y los datos en esta propiedad [`IChartData.categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/categories) se usan tanto para series primarias como secundarias. Si la propiedad [`IChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/use_secondary_categories) es verdadera entonces los datos en la propiedad [`IChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/secondary_categories) se usan para series secundarias y los datos en esta propiedad [`IChartData.categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/categories) se usan para series primarias.

### Definición:
```python
@property
def categories(self):
    ...
```

### Ver también
* clase [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection)
* clase [`IChartData`](/slides/python-net/es/aspose.slides.charts/ichartdata)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)