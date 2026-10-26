---
title: number_format property
second_title: Referencia API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format propiedad
Representa la cadena de formato para el objeto DataLabels.
Lectura/escritura **str**.


### Observaciones

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad NumberFormat para las nuevas etiquetas de datos en la colección DataLabelCollection.
Cuando esta propiedad se establece con un valor, ese valor también se establece para la propiedad NumberFormat de todas las etiquetas de datos en la colección DataLabelCollection
(p. ej. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" hace que todos los DataLabels[i].NumberFormat sean iguales a val).

### Definición:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### Ver también
* clase [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)