---
title: show_series_name property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name property
Devuelve o establece un Boolean para indicar el comportamiento de visualización del nombre de la serie en las etiquetas de datos de un gráfico. 
            True para mostrar el nombre de la serie. False para ocultarlo.
            Lectura/escritura **bool**.


### Observaciones

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta
            propiedad obtiene o establece el valor predeterminado de la propiedad ShowSeriesName para las nuevas etiquetas 
            de datos en la colección DataLabelCollection.
            Establecer esta propiedad con un valor también asigna este valor a la propiedad ShowSeriesName 
            para todas las etiquetas de datos en la colección DataLabelCollection
            (es decir, "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" hace que 
            todas DataLabels[i].ShowSeriesName sean iguales a val).

### Definición:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### Ver también
* clase [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)