---
title: categories property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/chartdata/categories/
weight: 70
---
## propiedad de categorías
Obtiene las categorías primarias (o tanto las categorías primarias como las secundarias si [`ChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/use_secondary_categories) propiedad es falsa). Solo lectura [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection).


### Observaciones

Si [`ChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/use_secondary_categories) propiedad es falsa entonces [`ChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/secondary_categories) propiedad devuelve None y los datos en esta [`ChartData.categories`](/slides/python-net/es/aspose.slides.charts/chartdata/categories) propiedad se utilizan tanto para series primarias como secundarias. Si [`ChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/use_secondary_categories) propiedad es verdadera entonces los datos en [`ChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/secondary_categories) propiedad se utilizan para series secundarias y los datos en esta [`ChartData.categories`](/slides/python-net/es/aspose.slides.charts/chartdata/categories) propiedad se utilizan para series primarias.

### Definición:
```python
@property
def categories(self):
    ...
```


### Ver también
* clase [`ChartData`](/slides/python-net/es/aspose.slides.charts/chartdata)
* clase [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)