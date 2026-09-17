---
title: ErrorBarsFormat class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat Klasse

Stellt die Fehlerbalken einer Diagrammserie dar. Fehlerbalken-benutzerdefinierte Werte befinden sich in IChartDataPointCollection (in der Eigenschaft [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).

Der Typ ErrorBarsFormat enthält die folgenden Mitglieder:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`type`](/slides/python-net/de/aspose.slides.charts/errorbarsformat/type/) | Ruft den Typ der Fehlerbalken ab oder legt ihn fest. <br/>            Lese-/Schreib [`ErrorBarType`](/slides/python-net/de/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/de/aspose.slides.charts/errorbarsformat/value_type/) | Stellt mögliche Arten dar, wie die Länge der Fehlerbalken bestimmt wird. <br/>            Im Falle eines benutzerdefinierten Werttyps zum Festlegen des Werts verwenden Sie die [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)-Eigenschaft des jeweiligen Datenpunkts in der DataPoints-Sammlung der Serie.<br/>            Im Falle des Werttyps Fixed, Percentage oder StandardDeviation verwenden Sie die Value-Eigenschaft, um den Wert festzulegen.  <br/>            Lese-/Schreib [`ErrorBarValueType`](/slides/python-net/de/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/de/aspose.slides.charts/errorbarsformat/has_end_cap/) | Gibt an, dass an den Fehlerbalken keine Endkappe gezeichnet wird.<br/>            Lese-/Schreib **bool**. |
| [`value`](/slides/python-net/de/aspose.slides.charts/errorbarsformat/value/) | Ruft den Wert ab, der mit den Werttypen Fixed, Percentage und StandardDeviation verwendet wird, um die Länge der Fehlerbalken zu bestimmen, oder legt ihn fest. <br/>            In allen anderen Fällen wird NaN zurückgegeben.<br/>            Lese-/Schreib **float**. |
| [`format`](/slides/python-net/de/aspose.slides.charts/errorbarsformat/format/) | Stellt das Format der Fehlerbalken dar.<br/>            Lese-/Schreib [`IFormat`](/slides/python-net/de/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/de/aspose.slides.charts/errorbarsformat/chart/) | Gibt das übergeordnete Diagramm zurück.<br/>            Nur lesbar [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/de/aspose.slides.charts/errorbarsformat/is_visible/) | Ruft die Sichtbarkeit der Fehlerbalken ab oder legt sie fest.<br/>            Lese-/Schreib **bool**. |
| [`slide`](/slides/python-net/de/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides.charts/errorbarsformat/presentation/) |  |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)