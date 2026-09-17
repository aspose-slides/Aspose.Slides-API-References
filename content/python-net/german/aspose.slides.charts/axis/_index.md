---
title: Axis class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/axis/
---
## Axis Klasse

Kapselt das Objekt, das die Achse eines Diagramms darstellt.

Der Axis-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`chart`](/slides/python-net/de/aspose.slides.charts/axis/chart/) | Gibt das übergeordnete Diagramm zurück.<br/>            Nur lesend [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/de/aspose.slides.charts/axis/axis_between_categories/) | Gibt an, ob die Wertachse die Kategorienachse zwischen den Kategorien schneidet.<br/>             Diese Eigenschaft gilt nur für Kategorienachsen und nicht für 3-D-Diagramme.<br/>             Lesen/Schreiben **bool**. |
| [`category_axis_type`](/slides/python-net/de/aspose.slides.charts/axis/category_axis_type/) | Gibt den Typ der Kategorienachse an.<br/>            Lesen/Schreiben [`CategoryAxisType`](/slides/python-net/de/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/de/aspose.slides.charts/axis/cross_at/) | Gibt den Punkt auf der Achse an, an dem die senkrechte Achse sie schneidet.<br/>             Lesen/Schreiben **float**. |
| [`display_unit`](/slides/python-net/de/aspose.slides.charts/axis/display_unit/) | Gibt den Skalierungswert der Anzeigeeinheiten für die Wertachse an.<br/>             Lesen/Schreiben [`DisplayUnitType`](/slides/python-net/de/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/de/aspose.slides.charts/axis/actual_max_value/) | Gibt den tatsächlichen Maximalwert auf der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [`actual_min_value`](/slides/python-net/de/aspose.slides.charts/axis/actual_min_value/) | Gibt den tatsächlichen Minimalwert auf der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [`actual_major_unit`](/slides/python-net/de/aspose.slides.charts/axis/actual_major_unit/) | Gibt die tatsächliche Haupteinheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [`actual_minor_unit`](/slides/python-net/de/aspose.slides.charts/axis/actual_minor_unit/) | Gibt die tatsächliche Nebeneinheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [`actual_major_unit_scale`](/slides/python-net/de/aspose.slides.charts/axis/actual_major_unit_scale/) | Gibt die tatsächliche Skalierung der Haupteinheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [`actual_minor_unit_scale`](/slides/python-net/de/aspose.slides.charts/axis/actual_minor_unit_scale/) | Gibt die tatsächliche Skalierung der Nebeneinheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [`is_automatic_max_value`](/slides/python-net/de/aspose.slides.charts/axis/is_automatic_max_value/) | Gibt an, ob der Maximalwert automatisch zugewiesen wird.<br/>             Lesen/Schreiben **bool**. |
| [`max_value`](/slides/python-net/de/aspose.slides.charts/axis/max_value/) | Gibt den Maximalwert auf der Wertachse an.<br/>             Lesen/Schreiben **float**. |
| [`minor_unit`](/slides/python-net/de/aspose.slides.charts/axis/minor_unit/) | Gibt die Nebeneinheiten für die Datums- oder Wertachse an.<br/>             Lesen/Schreiben **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/de/aspose.slides.charts/axis/is_automatic_minor_unit/) | Gibt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird.<br/>             Lesen/Schreiben **bool**. |
| [`major_unit`](/slides/python-net/de/aspose.slides.charts/axis/major_unit/) | Gibt die Haupteinheiten für die Datums- oder Wertachse an.<br/>             Lesen/Schreiben **float**. |
| [`is_automatic_major_unit`](/slides/python-net/de/aspose.slides.charts/axis/is_automatic_major_unit/) | Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. <br/>            Lesen/Schreiben **bool**. |
| [`is_automatic_min_value`](/slides/python-net/de/aspose.slides.charts/axis/is_automatic_min_value/) | Gibt an, ob der Minimalwert automatisch zugewiesen wird.<br/>             Lesen/Schreiben **bool**. |
| [`min_value`](/slides/python-net/de/aspose.slides.charts/axis/min_value/) | Gibt den Minimalwert auf der Wertachse an.<br/>             Lesen/Schreiben **float**. |
| [`is_logarithmic`](/slides/python-net/de/aspose.slides.charts/axis/is_logarithmic/) | Gibt an, ob der Achsenskalierungstyp der Wertachse logarithmisch ist oder nicht.<br/>             Lesen/Schreiben **bool**. |
| [`log_base`](/slides/python-net/de/aspose.slides.charts/axis/log_base/) | Gibt die logarithmische Basis an. Standardwert ist 10.<br/>             Lesen/Schreiben **float**. |
| [`is_plot_order_reversed`](/slides/python-net/de/aspose.slides.charts/axis/is_plot_order_reversed/) | Gibt an, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst darstellt.<br/>             Lesen/Schreiben **bool**. |
| [`is_visible`](/slides/python-net/de/aspose.slides.charts/axis/is_visible/) | Gibt an, ob die Achse sichtbar ist.<br/>             Lesen/Schreiben **bool**. |
| [`major_tick_mark`](/slides/python-net/de/aspose.slides.charts/axis/major_tick_mark/) | Gibt den Typ der Haupt-Markierung für die angegebene Achse an.<br/>             Lesen/Schreiben [`TickMarkType`](/slides/python-net/de/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/de/aspose.slides.charts/axis/minor_tick_mark/) | Gibt den Typ der Neben-Markierung für die angegebene Achse an.<br/>             Lesen/Schreiben [`TickMarkType`](/slides/python-net/de/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/de/aspose.slides.charts/axis/tick_label_position/) | Gibt die Position der Beschriftungen der Markierungen auf der angegebenen Achse an.<br/>             Lesen/Schreiben [`TickLabelPositionType`](/slides/python-net/de/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/de/aspose.slides.charts/axis/major_unit_scale/) | Gibt die Skalierung der Haupteinheit für die Datumsachse an.<br/>             Lesen/Schreiben [`TimeUnitType`](/slides/python-net/de/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/de/aspose.slides.charts/axis/minor_unit_scale/) | Gibt die Skalierung der Haupteinheit für die Datumsachse an.<br/>             Lesen/Schreiben [`TimeUnitType`](/slides/python-net/de/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/de/aspose.slides.charts/axis/base_unit_scale/) | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird.<br/>            Lesen/Schreiben [`TimeUnitType`](/slides/python-net/de/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/de/aspose.slides.charts/axis/minor_grid_lines_format/) | Gibt das Format der Nebenrasterlinien einer Diagrammachse an.<br/>             Nur lesend [`IChartLinesFormat`](/slides/python-net/de/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/de/aspose.slides.charts/axis/major_grid_lines_format/) | Gibt das Format der Hauptgitterlinien einer Diagrammachse an.<br/>             Nur lesend [`IChartLinesFormat`](/slides/python-net/de/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/de/aspose.slides.charts/axis/show_minor_grid_lines/) | Um Nebenrasterlinien auszublenden, setzen Sie MinorGridLinesFormat.Line.FillFormat.FillType auf FillType.NoFill.<br/>            Nur lesend **bool**. |
| [`show_major_grid_lines`](/slides/python-net/de/aspose.slides.charts/axis/show_major_grid_lines/) | Um Hauptgitterlinien auszublenden, setzen Sie MajorGridLinesFormat.Line.FillFormat.FillType auf FillType.NoFill.<br/>            Nur lesend **bool**. |
| [`format`](/slides/python-net/de/aspose.slides.charts/axis/format/) | Gibt das Format der Achse an.<br/>             Nur lesend [`IAxisFormat`](/slides/python-net/de/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/de/aspose.slides.charts/axis/text_format/) | Gibt das Textformat an.<br/>             Nur lesend [`IChartTextFormat`](/slides/python-net/de/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/de/aspose.slides.charts/axis/title/) | Liefert den Titel der Achse.<br/>             Nur lesend [`IChartTitle`](/slides/python-net/de/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/de/aspose.slides.charts/axis/cross_type/) | Gibt den CrossType auf der angegebenen Achse an, an dem die andere Achse sie kreuzt.<br/>             Lesen/Schreiben [`CrossesType`](/slides/python-net/de/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/de/aspose.slides.charts/axis/position/) | Gibt die Position der Achse an.<br/>             Lesen/Schreiben [`AxisPositionType`](/slides/python-net/de/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/de/aspose.slides.charts/axis/has_title/) | Bestimmt, ob eine Achse einen sichtbaren Titel hat.<br/>            Lesen/Schreiben **bool**. |
| [`number_format`](/slides/python-net/de/aspose.slides.charts/axis/number_format/) | Gibt das Formatzeichenfolge für die Achsenbeschriftungen an.<br/>            Lesen/Schreiben **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/de/aspose.slides.charts/axis/is_number_format_linked_to_source/) | Gibt an, ob das Format mit Quelldaten verknüpft ist.<br/>            Lesen/Schreiben **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/de/aspose.slides.charts/axis/tick_label_rotation_angle/) | Gibt den Rotationswinkel der Markierungsbeschriftungen an.<br/>            Lesen/Schreiben **float**. |
| [`tick_label_spacing`](/slides/python-net/de/aspose.slides.charts/axis/tick_label_spacing/) | Gibt an, wie viele Markierungsbeschriftungen zwischen den gezeichneten Beschriftungen übersprungen werden sollen. Gilt für Kategorien- oder Serienachse.<br/>            Lesen/Schreiben **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/de/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | Gibt den automatischen Abstand der Markierungsbeschriftungen an. Wenn falsch: verwenden Sie die Eigenschaft TickLabelSpacing.<br/>            Lesen/Schreiben **bool**. |
| [`tick_marks_spacing`](/slides/python-net/de/aspose.slides.charts/axis/tick_marks_spacing/) | Gibt an, wie viele Markierungen übersprungen werden sollen, bevor die nächste gezeichnet wird.<br/>            Gilt für Kategorien- oder Serienachse.<br/>            Lesen/Schreiben **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/de/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | Gibt den automatischen Abstand der Markierungen an. Wenn falsch: verwenden Sie die Eigenschaft TickMarksSpacing.<br/>            Lesen/Schreiben **bool**. |
| [`label_offset`](/slides/python-net/de/aspose.slides.charts/axis/label_offset/) | Gibt den Abstand der Beschriftungen von der Achse an. Gilt für Kategorien- oder Datumsachse. Der Wert muss zwischen 0 % und 1000 % liegen.<br/>            Lesen/Schreiben **int**. |
| [`aggregation_type`](/slides/python-net/de/aspose.slides.charts/axis/aggregation_type/) | Gibt den Aggregationstyp der Kategorienachse (Binning) an. Gilt für Kategorien. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [`bin_width`](/slides/python-net/de/aspose.slides.charts/axis/bin_width/) | Gibt die Bin-Breite an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByBinWidth gesetzt ist.<br/>            Gilt für Kategorienachsen. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [`number_of_bins`](/slides/python-net/de/aspose.slides.charts/axis/number_of_bins/) | Gibt die Anzahl der Bins an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByNumberOfBins gesetzt ist.<br/>            Gilt für Kategorienachsen. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [`is_overflow_bin`](/slides/python-net/de/aspose.slides.charts/axis/is_overflow_bin/) | Gibt an, ob ein Überlauf-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Wert des Überlauf-Bins anzupassen. |
| [`is_automatic_overflow_bin`](/slides/python-net/de/aspose.slides.charts/axis/is_automatic_overflow_bin/) | Gibt den automatischen Wert des Überlauf-Bins an. Wenn falsch: verwenden Sie die Eigenschaft OverflowBin. |
| [`overflow_bin`](/slides/python-net/de/aspose.slides.charts/axis/overflow_bin/) | Gibt den benutzerdefinierten Wert des Überlauf-Bins an. Wird verwendet, wenn die Eigenschaft IsAutomaticOverflowBin auf false gesetzt ist und IsOverflowBin true ist. |
| [`is_underflow_bin`](/slides/python-net/de/aspose.slides.charts/axis/is_underflow_bin/) | Gibt an, ob ein Unterlauf-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Wert des Unterlauf-Bins anzupassen. |
| [`is_automatic_underflow_bin`](/slides/python-net/de/aspose.slides.charts/axis/is_automatic_underflow_bin/) | Gibt den automatischen Wert des Unterlauf-Bins an. Wenn falsch: verwenden Sie die Eigenschaft UnderflowBin. |
| [`underflow_bin`](/slides/python-net/de/aspose.slides.charts/axis/underflow_bin/) | Gibt den benutzerdefinierten Wert des Unterlauf-Bins an. Wird verwendet, wenn die Eigenschaft IsAutomaticUnderflowBin auf false gesetzt ist und IsUnderflowBin true ist. |
| [`slide`](/slides/python-net/de/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides.charts/axis/presentation/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/de/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | Setzt die Eigenschaft IAxis.CategoryAxisType mit einem Wert, der basierend auf den Achsendaten automatisch bestimmt wird. |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)