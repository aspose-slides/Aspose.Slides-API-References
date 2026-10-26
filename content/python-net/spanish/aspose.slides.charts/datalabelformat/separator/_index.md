---
title: separator property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## separator propiedad
Establece o devuelve un Variant que representa el separator utilizado para las etiquetas de datos en un gráfico.
            Lectura/escritura **str**.


### Observaciones

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad Separator para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna ese valor a la propiedad Separator para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.DefaultDataLabelFormat.Separator = val;" provoca que todas las DataLabels[i].Separator sean iguales a val).

### Definición:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```


### Ver también
* clase [`DataLabelFormat`](/slides/python-net/es/aspose.slides.charts/datalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)