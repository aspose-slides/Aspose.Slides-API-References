---
title: categories property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartdata/categories/
weight: 80
---
## propiedad de categorías
Obtiene las categorías primarias (o tanto las categorías primarias como secundarias si la [`IChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/use_secondary_categories) propiedad es falsa). Solo lectura [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection).

### Observaciones

Si la [`IChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/use_secondary_categories) propiedad es falsa, la [`IChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/secondary_categories) propiedad devuelve None y los datos en esta [`IChartData.categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/categories) propiedad se utilizan tanto para series primarias como secundarias.
Si la [`IChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/use_secondary_categories) propiedad es verdadera, los datos en la [`IChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/secondary_categories) propiedad se utilizan para series secundarias y los datos en esta [`IChartData.categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/categories) propiedad se utilizan para series primarias.

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