---
title: IChartDataPoint class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint Klasse

Stellt einen Datenpunkt der Serie dar.

Der IChartDataPoint-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`x_value`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/x_value/) | Gibt den x-Wert des Diagrammdatenpunkts zurück.<br/>            Nur-lesen [`IStringOrDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/y_value/) | Gibt den y-Wert des Diagrammdatenpunkts zurück.<br/>            Nur-lesen [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/bubble_size/) | Gibt die Blasengröße des Diagrammdatenpunkts zurück.<br/>            Nur-lesen [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/value/) | Gibt den Wert des Diagrammdatenpunkts zurück.<br/>            Nur-lesen [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/size_value/) | Gibt den Größewert des Diagrammdatenpunkts zurück.<br/>            Wird mit Treemap- und Sunburst-Diagrammen verwendet. <br/>            Nur-lesen [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/color_value/) | Gibt den Farbwert des Diagrammdatenpunkts zurück.<br/>            Wird mit Karten-Diagrammen verwendet. <br/>            Nur-lesen [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Stellt die Werte der Fehlerbalken der Serie dar, falls der Werttyp Custom ist.<br/>            Nur-lesen [`IErrorBarsCustomValues`](/slides/python-net/de/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/label/) | Stellt die Bezeichnung des Diagrammdatenpunkts dar.<br/>            Nur-lesen [`IDataLabel`](/slides/python-net/de/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Gibt an, dass die Blasen einen 3-D-Effekt erhalten.<br/>            Lesen/Schreiben **bool**. |
| [`explosion`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/explosion/) | Gibt die Menge an, um die der Datenpunkt vom Zentrum des Kuchendiagramms verschoben wird.<br/>            Lesen/Schreiben **int**. |
| [`format`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/format/) | Stellt die Formatierungseigenschaften dar.<br/>            Lesen/Schreiben [`IFormat`](/slides/python-net/de/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/marker/) | Gibt einen Datenmarker an.<br/>            Nur-lesen [`IMarker`](/slides/python-net/de/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Eigenschaften des entsprechenden Legendeeintrags, falls der Diagrammtyp aus dieser Liste stammt:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Nur-lesen [`ILegendEntryProperties`](/slides/python-net/de/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/set_as_total/) | Setzt den Datenpunkt als Gesamtwert. Wird nur für den Waterfall-Serientyp verwendet. |
| [`invert_if_negative`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Gibt an, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist.<br/>            Lesen/Schreiben **bool**. |
| [`data_point_levels`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Gibt den Container der Datenpunktenebenen zurück. Wird für Treeamp- und Sunburst-Serien verwendet.<br/>            Die Indizierung der Datenpunktenebenen ist nullbasiert. |
| [`index`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/index/) | Bestimmt, auf welche Kindersammlung des übergeordneten Elements dieser Datenpunkt angewendet wird.<br/>            Lesen **int**. |
| [`actual_x`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`remove(self)`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/remove/#) | Entfernt den Datenpunkt aus der Diagrammserie. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Gibt eine automatische Farbe des Datenpunkts zurück, basierend auf dem Serienindex, dem Datenpunktindex, der Eigenschaft ParentSeriesGroup.IsColorVaried und dem Diagrammstil. <br/>            Diese Farbe wird standardmäßig verwendet, wenn FillType gleich NotDefined ist. |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)