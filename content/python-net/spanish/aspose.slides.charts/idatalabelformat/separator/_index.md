---
title: separator property
second_title: Aspose.Slides para Python mediante .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## propiedad Separator
Establece o devuelve un Variant que representa el separador usado para las etiquetas de datos en un gráfico.
            Lectura/escritura **str**.

### Observaciones

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            la propiedad obtiene o establece el valor predeterminado de la propiedad Separator para las nuevas etiquetas
            de datos en la colección DataLabelCollection.
            Establecer esta propiedad con un valor también asigna este valor a la propiedad Separator 
            para todas las etiquetas de datos en la colección DataLabelCollection
            (es decir "DataLabels.DefaultDataLabelFormat.Separator = val;" causa que 
            todas las DataLabels[i].Separator sean iguales a val).

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
* clase [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)