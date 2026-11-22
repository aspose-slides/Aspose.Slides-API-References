---
title: ChartDataPoint class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint Klasse

Stellt einen Datenpunkt der Serie dar.

Der Typ ChartDataPoint stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/x_value/) | X-Wert.<br/>            Nur lesbar [`IStringOrDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/y_value/) | Y-Wert.<br/>            Nur lesbar [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/bubble_size/) | Blasengröße.<br/>            Nur lesbar [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/value/) | Wert.<br/>            Nur lesbar [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/size_value/) | Gibt den Größenwert des Diagrammdatenpunkts zurück.<br/>            Wird mit Treemap- und Sunburst-Diagrammen verwendet. <br/>            Nur lesbar [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/color_value/) | Gibt den Farbwert des Diagrammdatenpunkts zurück.<br/>            Wird mit Karten-Diagrammen verwendet. <br/>            Nur lesbar [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Stellt die Werte der Fehlerbalken der Serie dar, falls ein benutzerdefinierter Werttyp verwendet wird.<br/>            Nur lesbar [`IErrorBarsCustomValues`](/slides/python-net/de/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/label/) | Bezeichnung.<br/>            Nur lesbar [`IDataLabel`](/slides/python-net/de/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Gibt an, dass die Blasen einen 3-D-Effekt erhalten.<br/>            Lese/Schreib **bool**. |
| [`explosion`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/explosion/) | Gibt an, um welchen Betrag der Datenpunkt vom Mittelpunkt des Kuchendiagramms verschoben wird.<br/>            Lese/Schreib **int**. |
| [`format`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/format/) | Stellt die Formatierungseigenschaften dar.<br/>            Lese/Schreib [`IFormat`](/slides/python-net/de/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/marker/) | Gibt einen Datenmarker an.<br/>            Nur lesbar [`IMarker`](/slides/python-net/de/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/set_as_total/) | Setzt den Datenpunkt als Gesamtwert. Wird nur für den Waterfall-Serientyp angewendet. |
| [`related_legend_entry`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Eigenschaften des entsprechenden Legendeneintrags, falls der Diagrammtyp aus dieser Liste stammt:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Nur lesbar [`ILegendEntryProperties`](/slides/python-net/de/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/data_point_levels/) | Gibt den Container der Datenpunkteniveaus zurück. Wird für Treeamp- und Sunburst-Serien verwendet.<br/>            Die Indizierung der Datenpunkteniveaus beginnt bei Null. |
| [`index`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Gibt an, dass der Datenpunkt seine Farben invertieren soll, wenn der Wert negativ ist.<br/>            Lese/Schreib **bool**. |
| [`cached_value`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/cached_value/) | Ruft den zwischengespeicherten Wert eines Diagrammdatenpunkts ab.<br/>            Nur lesbar [`ICachedChartValue`](/slides/python-net/de/aspose.slides.charts/icachedchartvalue). |
| [`cached_x_value`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/cached_x_value/) | Ruft den zwischengespeicherten X-Wert eines Diagrammdatenpunkts ab.<br/>            Nur lesbar [`ICachedChartValue`](/slides/python-net/de/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/cached_y_value/) | Ruft den zwischengespeicherten Y-Wert eines Diagrammdatenpunkts ab.<br/>            Nur lesbar [`ICachedChartValue`](/slides/python-net/de/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/cached_bubble_size/) | Ruft die zwischengespeicherte Blasengröße eines Diagrammdatenpunkts ab.<br/>            Nur lesbar [`ICachedChartValue`](/slides/python-net/de/aspose.slides.charts/icachedchartvalue). |
| [`actual_x`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/actual_x/) | Gibt die tatsächliche X-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an.<br/>            Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. <br/>            Lesen **float**. |
| [`actual_y`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/actual_y/) | Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an.<br/>            Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. <br/>            Lesen **float**. |
| [`actual_width`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/actual_width/) | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. <br/>            Lesen **float**. |
| [`actual_height`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/actual_height/) | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. <br/>            Lesen **float**. |

## Methoden

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/remove/#) | Entfernt den Datenpunkt aus der Diagrammserie. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Gibt eine automatische Farbe des Datenpunkts zurück, basierend auf dem Serienindex, dem Datenpunktindex, der Eigenschaft ParentSeriesGroup.IsColorVaried und dem Diagrammstil.<br/>            Diese Farbe wird standardmäßig verwendet, wenn FillType gleich NotDefined ist. |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)