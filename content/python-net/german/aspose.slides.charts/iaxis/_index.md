---
title: IAxis class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/iaxis/
---
## IAxis Klasse

Kapselt das Objekt, das eine Diagrammachse darstellt.

Der IAxis-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/de/aspose.slides.charts/iaxis/axis_between_categories/) | Gibt an, ob die Werteachse die Kategorienachse zwischen den Kategorien schneidet.<br/>            Diese Eigenschaft gilt nur für Kategorienachsen und ist nicht für 3-D-Diagramme anwendbar.<br/>            Lesen/Schreiben **bool**. |
| [`cross_at`](/slides/python-net/de/aspose.slides.charts/iaxis/cross_at/) | Gibt den Punkt auf der Achse an, an dem die senkrechte Achse sie schneidet.<br/>            Lesen/Schreiben **float**. |
| [`display_unit`](/slides/python-net/de/aspose.slides.charts/iaxis/display_unit/) | Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an.<br/>            Lesen/Schreiben [`DisplayUnitType`](/slides/python-net/de/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/de/aspose.slides.charts/iaxis/actual_max_value/) | Gibt den tatsächlichen Maximalwert der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [`actual_min_value`](/slides/python-net/de/aspose.slides.charts/iaxis/actual_min_value/) | Gibt den tatsächlichen Minimalwert der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [`actual_major_unit`](/slides/python-net/de/aspose.slides.charts/iaxis/actual_major_unit/) | Gibt die tatsächliche Haupteinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [`actual_minor_unit`](/slides/python-net/de/aspose.slides.charts/iaxis/actual_minor_unit/) | Gibt die tatsächliche Nebeneinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [`actual_major_unit_scale`](/slides/python-net/de/aspose.slides.charts/iaxis/actual_major_unit_scale/) | Gibt die tatsächliche Haupt-Einheitsskala der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [`actual_minor_unit_scale`](/slides/python-net/de/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | Gibt die tatsächliche Neben-Einheitsskala der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [`is_automatic_max_value`](/slides/python-net/de/aspose.slides.charts/iaxis/is_automatic_max_value/) | Gibt an, ob der Maximalwert automatisch zugewiesen wird.<br/>             Lesen/Schreiben **bool**. |
| [`max_value`](/slides/python-net/de/aspose.slides.charts/iaxis/max_value/) | Gibt den Maximalwert auf der Werteachse an.<br/>             Lesen/Schreiben **float**. |
| [`minor_unit`](/slides/python-net/de/aspose.slides.charts/iaxis/minor_unit/) | Gibt die Nebeneinheiten für die Datums- oder Werteachse an.<br/>             Lesen/Schreiben **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/de/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | Gibt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird.<br/>             Lesen/Schreiben **bool**. |
| [`major_unit`](/slides/python-net/de/aspose.slides.charts/iaxis/major_unit/) | Gibt die Haupteinheiten für die Datums- oder Werteachse an.<br/>             Lesen/Schreiben **float**. |
| [`is_automatic_major_unit`](/slides/python-net/de/aspose.slides.charts/iaxis/is_automatic_major_unit/) | Gibt an, ob die Haupt-einheit der Achse automatisch zugewiesen wird.<br/>            Lesen/Schreiben **bool**. |
| [`is_automatic_min_value`](/slides/python-net/de/aspose.slides.charts/iaxis/is_automatic_min_value/) | Gibt an, ob der Minimalwert automatisch zugewiesen wird.<br/>             Lesen/Schreiben **bool**. |
| [`min_value`](/slides/python-net/de/aspose.slides.charts/iaxis/min_value/) | Gibt den Minimalwert auf der Werteachse an.<br/>             Lesen/Schreiben **float**. |
| [`is_logarithmic`](/slides/python-net/de/aspose.slides.charts/iaxis/is_logarithmic/) | Gibt an, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht.<br/>             Lesen/Schreiben **bool**. |
| [`log_base`](/slides/python-net/de/aspose.slides.charts/iaxis/log_base/) | Gibt die logarithmische Basis an. Der Standardwert ist 10.<br/>             Lesen/Schreiben **float**. |
| [`is_plot_order_reversed`](/slides/python-net/de/aspose.slides.charts/iaxis/is_plot_order_reversed/) | Gibt an, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst zeichnet.<br/>             Lesen/Schreiben **bool**. |
| [`is_visible`](/slides/python-net/de/aspose.slides.charts/iaxis/is_visible/) | Gibt an, ob die Achse sichtbar ist.<br/>             Lesen/Schreiben **bool**. |
| [`major_tick_mark`](/slides/python-net/de/aspose.slides.charts/iaxis/major_tick_mark/) | Gibt den Typ des Haupt-Achsenstrichs für die angegebene Achse an.<br/>             Lesen/Schreiben [`TickMarkType`](/slides/python-net/de/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/de/aspose.slides.charts/iaxis/minor_tick_mark/) | Gibt den Typ des Neben-Achsenstrichs für die angegebene Achse an.<br/>             Lesen/Schreiben [`TickMarkType`](/slides/python-net/de/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/de/aspose.slides.charts/iaxis/tick_label_position/) | Gibt die Position der Beschriftungen der Achsenstriche auf der angegebenen Achse an.<br/>             Lesen/Schreiben [`TickLabelPositionType`](/slides/python-net/de/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/de/aspose.slides.charts/iaxis/major_unit_scale/) | Gibt die Skalierung der Haupteinheit für die Datumsachse an.<br/>             Lesen/Schreiben [`TimeUnitType`](/slides/python-net/de/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/de/aspose.slides.charts/iaxis/minor_unit_scale/) | Gibt die Skalierung der Haupteinheit für die Datumsachse an.<br/>             Lesen/Schreiben [`TimeUnitType`](/slides/python-net/de/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/de/aspose.slides.charts/iaxis/base_unit_scale/) | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird.<br/>            Lesen/Schreiben [`TimeUnitType`](/slides/python-net/de/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/de/aspose.slides.charts/iaxis/minor_grid_lines_format/) | Gibt das Format der Nebenrasterlinien auf einer Diagrammachse an.<br/>             Nur-Lesen [`IChartLinesFormat`](/slides/python-net/de/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/de/aspose.slides.charts/iaxis/major_grid_lines_format/) | Gibt das Format der Hauptrasterlinien auf einer Diagrammachse an.<br/>             Nur-Lesen [`IChartLinesFormat`](/slides/python-net/de/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/de/aspose.slides.charts/iaxis/show_minor_grid_lines/) | Gibt an, ob die Nebenrasterlinien angezeigt werden.<br/>             Nur-Lesen **bool**. |
| [`show_major_grid_lines`](/slides/python-net/de/aspose.slides.charts/iaxis/show_major_grid_lines/) | Gibt an, ob die Hauptrasterlinien angezeigt werden.<br/>             Nur-Lesen **bool**. |
| [`format`](/slides/python-net/de/aspose.slides.charts/iaxis/format/) | Gibt das Format der Achse an.<br/>             Nur-Lesen [`IAxisFormat`](/slides/python-net/de/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/de/aspose.slides.charts/iaxis/title/) | Liefert den Titel der Achse.<br/>             Nur-Lesen [`IChartTitle`](/slides/python-net/de/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/de/aspose.slides.charts/iaxis/cross_type/) | Gibt den CrossType auf der angegebenen Achse an, an dem die andere Achse sie schneidet.<br/>             Lesen/Schreiben [`CrossesType`](/slides/python-net/de/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/de/aspose.slides.charts/iaxis/position/) | Gibt die Position der Achse an.<br/>             Lesen/Schreiben [`AxisPositionType`](/slides/python-net/de/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/de/aspose.slides.charts/iaxis/has_title/) | Bestimmt, ob eine Achse einen sichtbaren Titel hat.<br/>            Lesen/Schreiben **bool**. |
| [`number_format`](/slides/python-net/de/aspose.slides.charts/iaxis/number_format/) | Gibt die Formatzeichenfolge für die Achsenbeschriftungen an.<br/>            Lesen/Schreiben **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/de/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | Gibt an, ob das Format mit Quelldaten verknüpft ist.<br/>            Lesen/Schreiben **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/de/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | Gibt den Drehwinkel der Achsenbeschriftungen an<br/>            Lesen/Schreiben **float**. |
| [`tick_label_spacing`](/slides/python-net/de/aspose.slides.charts/iaxis/tick_label_spacing/) | Gibt an, wie viele Achsenbeschriftungen zwischen den gezeichneten Beschriftungen übersprungen werden sollen.<br/>            Lesen/Schreiben **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/de/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | Gibt den automatischen Abstand der Achsenbeschriftungen an. Wenn false: verwenden Sie die Eigenschaft TickLabelSpacing.<br/>            Lesen/Schreiben **bool**. |
| [`tick_marks_spacing`](/slides/python-net/de/aspose.slides.charts/iaxis/tick_marks_spacing/) | Gibt an, wie viele Achsenstriche übersprungen werden sollen, bevor der nächste gezeichnet wird.<br/>            Gilt für Kategorien- oder Serienachsen.<br/>            Lesen/Schreiben **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/de/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | Gibt den automatischen Abstand der Achsenstriche an. Wenn false: verwenden Sie die Eigenschaft TickMarksSpacing.<br/>            Lesen/Schreiben **bool**. |
| [`label_offset`](/slides/python-net/de/aspose.slides.charts/iaxis/label_offset/) | Gibt den Abstand der Beschriftungen von der Achse an. Gilt für Kategorien- oder Datumsachsen. Der Wert muss zwischen 0 % und 1000 % liegen.<br/>            Lesen/Schreiben **int**. |
| [`category_axis_type`](/slides/python-net/de/aspose.slides.charts/iaxis/category_axis_type/) | Gibt den Typ der Kategorienachse an.<br/>            Lesen/Schreiben [`IAxis.category_axis_type`](/slides/python-net/de/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/de/aspose.slides.charts/iaxis/aggregation_type/) | Gibt den Aggregationstyp der Kategorienachse (Binning) an. Gilt für Kategorien. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [`bin_width`](/slides/python-net/de/aspose.slides.charts/iaxis/bin_width/) | Gibt die Bin-Breite an, wenn der Property-Wert AggregationType auf AxisAggregationType.ByBinWidth gesetzt ist.<br/>            Gilt für Kategorienachsen. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [`number_of_bins`](/slides/python-net/de/aspose.slides.charts/iaxis/number_of_bins/) | Gibt die Anzahl der Bins an, wenn der Property-Wert AggregationType auf AxisAggregationType.ByNumberOfBins gesetzt ist.<br/>            Gilt für Kategorienachsen. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [`is_overflow_bin`](/slides/python-net/de/aspose.slides.charts/iaxis/is_overflow_bin/) | Gibt an, ob ein Überlauf-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Überlauf-Bin-Wert anzupassen. |
| [`is_automatic_overflow_bin`](/slides/python-net/de/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | Gibt den automatischen Überlauf-Bin-Wert an. Wenn false: verwenden Sie die Eigenschaft OverflowBin. |
| [`overflow_bin`](/slides/python-net/de/aspose.slides.charts/iaxis/overflow_bin/) | Gibt den benutzerdefinierten Wert für den Überlauf-Bin an. Wird angewendet, wenn die Eigenschaft IsAutomaticOverflowBin auf false gesetzt ist und IsOverflowBin den Wert true hat. |
| [`is_underflow_bin`](/slides/python-net/de/aspose.slides.charts/iaxis/is_underflow_bin/) | Gibt an, ob ein Unterlauf-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Unterlauf-Bin-Wert anzupassen. |
| [`is_automatic_underflow_bin`](/slides/python-net/de/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | Gibt den automatischen Unterlauf-Bin-Wert an. Wenn false: verwenden Sie die Eigenschaft UnderflowBin. |
| [`underflow_bin`](/slides/python-net/de/aspose.slides.charts/iaxis/underflow_bin/) | Gibt den benutzerdefinierten Wert für den Unterlauf-Bin an. Wird angewendet, wenn die Eigenschaft IsAutomaticUnderflowBin auf false gesetzt ist und IsUnderflowBin den Wert true hat. |
| [`text_format`](/slides/python-net/de/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/de/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/de/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides.charts/iaxis/presentation/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/de/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | Setzt die Eigenschaft IAxis.CategoryAxisType mit einem Wert, der automatisch basierend auf den Achsendaten ermittelt wird. |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)