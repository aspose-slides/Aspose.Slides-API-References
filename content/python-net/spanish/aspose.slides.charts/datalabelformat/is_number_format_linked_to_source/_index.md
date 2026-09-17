---
title: is_number_format_linked_to_source property
second_title: Aspose.Slides para Python a través de .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source propiedad
Lectura/escritura **bool**.

### Observaciones

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta
            propiedad obtiene o establece el valor predeterminado de la propiedad IsNumberFormatLinkedToSource para las nuevas etiquetas de datos en la colección DataLabelCollection.
            Establecer esta propiedad con un valor también asigna este valor a la propiedad IsNumberFormatLinkedToSource
            para todas las etiquetas de datos en la colección DataLabelCollection
            (es decir, "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" hace que
            todas las DataLabels[i].IsNumberFormatLinkedToSource sean iguales a val).

### Definición:
```python
@property
def is_number_format_linked_to_source(self):
    ...

@is_number_format_linked_to_source.setter
def is_number_format_linked_to_source(self, value):
    ...
```

### Ver también
* clase [`DataLabelFormat`](/slides/python-net/es/aspose.slides.charts/datalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)