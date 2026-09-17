---
title: show_bubble_size property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/idatalabelformat/show_bubble_size/
weight: 120
---
## propiedad show_bubble_size
Representa el comportamiento de visualización del valor del tamaño de la burbuja de la etiqueta de datos de un gráfico especificado.  
True muestra el valor del tamaño de la burbuja. False lo oculta.  
Lectura/escritura **bool**.

### Remarks
Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta  
propiedad obtiene o establece el valor predeterminado de la propiedad ShowBubbleSize para las nuevas  
etiquetas de datos en la colección DataLabelCollection.  
Establecer esta propiedad con un valor también asigna ese valor a la propiedad ShowBubbleSize  
para todas las etiquetas de datos en la colección DataLabelCollection  
(p. ej. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" provoca que  
todos DataLabels[i].ShowBubbleSize sean iguales a val).

### Definition:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```

### See Also
* clase [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)