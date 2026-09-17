---
title: position property
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/datalabelformat/position/
weight: 90
---
## position propiedad
Representa la position del data label.
            Lectura/escritura [`LegendDataLabelPosition`](/slides/python-net/es/aspose.slides.charts/legenddatalabelposition).


### Comentarios

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad Position para las nuevas etiquetas de datos en la colección DataLabelCollection.
            Representa la position para los objetos DataLabel.
            Establecer esta propiedad con un valor también asigna ese valor a la propiedad Position para todas las etiquetas de datos en la colección DataLabelCollection
            (p. ej., "DataLabels.DefaultDataLabelFormat.Position = val;" hace que todos los DataLabels[i].Position sean iguales a val).

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
* clase [`DataLabelFormat`](/slides/python-net/es/aspose.slides.charts/datalabelformat)
* enumeración [`LegendDataLabelPosition`](/slides/python-net/es/aspose.slides.charts/legenddatalabelposition)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)