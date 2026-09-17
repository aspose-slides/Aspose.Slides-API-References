---
title: show_label_value_from_cell property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell propiedad
Representa el comportamiento de visualización del valor de la celda de la etiqueta de datos de un gráfico específico. 
            True muestra el valor de la celda. False para ocultar.
            Lectura/escritura **bool**.


### Comentarios

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelValueFromCell para los nuevos datos 
            etiquetas en la colección DataLabelCollection.
            Establecer esta propiedad con un valor también asigna este valor a la propiedad ShowLabelValueFromCell 
            para todas las etiquetas de datos en la colección DataLabelCollection
            (p.ej. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" causa que 
            todas las DataLabels[i].ShowLabelValueFromCell sean iguales a val).

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
* clase [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)