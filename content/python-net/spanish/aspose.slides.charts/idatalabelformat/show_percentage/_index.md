---
title: show_percentage property
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/idatalabelformat/show_percentage/
weight: 180
---
## propiedad show_percentage
Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. 
True muestra el valor del porcentaje. False lo oculta.
Lectura/escritura **bool**.

### Observaciones

Si el elemento padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta
propiedad obtiene o establece el valor predeterminado de la propiedad ShowPercentage para las nuevas etiquetas de datos en la colección DataLabelCollection.
Establecer esta propiedad con un valor también asigna ese valor a la propiedad ShowPercentage
para todas las etiquetas de datos en la colección DataLabelCollection
(p. ej., "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" hace que
todas las DataLabels[i].ShowPercentage sean iguales a val).

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
* clase [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)