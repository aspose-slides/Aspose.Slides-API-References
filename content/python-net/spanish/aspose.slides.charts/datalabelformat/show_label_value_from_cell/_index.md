---
title: show_label_value_from_cell property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell propiedad
Representa el comportamiento de visualización del valor de la celda de la etiqueta de datos de un gráfico especificado. 
            True muestra el valor de la celda. False para ocultar.
            Lectura/escritura **bool**.


### Observaciones

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta
            propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelValueFromCell para las nuevas 
            etiquetas de datos en la colección DataLabelCollection.
            Establecer esta propiedad con un valor también establece este valor a la propiedad ShowLabelValueFromCell 
            para todas las etiquetas de datos en la colección DataLabelCollection
            (es decir, "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" causa que 
            todas DataLabels[i].ShowLabelValueFromCell sea igual a val).

### Definición:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```


### Ver también
* clase [`DataLabelFormat`](/slides/python-net/es/aspose.slides.charts/datalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)