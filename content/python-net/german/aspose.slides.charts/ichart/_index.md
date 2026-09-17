---
title: IChart class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichart/
---
## IChart Klasse

Stellt ein Grafikdiagramm auf einer Folie dar.

Der IChart-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`plot_visible_cells_only`](/slides/python-net/de/aspose.slides.charts/ichart/plot_visible_cells_only/) | Bestimmt, ob nur die sichtbaren Zellen geplottet werden. False, um sowohl sichtbare als auch ausgeblendete Zellen zu plotten.<br/>            Lese-/Schreib **bool**. |
| [`display_blanks_as`](/slides/python-net/de/aspose.slides.charts/ichart/display_blanks_as/) | Gibt die Art und Weise zurück, wie leere Zellen in einem Diagramm geplottet werden, oder legt sie fest.<br/>            Lese-/Schreib [`DisplayBlanksAsType`](/slides/python-net/de/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/de/aspose.slides.charts/ichart/chart_data/) | Gibt Informationen über die verknüpften oder eingebetteten Daten zurück, die einem Diagramm zugeordnet sind.<br/>            Nur-Lesen [`IChartData`](/slides/python-net/de/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/de/aspose.slides.charts/ichart/has_title/) | Bestimmt, ob ein Diagramm einen sichtbaren Titel hat.<br/>            Lese-/Schreib **bool**. |
| [`chart_title`](/slides/python-net/de/aspose.slides.charts/ichart/chart_title/) | Gibt den Diagrammtitel zurück oder legt ihn fest<br/>            Nur-Lesen [`IChartTitle`](/slides/python-net/de/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/de/aspose.slides.charts/ichart/has_data_table/) | Bestimmt, ob ein Diagramm eine Datentabelle hat.<br/>            Lese-/Schreib **bool**. |
| [`has_legend`](/slides/python-net/de/aspose.slides.charts/ichart/has_legend/) | Bestimmt, ob ein Diagramm eine Legende hat.<br/>            Lese-/Schreib **bool**. |
| [`legend`](/slides/python-net/de/aspose.slides.charts/ichart/legend/) | Gibt eine Legende für ein Diagramm zurück oder legt sie fest.<br/>            Nur-Lesen [`ILegend`](/slides/python-net/de/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/de/aspose.slides.charts/ichart/chart_data_table/) | Gibt die Datentabelle eines Diagramms zurück.<br/>            Nur-Lesen [`IDataTable`](/slides/python-net/de/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/de/aspose.slides.charts/ichart/style/) | Gibt den Diagrammstil zurück oder legt ihn fest.<br/>            Lese-/Schreib [`StyleType`](/slides/python-net/de/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/de/aspose.slides.charts/ichart/type/) | Gibt den Diagrammtyp zurück oder legt ihn fest.<br/>            Lese-/Schreib [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/de/aspose.slides.charts/ichart/plot_area/) | Stellt den Plotbereich eines Diagramms dar.<br/>            Nur-Lesen [`IChartPlotArea`](/slides/python-net/de/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/de/aspose.slides.charts/ichart/rotation_3d/) | Gibt die 3D-Drehung eines Diagramms zurück.<br/>            Nur-Lesen [`IRotation3D`](/slides/python-net/de/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/de/aspose.slides.charts/ichart/back_wall/) | Gibt ein Objekt zurück, mit dem das Format der Rückwand eines 3D-Diagramms geändert werden kann.<br/>            Nur-Lesen [`IChartWall`](/slides/python-net/de/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/de/aspose.slides.charts/ichart/side_wall/) | Gibt ein Objekt zurück, mit dem das Format der Seitenwand eines 3D-Diagramms geändert werden kann.<br/>            Nur-Lesen [`IChartWall`](/slides/python-net/de/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/de/aspose.slides.charts/ichart/floor/) | Gibt ein Objekt zurück, mit dem das Format des Bodens eines 3D-Diagramms geändert werden kann.<br/>            Nur-Lesen [`IChartWall`](/slides/python-net/de/aspose.slides.charts/ichartwall). |
| [`user_shapes`](/slides/python-net/de/aspose.slides.charts/ichart/user_shapes/) | Gibt die Formen an, die über dem Diagramm gezeichnet werden.<br/>            Nur-Lesen [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/de/aspose.slides.charts/ichart/axes/) | Stellt Zugriff auf Diagrammachsen bereit.<br/>            Nur-Lesen [`IAxesManager`](/slides/python-net/de/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/de/aspose.slides.charts/ichart/show_data_labels_over_maximum/) | Gibt an, ob Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen.<br/>            Lese-/Schreib **bool**. |
| [`has_rounded_corners`](/slides/python-net/de/aspose.slides.charts/ichart/has_rounded_corners/) | Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll.<br/>            Lese-/Schreib **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides.charts/ichart/shape_lock/) |  |
| [`graphical_object_lock`](/slides/python-net/de/aspose.slides.charts/ichart/graphical_object_lock/) |  |
| [`is_text_holder`](/slides/python-net/de/aspose.slides.charts/ichart/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/de/aspose.slides.charts/ichart/placeholder/) |  |
| [`custom_data`](/slides/python-net/de/aspose.slides.charts/ichart/custom_data/) |  |
| [`raw_frame`](/slides/python-net/de/aspose.slides.charts/ichart/raw_frame/) |  |
| [`frame`](/slides/python-net/de/aspose.slides.charts/ichart/frame/) |  |
| [`line_format`](/slides/python-net/de/aspose.slides.charts/ichart/line_format/) |  |
| [`three_d_format`](/slides/python-net/de/aspose.slides.charts/ichart/three_d_format/) |  |
| [`effect_format`](/slides/python-net/de/aspose.slides.charts/ichart/effect_format/) |  |
| [`fill_format`](/slides/python-net/de/aspose.slides.charts/ichart/fill_format/) |  |
| [`hidden`](/slides/python-net/de/aspose.slides.charts/ichart/hidden/) |  |
| [`z_order_position`](/slides/python-net/de/aspose.slides.charts/ichart/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/de/aspose.slides.charts/ichart/connection_site_count/) |  |
| [`rotation`](/slides/python-net/de/aspose.slides.charts/ichart/rotation/) |  |
| [`x`](/slides/python-net/de/aspose.slides.charts/ichart/x/) |  |
| [`y`](/slides/python-net/de/aspose.slides.charts/ichart/y/) |  |
| [`width`](/slides/python-net/de/aspose.slides.charts/ichart/width/) |  |
| [`height`](/slides/python-net/de/aspose.slides.charts/ichart/height/) |  |
| [`alternative_text`](/slides/python-net/de/aspose.slides.charts/ichart/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides.charts/ichart/alternative_text_title/) |  |
| [`name`](/slides/python-net/de/aspose.slides.charts/ichart/name/) |  |
| [`is_decorative`](/slides/python-net/de/aspose.slides.charts/ichart/is_decorative/) |  |
| [`unique_id`](/slides/python-net/de/aspose.slides.charts/ichart/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides.charts/ichart/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/de/aspose.slides.charts/ichart/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/de/aspose.slides.charts/ichart/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/de/aspose.slides.charts/ichart/parent_group/) |  |
| [`slide`](/slides/python-net/de/aspose.slides.charts/ichart/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides.charts/ichart/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides.charts/ichart/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides.charts/ichart/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides.charts/ichart/hyperlink_manager/) |  |
| [`text_format`](/slides/python-net/de/aspose.slides.charts/ichart/text_format/) |  |
| [`chart`](/slides/python-net/de/aspose.slides.charts/ichart/chart/) |  |
| [`theme_manager`](/slides/python-net/de/aspose.slides.charts/ichart/theme_manager/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides.charts/ichart/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides.charts/ichart/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides.charts/ichart/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides.charts/ichart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`validate_chart_layout(self)`](/slides/python-net/de/aspose.slides.charts/ichart/validate_chart_layout/#) | Berechnet die tatsächlichen Werte der Diagrammelemente. Tatsächliche Werte beinhalten die Position von Elementen, die das IActualLayout-Interface implementieren <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            und die tatsächlichen Achsenwerte (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides.charts/ichart/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides.charts/ichart/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides.charts/ichart/get_base_placeholder/#) |  |
| [`create_theme_effective(self)`](/slides/python-net/de/aspose.slides.charts/ichart/create_theme_effective/#) |  |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)