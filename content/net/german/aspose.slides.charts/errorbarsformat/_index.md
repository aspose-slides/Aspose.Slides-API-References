---
title: ErrorBarsFormat
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt Fehlerbalken von Diagrammserien dar. Fehlerbalken benutzerdefinierte Werte befinden sich in IChartDataPointCollection im Fehlerbalkenbenutzerdefinierte Werte./ichartdatapoint/errorbarscustomvalues-Eigenschaft.
type: docs
weight: 1590
url: /de/aspose.slides.charts/errorbarsformat/
---

## ErrorBarsFormat-Klasse

Stellt Fehlerbalken von Diagrammserien dar. Fehlerbalken benutzerdefinierte Werte befinden sich in IChartDataPointCollection (in der [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)-Eigenschaft).

```csharp
public class ErrorBarsFormat : DomObject<ChartSeries>, IErrorBarsFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Chart](../../aspose.slides.charts/errorbarsformat/chart) { get; } | Gibt das übergeordnete Diagramm zurück. Schreibgeschützt [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/errorbarsformat/format) { get; set; } | Stellt das Format der Fehlerbalken dar. Lese-/Schreibzugriff [`IFormat`](../iformat). |
| [HasEndCap](../../aspose.slides.charts/errorbarsformat/hasendcap) { get; set; } | Gibt an, dass kein Endkappe auf den Fehlerbalken gezeichnet wird. Lese-/Schreibzugriff Boolean. |
| [IsVisible](../../aspose.slides.charts/errorbarsformat/isvisible) { get; set; } | Ruft die Sichtbarkeit der Fehlerbalken ab oder legt sie fest. Lese-/Schreibzugriff Boolean. |
| [Type](../../aspose.slides.charts/errorbarsformat/type) { get; set; } | Ruft den Typ der Fehlerbalken ab oder legt ihn fest. Lese-/Schreibzugriff [`ErrorBarType`](../errorbartype). |
| [Value](../../aspose.slides.charts/errorbarsformat/value) { get; set; } | Ruft den Wert ab oder legt ihn fest, der mit den Werttypen Fest, Prozentsatz und Standardabweichung verwendet wird, um die Länge der Fehlerbalken zu bestimmen. In jedem anderen Fall wird NaN zurückgegeben. Lese-/Schreibzugriff Single. |
| [ValueType](../../aspose.slides.charts/errorbarsformat/valuetype) { get; set; } | Stellt mögliche Methoden dar, um die Länge der Fehlerbalken zu bestimmen. Im Falle des benutzerdefinierten Wertes verwenden Sie die [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)-Eigenschaft des spezifischen Datenpunkts in der DataPoints-Sammlung der Serie. Im Falle des Wertes Fest, Prozentsatz oder Standardabweichung verwenden Sie die Value-Eigenschaft, um den Wert festzulegen. Lese-/Schreibzugriff [`ErrorBarValueType`](../errorbarvaluetype). |

### Siehe auch

* Klasse [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* Klasse [ChartSeries](../chartseries)
* Schnittstelle [IErrorBarsFormat](../ierrorbarsformat)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->