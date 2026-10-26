---
title: secondary_categories property
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/chartdata/secondary_categories/
weight: 120
---
## propiedad secondary_categories
Obtiene las categorías secundarias si la propiedad [`ChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/use_secondary_categories) es verdadera.
            Solo lectura [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection).

### Observaciones
Si la propiedad [`ChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/use_secondary_categories) es falsa entonces esta [`ChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/secondary_categories) 
            propiedad devuelve None y los datos en la propiedad [`ChartData.categories`](/slides/python-net/es/aspose.slides.charts/chartdata/categories) se usan tanto para la primaria 
            y la serie secundaria.
            Si la propiedad [`ChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/use_secondary_categories) es verdadera entonces los datos en 
            esta [`ChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/secondary_categories) propiedad se usan para la serie secundaria y los datos 
            en la propiedad [`ChartData.categories`](/slides/python-net/es/aspose.slides.charts/chartdata/categories) se usan para la serie primaria.

### Definición:
```python
@property
def secondary_categories(self):
    ...
```

### Ver también
* clase [`ChartData`](/slides/python-net/es/aspose.slides.charts/chartdata)
* clase [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection)
* modulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)