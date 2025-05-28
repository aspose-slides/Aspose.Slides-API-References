---
title: FormatoNúmero
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa la cadena de formato para el objeto DataLabels. Leer/escribir String.
type: docs
weight: 40
url: /es/aspose.slides.charts/datalabelformat/numberformat/
---

## Propiedad DataLabelFormat.NumberFormat

Representa la cadena de formato para el objeto DataLabels. Leer/escribir String.

```csharp
public string NumberFormat { get; set; }
```

### Observaciones

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad NumberFormat para las nuevas etiquetas de datos en la colección DataLabelCollection. Cuando esta propiedad se establece con un valor, ese valor también se establece para la propiedad NumberFormat de todas las etiquetas de datos en la colección DataLabelCollection (es decir, "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" causa que todas las DataLabels[i].NumberFormat sean iguales a val).

### Ejemplos

```csharp
[C#]
series.Labels.DefaultDataLabelFormat.ShowValue = true;
series.Labels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = false;
series.Labels.DefaultDataLabelFormat.NumberFormat = "0.0%";
```

### Véase También

* clase [DataLabelFormat](../../datalabelformat)
* espacio de nombres [Aspose.Slides.Charts](../../datalabelformat)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->