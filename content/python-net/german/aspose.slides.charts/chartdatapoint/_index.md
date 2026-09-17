---
title: ChartDataPoint class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint Klasse

Stellt einen Serien-Datenpunkt dar.

Der Typ ChartDataPoint stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`x_value`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Nur lesbar [`IStringOrDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Nur lesbar [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Nur lesbar [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Nur lesbar [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/size_value/) | Gibt den Größenwert des Diagrammdatenpunkts zurück.<br/>            Wird verwendet mit Treemap- und Sunburst-Diagrammen. <br/>            Nur lesbar [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/color_value/) | Gibt den Farbwert des Diagrammdatenpunkts zurück.<br/>            Wird verwendet mit Karten-Diagrammen. <br/>            Nur lesbar [`IDoubleChartValue`](/slides/python-net/de/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Stellt die Werte der Serien-Fehlerbalken dar, falls der Typ Custom verwendet wird.<br/>            Nur lesbar [`IErrorBarsCustomValues`](/slides/python-net/de/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/label/) | Beschriftung.<br/>            Nur lesbar [`IDataLabel`](/slides/python-net/de/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Gibt an, dass die Blasen einen 3-D-Effekt erhalten.<br/>            Lesen/Schreiben **bool**. |
| [`explosion`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/explosion/) | Gibt an, um welchen Betrag der Datenpunkt vom Zentrum des Kreisdiagramms verschoben wird.<br/>            Lesen/Schreiben **int**. |
| [`format`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/format/) | Stellt die Formatierungseigenschaften dar.<br/>            Lesen/Schreiben [`IFormat`](/slides/python-net/de/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/marker/) | Gibt einen Datenmarker an.<br/>            Nur lesbar [`IMarker`](/slides/python-net/de/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/set_as_total/) | Setzt den Datenpunkt als Gesamtwert. Wird nur für den Serien-Typ Waterfall verwendet. |
| [`related_legend_entry`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Eigenschaften des entsprechenden Legendeneintrags im Falle eines Diagrammtyps aus dieser Liste:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Nur lesbar [`ILegendEntryProperties`](/slides/python-net/de/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/data_point_levels/) | Gibt den Container der Datenpunkteniveaus zurück. Wird für Treeamp- und Sunburst-Serien verwendet.<br/>            Die Indizierung der Datenpunkteniveaus beginnt bei Null. |
| [`index`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Gibt an, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist.<br/>            Lesen/Schreiben **bool**. |
| [`actual_x`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/actual_x/) | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an.<br/>            Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. <br/>            Nur lesbar **float**. |
| [`actual_y`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/actual_y/) | Gibt die tatsächliche y-Position (oben) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an.<br/>            Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. <br/>            Nur lesbar **float**. |
| [`actual_width`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/actual_width/) | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. <br/>            Nur lesbar **float**. |
| [`actual_height`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/actual_height/) | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. <br/>            Nur lesbar **float**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`remove(self)`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/remove/#) | Entfernt DataPoint aus der Diagrammserie. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/de/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Gibt eine automatische Farbe des Datenpunkts zurück, basierend auf dem Serien-Index, dem Datenpunkt-Index, der Eigenschaft ParentSeriesGroup.IsColorVaried und dem Diagrammstil.<br/>            Diese Farbe wird standardmäßig verwendet, wenn FillType gleich NotDefined ist. |


### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)