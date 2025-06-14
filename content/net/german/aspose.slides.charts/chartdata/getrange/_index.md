---
title: GetRange
second_title: Aspose.Slides für .NET API Referenz
description: Ruft den Datenbereich des Diagramms ab.
type: docs
weight: 90
url: /de/aspose.slides.charts/chartdata/getrange/
---

## ChartData.GetRange-Methode

Ruft den Datenbereich des Diagramms ab.

```csharp
public string GetRange()
```

### Rückgabewert

Zellen-Datenbereichsformel. Z.B.: "Sheet1!$A$1:$C$4"

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidOperationException | Das Diagramm verwendet kein Arbeitsbuch als Datenquelle |

### Beispiele

Beispiel C#

```csharp
using (Presentation pres = new Presentation())
{
    IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
    string result = (chart.ChartData as ChartData).GetRange();
}
```

### Siehe auch

* Klasse [ChartData](../../chartdata)
* Namespace [Aspose.Slides.Charts](../../chartdata)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->