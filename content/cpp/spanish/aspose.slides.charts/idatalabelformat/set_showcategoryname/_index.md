---
title: set_ShowCategoryName()
second_title: Referencia de API de Aspose.Slides for C++
description: Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. True para mostrar el nombre de categoría de las etiquetas de datos en un gráfico. False para ocultarlo. Write bool.
type: docs
weight: 157
url: /es/aspose.slides.charts/idatalabelformat/set_showcategoryname/
---
## IDataLabelFormat::set_ShowCategoryName(bool) método

Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. True para mostrar el nombre de categoría de las etiquetas de datos en un gráfico. False para ocultarlo. Escribir **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowCategoryName(bool value)=0
```

## Observaciones

Si el padre de este objeto [DataLabelFormat](../../datalabelformat/) es una colección [DataLabelCollection](../../datalabelcollection/) de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowCategoryName para las nuevas etiquetas de datos en la colección [DataLabelCollection](../../datalabelcollection/). Establecer esta propiedad con un valor también asigna ese valor a la propiedad ShowCategoryName de todas las etiquetas de datos en la colección [DataLabelCollection](../../datalabelcollection/) (es decir, "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" hace que todas las DataLabels[i].ShowCategoryName sean iguales a val).

## Ver también

* Clase [IDataLabelFormat](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)