---
title: SetRange
second_title: Referencia de API de Aspose.Slides para .NET
description: Establecer el rango de datos del gráfico. Las series y categorías se actualizarán en función del nuevo rango de datos. Si la cantidad de series en el rango de datos es mayor que la cantidad de series en los datos del gráfico, se agregarán series adicionales del mismo tipo que la última serie en la colección actual al final de la colección.
type: docs
weight: 120
url: /es/aspose.slides.charts/chartdata/setrange/
---

## Método ChartData.SetRange

Establecer el rango de datos del gráfico. Las series y categorías se actualizarán en función del nuevo rango de datos. Si la cantidad de series en el rango de datos es mayor que la cantidad de series en los datos del gráfico, se agregarán series adicionales del mismo tipo que la última serie en la colección actual al final de la colección.

```csharp
public void SetRange(string formula)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formula | String | La fórmula del rango de datos de las celdas. Ej.: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | formula es null. |
| InvalidOperationException | Tipo de gráfico no soportado |
| ArgumentException | formula tiene un formato incorrecto. |

### Véase también

* clase [ChartData](../../chartdata)
* espacio de nombres [Aspose.Slides.Charts](../../chartdata)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->