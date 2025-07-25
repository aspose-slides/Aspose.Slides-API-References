---
title: Overlap
second_title: Aspose.Sildes for .NET API Reference
description: Gibt an, wie stark sich Balken und Säulen in 2-D-Diagrammen prozentual von -100 bis 100 überlappen sollen. - -100 Höchster Abstand, Balken sind vollständig getrennt. - 0 Balken werden nebeneinander ohne Überlappung oder Abstand platziert. - 100 Maximale Überlappung, Balken überlappen sich vollständig. Diese Eigenschaft ist schreibbar SByte.
type: docs
weight: 120
url: /de/aspose.slides.charts/chartseriesgroup/overlap/
---

## ChartSeriesGroup.Overlap-Eigenschaft

Gibt an, wie stark sich Balken und Säulen in 2-D-Diagrammen prozentual überlappen sollen (von -100% bis 100%). - -100%: Höchster Abstand (Balken sind vollständig getrennt). - 0%: Balken werden nebeneinander ohne Überlappung oder Abstand platziert. - 100%: Maximale Überlappung (Balken überlappen sich vollständig). Diese Eigenschaft ist schreibbar SByte.

```csharp
public sbyte Overlap { get; set; }
```

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | Wird ausgelöst, wenn der Wert außerhalb des gültigen Bereichs von -100 bis 100 festgelegt wird. |

### Beispiele

Das folgende Beispiel zeigt, wie die Überlappung für eine Diagrammseriengruppe festgelegt und das resultierende Diagramm in einem Formular gerendert wird:

```csharp
using (Presentation pres = new Presentation())
{
    IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
    IChartSeriesCollection series = chart.ChartData.Series;
    series[0].ParentSeriesGroup.Overlap = 55; // Überlappung auf 55% setzen

    var image=pres.Slides[0].GetImage(1, 1);
    image.Save("image.png",ImageFormat.Png);
}
```

### Siehe auch

* class [ChartSeriesGroup](../../chartseriesgroup)
* namespace [Aspose.Slides.Charts](../../chartseriesgroup)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->