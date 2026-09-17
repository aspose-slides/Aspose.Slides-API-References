---
title: show_label_as_data_callout property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/datalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout propiedad
Determina si la etiqueta de datos del gráfico especificado se mostrará como una llamada de datos o como una etiqueta de datos.

            Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces este
            propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelAsDataCallout para las nuevas etiquetas de datos
            en la colección DataLabelCollection.
            Establecer esta propiedad con un valor también establece este valor en la propiedad ShowLabelAsDataCallout
            para todas las etiquetas de datos en la colección DataLabelCollection
            (p.ej. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" causa que
            todas las DataLabels[i].ShowLabelAsDataCallout sean iguales a val).

### Definición:
```python
@property
def show_label_as_data_callout(self):
    ...

@show_label_as_data_callout.setter
def show_label_as_data_callout(self, value):
    ...
```

### Ver también
* clase [`DataLabelFormat`](/slides/python-net/es/aspose.slides.charts/datalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)