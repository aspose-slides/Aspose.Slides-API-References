---
title: secondary_categories property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories propiedad
Obtiene las categorías secundarias si la propiedad [`IChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/use_secondary_categories) es verdadera.
            Solo lectura [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection).

### Observaciones

Si la propiedad [`IChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/use_secondary_categories) es falsa, entonces esta propiedad [`IChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/secondary_categories) 
            devuelve None y los datos en la propiedad [`IChartData.categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/categories) se utilizan tanto para la serie primaria como para la serie secundaria.
            Si la propiedad [`IChartData.use_secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/use_secondary_categories) es verdadera, entonces los datos en esta propiedad [`IChartData.secondary_categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/secondary_categories) se utilizan para la serie secundaria y los datos en la propiedad [`IChartData.categories`](/slides/python-net/es/aspose.slides.charts/ichartdata/categories) se utilizan para la serie primaria.

### Definición:
```python
@property
def secondary_categories(self):
    ...
```

### Ver también
* clase [`IChartCategoryCollection`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection)
* clase [`IChartData`](/slides/python-net/es/aspose.slides.charts/ichartdata)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)