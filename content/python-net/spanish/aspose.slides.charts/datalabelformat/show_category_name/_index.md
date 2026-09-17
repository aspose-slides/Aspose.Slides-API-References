---
title: show_category_name property
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name propiedad
Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado.
            True para mostrar el nombre de categoría de las etiquetas de datos en un gráfico. False para ocultar.
            Lectura/escritura **bool**.


### Observaciones

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowCategoryName property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowCategoryName property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" cause to 
            all DataLabels[i].ShowCategoryName is equal to val).


### Definición:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```


### Véase también
* clase [`DataLabelFormat`](/slides/python-net/es/aspose.slides.charts/datalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)