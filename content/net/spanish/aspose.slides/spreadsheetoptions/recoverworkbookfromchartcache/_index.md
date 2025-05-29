---
title: RecoverWorkbookFromChartCache
second_title: Aspose.Slides para .NET Referencia de API
description: Si la fuente de datos para el gráfico es un libro de trabajo externo y no está disponible, se recuperará del caché del gráfico.
type: docs
weight: 30
url: /es/aspose.slides/spreadsheetoptions/recoverworkbookfromchartcache/
---

## Propiedad SpreadsheetOptions.RecoverWorkbookFromChartCache

Si la fuente de datos para el gráfico es un libro de trabajo externo y no está disponible, se recuperará del caché del gráfico.

```csharp
public bool RecoverWorkbookFromChartCache { get; set; }
```

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Lanzada cuando el libro de trabajo externo no está disponible y el valor de la propiedad RecoverWorkbookFromChartCache es falso. |

### Ejemplos

Ejemplo:

```csharp
[C#]
LoadOptions loadOptions = new LoadOptions
{
    SpreadsheetOptions = new SpreadsheetOptions
    {
        RecoverWorkbookFromChartCache = true
    }
};

using (Presentation pres = new Presentation("Presentation.pptx", loadOptions))
{
    IChart chart = pres.Slides[0].Shapes[0] as IChart;
    IChartDataWorkbook recoveredWorkbook = chart.ChartData.ChartDataWorkbook;
}
```

### Véase También

* clase [SpreadsheetOptions](../../spreadsheetoptions)
* espacio de nombres [Aspose.Slides](../../spreadsheetoptions)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->