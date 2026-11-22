---
title: secondary_categories property
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/chartdata/secondary_categories/
weight: 130
---
## secondary_categories propiedad
Obtiene las categorías secundarias si la propiedad [`ChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/use_secondary_categories) es verdadera.
            Solo lectura [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection).

### Observaciones

Si la propiedad [`ChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/use_secondary_categories) es falsa, entonces esta propiedad [`ChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/secondary_categories) 
            devuelve None y los datos en la propiedad [`ChartData.categories`](/slides/python-net/es/aspose.slides.charts/chartdata/categories) se utilizan tanto para la serie primaria 
            como para la secundaria.
            Si la propiedad [`ChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/use_secondary_categories) es verdadera, entonces los datos en esta propiedad [`ChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/chartdata/secondary_categories) 
            se utilizan para la serie secundaria y los datos en la propiedad [`ChartData.categories`](/slides/python-net/es/aspose.slides.charts/chartdata/categories) se utilizan para la serie primaria.

### Definición:
```python
@property
def secondary_categories(self):
    ...
```

### Ver también
* clase [`ChartData`](/slides/python-net/es/aspose.slides.charts/chartdata)
* clase [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)