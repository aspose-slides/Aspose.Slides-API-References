---
title: show_percentage property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/datalabelformat/show_percentage/
weight: 180
---
## show_percentage propiedad
Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. 
            True muestra el valor del porcentaje. False lo oculta.
            Lectura/escritura **bool**.

### Observaciones

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta
            propiedad obtiene o establece el valor predeterminado de la propiedad ShowPercentage para las nuevas etiquetas de datos en la colección DataLabelCollection.
            Establecer esta propiedad con un valor también establece ese valor en la propiedad ShowPercentage
            para todas las etiquetas de datos en la colección DataLabelCollection
            (p. ej. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" hace que 
            todos DataLabels[i].ShowPercentage sean iguales a val).

### Definición:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```

### Ver también
* clase [`DataLabelFormat`](/slides/python-net/es/aspose.slides.charts/datalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)