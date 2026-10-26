---
title: show_leader_lines property
second_title: Aspose.Slides para Python vía referencia de API .NET
description: 
type: docs
url: /es/aspose.slides.charts/idatalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines propiedad
Representa el comportamiento de visualización de las líneas guía de etiquetas de datos de un gráfico especificado. 
True muestra las líneas guía. False para ocultarlas. 
Lectura/escritura **bool**.

### Observaciones
Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLeaderLines para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna ese valor a la propiedad ShowLeaderLines para todas las etiquetas de datos en la colección DataLabelCollection (es decir, "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" hace que todas las DataLabels[i].ShowLeaderLines sea igual a val).

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
* clase [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)