---
title: RecoverWorkbookFromChartCache
second_title: Aspose.Slides für .NET API Referenz
description: Wenn die Datenquelle für das Diagramm eine externe Arbeitsmappe ist und diese nicht verfügbar ist, wird sie aus dem Diagramm-Cache wiederhergestellt.
type: docs
weight: 20
url: /de/aspose.slides/ispreadsheetoptions/recoverworkbookfromchartcache/
---

## ISpreadsheetOptions.RecoverWorkbookFromChartCache Eigenschaft

Wenn die Datenquelle für das Diagramm eine externe Arbeitsmappe ist und diese nicht verfügbar ist, wird sie aus dem Diagramm-Cache wiederhergestellt.

```csharp
public bool RecoverWorkbookFromChartCache { get; set; }
```

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidOperationException | Wird ausgelöst, wenn die externe Arbeitsmappe nicht verfügbar ist und der Wert der Eigenschaft RecoverWorkbookFromChartCache false ist. |

### Beispiele

Beispiel:

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

### Siehe Auch

* Schnittstelle [ISpreadsheetOptions](../../ispreadsheetoptions)
* Namespace [Aspose.Slides](../../ispreadsheetoptions)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->