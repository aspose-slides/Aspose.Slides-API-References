---
title: GetRange
second_title: Referencia de la API Aspose.Sildes para .NET
description: Obtiene el rango de datos del gráfico.
type: docs
weight: 90
url: /es/aspose.slides.charts/ichartdata/getrange/
---

## Método IChartData.GetRange

Obtiene el rango de datos del gráfico.

```csharp
public string GetRange()
```

### Valor de Retorno

Fórmula del rango de datos de las celdas. Ejemplo: "Sheet1!$A$1:$C$4"

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | El gráfico no utiliza el libro de trabajo como fuente de datos |

### Ejemplos

Ejemplo en C#

```csharp
using (Presentation pres = new Presentation())
{
    IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
    string result = (chart.ChartData as ChartData).GetRange();
}
```

### Véase También

* interfaz [IChartData](../../ichartdata)
* espacio de nombres [Aspose.Slides.Charts](../../ichartdata)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->