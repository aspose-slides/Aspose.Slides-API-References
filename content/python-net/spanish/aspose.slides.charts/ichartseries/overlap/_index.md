---
title: overlap property
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## propiedad overlap
Especifica cuánto se superponen las barras y columnas en los gráficos 2-D, como un porcentaje (de -100% a 100%). 
            Esta es la propiedad no solo de esta serie, sino de todas las series del grupo de series principal. 
            Es una proyección de la propiedad correspondiente en el grupo de series principal, por lo que esta propiedad es de solo lectura.
            Para cambiar el valor, use la propiedad ParentSeriesGroup.Overlap de lectura/escritura.
            Solo lectura **int**.


### Observaciones

Overlap especifica el grado de superposición o espaciado entre barras y columnas como un porcentaje de su ancho:
            - -100%: Espaciado máximo (las barras están completamente separadas).
            - 0%: Las barras se colocan una al lado de la otra sin superposición ni espaciado.
            - 100%: Superposición máxima (las barras se superponen completamente entre sí).
            Esta es una proyección de la propiedad ParentSeriesGroup.Overlap.

### Definición:
```python
@property
def overlap(self):
    ...
```


### Ver también
* clase [`IChartSeries`](/slides/python-net/es/aspose.slides.charts/ichartseries)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)