---
title: show_bubble_size property
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides.charts/datalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size propiedad
Representa el comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico especificado. 
            True muestra el valor del tamaño de burbuja. False para ocultarlo.
            Lectura/escritura **bool**.

### Comentarios

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta
            propiedad obtiene o establece el valor predeterminado de la propiedad ShowBubbleSize para las nuevas etiquetas de datos
            en la colección DataLabelCollection.
            Establecer esta propiedad con un valor también establece este valor en la propiedad ShowBubbleSize 
            para todas las etiquetas de datos en la colección DataLabelCollection
            (p.ej. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" causa que 
            todos DataLabels[i].ShowBubbleSize sean iguales a val).

### Definición:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```

### Ver también
* clase [`DataLabelFormat`](/slides/python-net/es/aspose.slides.charts/datalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)