---
title: overlap property
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## overlap propiedad
Especifica cuánto se superponen las barras y columnas en los gráficos 2D, como un porcentaje (de -100% a 100%). 
            Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre. 
            Es una proyección de la propiedad correspondiente en el grupo de series padre, por lo que esta propiedad es de solo lectura.
            Para cambiar el valor, use la propiedad de lectura/escritura **ParentSeriesGroup.Overlap**.
            Solo lectura **int**.


### Comentarios

Overlap especifica el grado de superposición o separación entre las barras y columnas como un porcentaje de su ancho:
            - -100%: Espacio máximo (las barras están completamente separadas).
            - 0%: Las barras se colocan una al lado de la otra sin superposición ni espacio.
            - 100%: Superposición máxima (las barras se superponen completamente entre sí).
            Esta es una proyección de la propiedad **ParentSeriesGroup.Overlap**.

### Definición:
```python
@property
def overlap(self):
    ...
```


### Ver también
* clase [`ChartSeries`](/slides/python-net/es/aspose.slides.charts/chartseries)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)