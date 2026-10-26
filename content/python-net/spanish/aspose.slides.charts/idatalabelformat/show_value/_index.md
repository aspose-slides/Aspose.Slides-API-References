---
title: show_value property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## show_value propiedad
Representa el comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico especificado. 
True muestra el valor porcentual. False lo oculta.
Lectura/escritura **bool**.

### Observaciones

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowValue para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece ese valor en la propiedad ShowValue para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.DefaultDataLabelFormat.ShowValue = val;" hace que todos DataLabels[i].ShowValue sea igual a val).

### Definición:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```

### Ver también
* clase [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)