---
title: get_ShowSeriesName()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve un Boolean para indicar el comportamiento de visualización del nombre de la serie en las etiquetas de datos de un gráfico. True para mostrar el nombre de la serie. False para ocultarlo. Leer bool.
type: docs
weight: 170
url: /es/aspose.slides.charts/idatalabelformat/get_showseriesname/
---
## IDataLabelFormat::get_ShowSeriesName() método

Devuelve un Boolean para indicar el comportamiento de visualización del nombre de la serie en las etiquetas de datos de un gráfico. True para mostrar el nombre de la serie. False para ocultarlo. Leer **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowSeriesName()=0
```

## Observaciones

Si el padre de este objeto [DataLabelFormat](../../datalabelformat/) es una colección [DataLabelCollection](../../datalabelcollection/) de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowSeriesName para las nuevas etiquetas de datos en la colección [DataLabelCollection](../../datalabelcollection/). Establecer esta propiedad con un valor también asigna dicho valor a la propiedad ShowSeriesName de todas las etiquetas de datos en la colección [DataLabelCollection](../../datalabelcollection/) (por ejemplo, "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" hace que todas las DataLabels[i].ShowSeriesName sean iguales a val).

## Ver también

* Clase [IDataLabelFormat](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)