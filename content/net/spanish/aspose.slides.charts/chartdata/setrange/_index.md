---
title: SetRange
second_title: Referencia de la API de Aspose.Slides para .NET
description: Establecer el rango de datos del gráfico. Las series y categorías se actualizarán en función del nuevo rango de datos. Si la cantidad de series en el rango de datos es mayor que el recuento de series en los datos del gráfico se agregarán al final series adicionales con el mismo tipo como última serie en la colección actual de la colección
type: docs
weight: 120
url: /es/aspose.slides.charts/chartdata/setrange/
---
## ChartData.SetRange method

Establecer el rango de datos del gráfico. Las series y categorías se actualizarán en función del nuevo rango de datos. Si la cantidad de series en el rango de datos es mayor que el recuento de series en los datos del gráfico, se agregarán al final series adicionales con el mismo tipo como última serie en la colección actual de la colección

```csharp
public void SetRange(string formula)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| formula | String | La fórmula del rango de datos de las celdas. Por ejemplo: "Hoja1!$A$1:$C$4", "AlgúnNombreHoja!A1:B100", "Hoja1!$A$1:$B$5;Hoja1!$D$1:$D$5". |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | fórmula es nula. |
| InvalidOperationException | Tipo de gráfico no compatible |
| ArgumentException | la fórmula tiene un formato incorrecto. |

### Ver también

* class [ChartData](../../chartdata)
* espacio de nombres [Aspose.Slides.Charts](../../chartdata)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
