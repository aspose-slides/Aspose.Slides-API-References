---
title: get_Separator()
second_title: Referencia de API de Aspose.Slides para C++
description: "Establece o devuelve un Variant que representa el separador utilizado para las etiquetas de datos en un gráfico. Lea System::String."
type: docs
weight: 326
url: /es/aspose.slides.charts/idatalabelformat/get_separator/
---
## IDataLabelFormat::get_Separator() método

Establece o devuelve un Variant que representa el separador utilizado para las etiquetas de datos en un gráfico. Lea [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_Separator()=0
```

## Observaciones

Si el padre de este objeto [DataLabelFormat](../../datalabelformat/) es una colección [DataLabelCollection](../../datalabelcollection/) de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad Separator para las nuevas etiquetas de datos en la colección [DataLabelCollection](../../datalabelcollection/). Establecer esta propiedad con un valor también asigna ese valor a la propiedad Separator para todas las etiquetas de datos en la colección [DataLabelCollection](../../datalabelcollection/) (p. ej. "DataLabels.DefaultDataLabelFormat.Separator = val;" hace que todas las DataLabels[i].Separator sean iguales a val).

## Ver también

* Clase [String](../../../system/string/)
* Clase [IDataLabelFormat](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)