---
title: pie_split_by property
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by propiedad
Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra  
en un gráfico de pastel-de-pastel o barra-de-pastel.  
Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre - es la proyección de la propiedad de grupo correspondiente.  
Por lo tanto, esta propiedad es solo lectura.  
Use la propiedad ParentSeriesGroup para acceder al grupo de series padre.  
Use ParentSeriesGroup.PieSplitBy propiedad lectura/escritura para cambiar el valor.  
Solo lectura [`PieSplitType`](/slides/python-net/es/aspose.slides.charts/piesplittype).

### Observaciones

1) Esta es la proyección de la propiedad ParentSeriesGroup.PieSplitBy.  
2) Si el valor de la propiedad es PieSplitType.Custom, puede definir información de división personalizada con la propiedad ParentSeriesGroup.PieSplitCustomPoints.

### Definición:
```python
@property
def pie_split_by(self):
    ...
```

### Ver también
* clase [`IChartSeries`](/slides/python-net/es/aspose.slides.charts/ichartseries)
* enumeración [`PieSplitType`](/slides/python-net/es/aspose.slides.charts/piesplittype)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)