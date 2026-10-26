---
title: show_legend_key property
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key propiedad
Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. 
            Verdadero si la clave de leyenda de la etiqueta de datos es visible.
            Lectura/escritura **bool**.


### Observaciones

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLegendKey para las nuevas etiquetas de datos en la colección DataLabelCollection.
            Establecer esta propiedad con un valor también asigna ese valor a la propiedad ShowLegendKey para todas las etiquetas de datos en la colección DataLabelCollection (p. ej. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" hace que todas las DataLabels[i].ShowLegendKey sean iguales a val).

### Definición:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```


### Ver también
* clase [`DataLabelFormat`](/slides/python-net/es/aspose.slides.charts/datalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)