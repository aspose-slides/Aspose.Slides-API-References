---
title: GetRange
second_title: Aspose.Sildes para .NET Referencia de API
description: Obtiene el rango de datos del gráfico.
type: docs
weight: 90
url: /es/aspose.slides.charts/chartdata/getrange/
---

## Método ChartData.GetRange

Obtiene el rango de datos del gráfico.

```csharp
public string GetRange()
```

### Valor de Retorno

Fórmula del rango de datos de celdas. Ej: "Sheet1!$A$1:$C$4"

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | El gráfico no utiliza el libro de trabajo como fuente de datos |

### Ejemplos

Ejemplo en C#

```csharp
using (Presentation pres = new Presentation())
{
    IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
    string result = (chart.ChartData as ChartData).GetRange();
}
```

### Véase También

* clase [ChartData](../../chartdata)
* espacio de nombres [Aspose.Slides.Charts](../../chartdata)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->