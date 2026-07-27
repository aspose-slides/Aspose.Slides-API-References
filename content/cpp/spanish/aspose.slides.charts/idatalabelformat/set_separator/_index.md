---
title: set_Separator()
second_title: Referencia de API de Aspose.Slides para C++
description: "Establece o devuelve un Variant que representa el separador usado para las etiquetas de datos en un gráfico. Escriba System::String."
type: docs
weight: 339
url: /es/aspose.slides.charts/idatalabelformat/set_separator/
---
## IDataLabelFormat::set_Separator(System::String) método

Establece o devuelve un Variant que representa el separador usado para las etiquetas de datos en un gráfico. Escriba [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_Separator(System::String value)=0
```

## Observaciones

Si el padre de este objeto [DataLabelFormat](../../datalabelformat/) es una colección [DataLabelCollection](../../datalabelcollection/) de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad Separator para las nuevas etiquetas de datos en la colección [DataLabelCollection](../../datalabelcollection/). Establecer esta propiedad con un valor también asigna ese valor a la propiedad Separator de todas las etiquetas de datos en la colección [DataLabelCollection](../../datalabelcollection/) (es decir, "DataLabels.DefaultDataLabelFormat.Separator = val;" hace que todos DataLabels[i].Separator sean iguales a val).

## Véase también

* Clase [String](../../../system/string/)
* Clase [IDataLabelFormat](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)