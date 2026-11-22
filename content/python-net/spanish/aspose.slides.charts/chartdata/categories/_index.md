---
title: categories property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/chartdata/categories/
weight: 80
---
## categories propiedad
Obtiene las categorías primarias (o tanto las categorías primarias como las secundarias 
            si la propiedad [`ChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/use_secondary_categories) es false).
            Solo lectura [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection).

### Observaciones

Si la propiedad [`ChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/use_secondary_categories) es false entonces [`ChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/secondary_categories) 
            propiedad devuelve None y los datos en esta [`ChartData.categories`](/slides/python-net/es/aspose.slides.charts/chartdata/categories) propiedad se utilizan tanto para series primarias 
            y secundarias.
            Si la propiedad [`ChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/use_secondary_categories) es true entonces los datos en la [`ChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/secondary_categories) 
            propiedad se utilizan para series secundarias y los datos en esta [`ChartData.categories`](/slides/python-net/es/aspose.slides.charts/chartdata/categories) propiedad se utilizan 
            para series primarias.

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
* biblioteca [`Aspose.Slides`](/slides/python-net)