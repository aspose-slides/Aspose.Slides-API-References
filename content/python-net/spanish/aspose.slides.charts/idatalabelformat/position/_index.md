---
title: position property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/idatalabelformat/position/
weight: 90
---
## propiedad position
Representa la propiedad position de la etiqueta de datos.
Lectura/escritura [`LegendDataLabelPosition`](/slides/python-net/es/aspose.slides.charts/legenddatalabelposition).

### Observaciones

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad Position para las nuevas etiquetas de datos en la colección DataLabelCollection.
Representa la position para los objetos DataLabel.
Establecer esta propiedad con un valor también establece ese valor en la propiedad Position para todas las etiquetas de datos en la colección DataLabelCollection
(p. ej. "DataLabels.DefaultDataLabelFormat.Position = val;" hace que todas las DataLabels[i].Position sean iguales a val).

### Definición:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### Ver también
* clase [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat)
* enumeración [`LegendDataLabelPosition`](/slides/python-net/es/aspose.slides.charts/legenddatalabelposition)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)