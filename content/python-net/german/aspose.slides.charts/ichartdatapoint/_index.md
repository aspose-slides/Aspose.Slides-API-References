---
title: IChartDataPoint class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint Klasse

Stellt einen Datenpunkt einer Serie dar.

The IChartDataPoint type exposes the following members:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/x_value/) | Liefert den x-Wert eines Diagrammdatenpunkts.<br/>            Nur lesend [`IStringOrDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/y_value/) | Liefert den y-Wert eines Diagrammdatenpunkts.<br/>            Nur lesend [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/bubble_size/) | Liefert die Blasengröße eines Diagrammdatenpunkts.<br/>            Nur lesend [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/value/) | Liefert den Wert eines Diagrammdatenpunkts.<br/>            Nur lesend [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`cached_x_value`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/cached_x_value/) | Liefert den zwischengespeicherten X-Wert eines Diagrammdatenpunkts.<br/>            Nur lesend [`ICachedChartValue`](/slides/python-net/de/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/cached_y_value/) | Liefert den zwischengespeicherten Y-Wert eines Diagrammdatenpunkts.<br/>            Nur lesend [`ICachedChartValue`](/slides/python-net/de/aspose.slides.charts/icachedchartvalue). |
| [`cached_value`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/cached_value/) | Liefert den zwischengespeicherten Wert eines Diagrammdatenpunkts.<br/>            Nur lesend [`ICachedChartValue`](/slides/python-net/de/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/cached_bubble_size/) | Liefert die zwischengespeicherte Blasengröße eines Diagrammdatenpunkts.<br/>            Nur lesend [`ICachedChartValue`](/slides/python-net/de/aspose.slides.charts/icachedchartvalue). |
| [`size_value`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/size_value/) | Liefert den Größenwert eines Diagrammdatenpunkts.<br/>            Wird mit Treemap- und Sunburst-Diagrammen verwendet. <br/>            Nur lesend [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/color_value/) | Liefert den Farbwert eines Diagrammdatenpunkts.<br/>            Wird mit Karten-Diagrammen verwendet. <br/>            Nur lesend [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Stellt die Error-Bar-Werte der Serie dar, falls der Werttyp Custom ist.<br/>            Nur lesend [`IErrorBarsCustomValues`](/slides/python-net/de/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/label/) | Stellt die Bezeichnung des Diagrammdatenpunkts dar.<br/>            Nur lesend [`IDataLabel`](/slides/python-net/de/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Gibt an, dass die Blasen einen 3-D-Effekt erhalten.<br/>            Lese-/Schreib-**bool**. |
| [`explosion`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/explosion/) | Gibt den Betrag an, um den der Datenpunkt vom Zentrum des Kuchendiagramms verschoben wird.<br/>            Lese-/Schreib-**int**. |
| [`format`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/format/) | Stellt die Formatierungseigenschaften dar.<br/>            Lese-/Schreib-[`IFormat`](/slides/python-net/de/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/marker/) | Gibt einen Datenmarker an.<br/>            Nur lesend [`IMarker`](/slides/python-net/de/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Eigenschaften des entsprechenden Legendeneintrags, falls der Diagrammtyp aus dieser Liste stammt:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Nur lesend [`ILegendEntryProperties`](/slides/python-net/de/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/set_as_total/) | Setzt den Datenpunkt als Gesamtsumme. Wird nur für den Waterfall-Serientyp verwendet. |
| [`invert_if_negative`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Gibt an, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist.<br/>            Lese-/Schreib-**bool**. |
| [`data_point_levels`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Gibt den Container der Datenpunktenebenen zurück. Wird für TreeMap- und Sunburst-Serien verwendet.<br/>            Die Indizierung der Datenpunktenebenen beginnt bei Null. |
| [`index`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/index/) | Bestimmt, auf welche Kindersammlung des übergeordneten Elements dieser Datenpunkt angewendet wird.<br/>            Lese-**int**. |
| [`actual_x`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/remove/#) | Entfernt den Datenpunkt aus der Diagrammserie. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Gibt eine automatische Farbe des Datenpunkts zurück, basierend auf dem Serien-Index, dem Datenpunkt-Index, der Eigenschaft ParentSeriesGroup.IsColorVaried und dem Diagrammstil.<br/>            Diese Farbe wird standardmäßig verwendet, wenn FillType gleich NotDefined ist. |


### Siehe auch
* module [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)