---
title: show_legend_key property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/idatalabelformat/show_legend_key/
weight: 170
---
## propiedad show_legend_key
Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. 
            True si la clave de leyenda de la etiqueta de datos es visible.
            Lectura/escritura **bool**.


### Observaciones

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces este
            propiedad obtiene o establece el valor predeterminado de la propiedad ShowLegendKey para las nuevas etiquetas de datos en la colección DataLabelCollection.
            Establecer esta propiedad con un valor también establece este valor a la propiedad ShowLegendKey 
            para todas las etiquetas de datos en la colección DataLabelCollection
            (p.e. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" causa que todos DataLabels[i].ShowLegendKey sean iguales a val).

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
* clase [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)