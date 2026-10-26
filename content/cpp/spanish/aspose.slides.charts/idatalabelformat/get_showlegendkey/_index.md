---
title: get_ShowLegendKey()
second_title: Referencia de API de Aspose.Slides para C++
description: Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. Verdadero si la clave de leyenda de la etiqueta de datos es visible. Leer bool.
type: docs
weight: 92
url: /es/aspose.slides.charts/idatalabelformat/get_showlegendkey/
---
## IDataLabelFormat::get_ShowLegendKey() método

Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. Verdadero si la clave de leyenda de la etiqueta de datos es visible. Leer **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLegendKey()=0
```

## Observaciones

Si el elemento padre de este objeto [DataLabelFormat](../../datalabelformat/) es una colección [DataLabelCollection](../../datalabelcollection/) de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLegendKey para las nuevas etiquetas de datos en la colección [DataLabelCollection](../../datalabelcollection/). Establecer esta propiedad con un valor también establece este valor en la propiedad ShowLegendKey para todas las etiquetas de datos en la colección [DataLabelCollection](../../datalabelcollection/) (es decir, \"DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;\" provoca que todos DataLabels[i].ShowLegendKey sea igual a val).

## Ver también

* Clase [IDataLabelFormat](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)