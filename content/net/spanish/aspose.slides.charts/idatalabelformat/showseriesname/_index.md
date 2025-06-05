---
title: ShowSeriesName
second_title: Referencia de la API de Aspose.Slides para .NET
description: Devuelve o establece un valor Booleano para indicar el comportamiento de visualización del nombre de la serie para las etiquetas de datos en un gráfico. Verdadero para mostrar el nombre de la serie. Falso para ocultar. Booleano de lectura/escritura.
type: docs
weight: 140
url: /es/aspose.slides.charts/idatalabelformat/showseriesname/
---

## Propiedad IDataLabelFormat.ShowSeriesName

Devuelve o establece un valor Booleano para indicar el comportamiento de visualización del nombre de la serie para las etiquetas de datos en un gráfico. Verdadero para mostrar el nombre de la serie. Falso para ocultar. Booleano de lectura/escritura.

```csharp
public bool ShowSeriesName { get; set; }
```

### Observaciones

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowSeriesName para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowSeriesName para todas las etiquetas de datos en la colección DataLabelCollection (es decir, "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" causa que todas las DataLabels[i].ShowSeriesName sean iguales a val).

### Véase también

* interfaz [IDataLabelFormat](../../idatalabelformat)
* espacio de nombres [Aspose.Slides.Charts](../../idatalabelformat)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->