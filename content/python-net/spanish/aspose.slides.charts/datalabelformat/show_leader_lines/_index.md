---
title: show_leader_lines property
second_title: Referencia API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/datalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines property
Representa el comportamiento de visualización de las líneas guía de la etiqueta de datos de un gráfico especificado. 
            True muestra las líneas guía. False para ocultarlas.
            Lectura/escritura **bool**.

### Observaciones

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLeaderLines para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowLeaderLines para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" causa que todas las DataLabels[i].ShowLeaderLines sean iguales a val).

### Definición:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```

### Ver también
* clase [`DataLabelFormat`](/slides/python-net/es/aspose.slides.charts/datalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)