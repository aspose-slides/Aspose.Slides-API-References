---
title: show_category_name property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name propiedad
Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado.  
True para mostrar el nombre de categoría de las etiquetas de datos en un gráfico. False para ocultar.  
Lectura/escritura **bool**.

### Observaciones

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowCategoryName para las nuevas etiquetas de datos en la colección DataLabelCollection.  
Establecer esta propiedad con un valor también asigna ese valor a la propiedad ShowCategoryName para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" hace que todas las DataLabels[i].ShowCategoryName sean iguales a val).

### Definición:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### Ver también
* clase [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)