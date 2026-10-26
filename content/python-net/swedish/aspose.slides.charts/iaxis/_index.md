---
title: IAxis class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/iaxis/
---
## IAxis klass

Inkapslar objektet som representerar diagrammets axel.

IAxis-typen exponeras följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/sv/aspose.slides.charts/iaxis/axis_between_categories/) | Representerar om värdeaxeln korsar kategoriaxeln mellan kategorier.<br/>            Denna egenskap gäller endast för kategoriaxlar och gäller inte för 3-D-diagram.<br/>            Läs/skriv **bool**. |
| [`cross_at`](/slides/python-net/sv/aspose.slides.charts/iaxis/cross_at/) | Representerar punkten på axeln där den räta axeln korsar den.<br/>            Läs/skriv **float**. |
| [`display_unit`](/slides/python-net/sv/aspose.slides.charts/iaxis/display_unit/) | Anger skalningsvärdet för visningsenheterna för värdeaxeln.<br/>            Läs/skriv [`DisplayUnitType`](/slides/python-net/sv/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/sv/aspose.slides.charts/iaxis/actual_max_value/) | Anger det faktiska maximala värdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [`actual_min_value`](/slides/python-net/sv/aspose.slides.charts/iaxis/actual_min_value/) | Anger det faktiska minsta värdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [`actual_major_unit`](/slides/python-net/sv/aspose.slides.charts/iaxis/actual_major_unit/) | Anger den faktiska huvudenheten för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [`actual_minor_unit`](/slides/python-net/sv/aspose.slides.charts/iaxis/actual_minor_unit/) | Anger den faktiska delenheten för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [`actual_major_unit_scale`](/slides/python-net/sv/aspose.slides.charts/iaxis/actual_major_unit_scale/) | Anger den faktiska huvudenhetsskalan för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [`actual_minor_unit_scale`](/slides/python-net/sv/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | Anger den faktiska delenhetsskalan för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [`is_automatic_max_value`](/slides/python-net/sv/aspose.slides.charts/iaxis/is_automatic_max_value/) | Indikerar om det maximala värdet tilldelas automatiskt.<br/>             Läs/skriv **bool**. |
| [`max_value`](/slides/python-net/sv/aspose.slides.charts/iaxis/max_value/) | Representerar det maximala värdet på värdeaxeln.<br/>             Läs/skriv **float**. |
| [`minor_unit`](/slides/python-net/sv/aspose.slides.charts/iaxis/minor_unit/) | Representerar delenheterna för datum- eller värdeaxeln.<br/>             Läs/skriv **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/sv/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | Indikerar om delenheten för axeln tilldelas automatiskt.<br/>             Läs/skriv **bool**. |
| [`major_unit`](/slides/python-net/sv/aspose.slides.charts/iaxis/major_unit/) | Representerar huvudenheterna för datum- eller värdeaxeln.<br/>             Läs/skriv **float**. |
| [`is_automatic_major_unit`](/slides/python-net/sv/aspose.slides.charts/iaxis/is_automatic_major_unit/) | Indikerar om huvudenheten för axeln tilldelas automatiskt.<br/>            Läs/skriv **bool**. |
| [`is_automatic_min_value`](/slides/python-net/sv/aspose.slides.charts/iaxis/is_automatic_min_value/) | Indikerar om det minsta värdet tilldelas automatiskt.<br/>             Läs/skriv **bool**. |
| [`min_value`](/slides/python-net/sv/aspose.slides.charts/iaxis/min_value/) | Representerar det minsta värdet på värdeaxeln.<br/>             Läs/skriv **float**. |
| [`is_logarithmic`](/slides/python-net/sv/aspose.slides.charts/iaxis/is_logarithmic/) | Representerar om skaltypen för värdeaxeln är logaritmisk eller inte.<br/>             Läs/skriv **bool**. |
| [`log_base`](/slides/python-net/sv/aspose.slides.charts/iaxis/log_base/) | Representerar den logaritmiska basen. Standardvärdet är 10.<br/>             Läs/skriv **float**. |
| [`is_plot_order_reversed`](/slides/python-net/sv/aspose.slides.charts/iaxis/is_plot_order_reversed/) | Representerar om MS PowerPoint ritar datapunkter från sista till första.<br/>             Läs/skriv **bool**. |
| [`is_visible`](/slides/python-net/sv/aspose.slides.charts/iaxis/is_visible/) | Representerar om axeln är synlig.<br/>             Läs/skriv **bool**. |
| [`major_tick_mark`](/slides/python-net/sv/aspose.slides.charts/iaxis/major_tick_mark/) | Representerar typen av huvudstapelflagga för den angivna axeln.<br/>             Läs/skriv [`TickMarkType`](/slides/python-net/sv/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/sv/aspose.slides.charts/iaxis/minor_tick_mark/) | Representerar typen av delstapelflagga för den angivna axeln.<br/>             Läs/skriv [`TickMarkType`](/slides/python-net/sv/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/sv/aspose.slides.charts/iaxis/tick_label_position/) | Representerar positionen för stapelns etiketter på den angivna axeln.<br/>             Läs/skriv [`TickLabelPositionType`](/slides/python-net/sv/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/sv/aspose.slides.charts/iaxis/major_unit_scale/) | Representerar huvudenhetsskalan för datumaxeln.<br/>             Läs/skriv [`TimeUnitType`](/slides/python-net/sv/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/sv/aspose.slides.charts/iaxis/minor_unit_scale/) | Representerar huvudenhetsskalan för datumaxeln.<br/>             Läs/skriv [`TimeUnitType`](/slides/python-net/sv/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/sv/aspose.slides.charts/iaxis/base_unit_scale/) | Anger den minsta tidsenheten som representeras på datumaxeln.<br/>            Läs/skriv [`TimeUnitType`](/slides/python-net/sv/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/sv/aspose.slides.charts/iaxis/minor_grid_lines_format/) | Representerar formatet för delnätlinjer på en diagramaxel.<br/>             Läs-endast [`IChartLinesFormat`](/slides/python-net/sv/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/sv/aspose.slides.charts/iaxis/major_grid_lines_format/) | Representerar formatet för huvudnätlinjer på en diagramaxel.<br/>             Läs-endast [`IChartLinesFormat`](/slides/python-net/sv/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/sv/aspose.slides.charts/iaxis/show_minor_grid_lines/) | Representerar om delnätlinjer visas.<br/>             Läs-endast **bool**. |
| [`show_major_grid_lines`](/slides/python-net/sv/aspose.slides.charts/iaxis/show_major_grid_lines/) | Representerar om huvudnätlinjer visas.<br/>             Läs-endast **bool**. |
| [`format`](/slides/python-net/sv/aspose.slides.charts/iaxis/format/) | Representerar formatet för axeln.<br/>             Läs-endast [`IAxisFormat`](/slides/python-net/sv/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/sv/aspose.slides.charts/iaxis/title/) | Hämtar axelns titel.<br/>             Läs-endast [`IChartTitle`](/slides/python-net/sv/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/sv/aspose.slides.charts/iaxis/cross_type/) | Representerar CrossType på den specificerade axeln där den andra axeln korsar.<br/>             Läs/skriv [`CrossesType`](/slides/python-net/sv/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/sv/aspose.slides.charts/iaxis/position/) | Representerar axelns position.<br/>             Läs/skriv [`AxisPositionType`](/slides/python-net/sv/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/sv/aspose.slides.charts/iaxis/has_title/) | Avgör om en axel har en synlig titel.<br/>            Läs/skriv **bool**. |
| [`number_format`](/slides/python-net/sv/aspose.slides.charts/iaxis/number_format/) | Representerar formatsträngen för axelrubriker.<br/>            Läs/skriv **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/sv/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | Indikerar om formatet är länkat till källdata.<br/>            Läs/skriv **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/sv/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | Representerar rotationsvinkeln för stapelrubriker<br/>            Läs/skriv **float**. |
| [`tick_label_spacing`](/slides/python-net/sv/aspose.slides.charts/iaxis/tick_label_spacing/) | Anger hur många stapelrubriker som ska hoppas över mellan de som ritas.<br/>            Läs/skriv **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/sv/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | Anger värdet för automatiskt avstånd mellan stapelrubriker. Om falskt: använd egenskapen TickLabelSpacing.<br/>            Läs/skriv **bool**. |
| [`tick_marks_spacing`](/slides/python-net/sv/aspose.slides.charts/iaxis/tick_marks_spacing/) | Anger hur många stapelmarkeringar som ska hoppas över innan nästa ritas.<br/>            Tillämpas på kategori- eller serieraxel.<br/>            Läs/skriv **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/sv/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | Anger värdet för automatiskt avstånd mellan stapelmarkeringar. Om falskt: använd egenskapen TickMarksSpacing.<br/>            Läs/skriv **bool**. |
| [`label_offset`](/slides/python-net/sv/aspose.slides.charts/iaxis/label_offset/) | Anger avståndet mellan etiketter och axeln. Tillämpas på kategori- eller datumaxel. Värdet måste vara mellan 0 % och 1000 %.<br/>            Läs/skriv **int**. |
| [`category_axis_type`](/slides/python-net/sv/aspose.slides.charts/iaxis/category_axis_type/) | Anger typen av kategoriaxeln.<br/>            Läs/skriv [`IAxis.category_axis_type`](/slides/python-net/sv/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/sv/aspose.slides.charts/iaxis/aggregation_type/) | Representerar aggregeringstyp för kategoriaxeln (binning). Tillämpas på kategori. Används endast med Histogram- eller HistogramPareto-serier. |
| [`bin_width`](/slides/python-net/sv/aspose.slides.charts/iaxis/bin_width/) | Anger binbredd när egenskapen AggregationType är inställd på AxisAggregationType.ByBinWidth.<br/>            Tillämpar på kategori-axlar. Används endast med Histogram- eller HistogramPareto-serier. |
| [`number_of_bins`](/slides/python-net/sv/aspose.slides.charts/iaxis/number_of_bins/) | Anger antal bin när egenskapen AggregationType är inställd på AxisAggregationType.ByNumberOfBins.<br/>            Tillämpar på kategori-axlar. Används endast med Histogram- eller HistogramPareto-serier. |
| [`is_overflow_bin`](/slides/python-net/sv/aspose.slides.charts/iaxis/is_overflow_bin/) | Anger om overflow-bin används. Använd IsAutomaticOverflowBin och OverflowBin för att justera overflow-bin-värdet. |
| [`is_automatic_overflow_bin`](/slides/python-net/sv/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | Anger automatiskt värde för overflow-bin. Om falskt: använd egenskapen OverflowBin. |
| [`overflow_bin`](/slides/python-net/sv/aspose.slides.charts/iaxis/overflow_bin/) | Anger anpassat värde för overflow-bin. Tillämpas när egenskapen IsAutomaticOverflowBin är falsk och IsOverflowBin är sann. |
| [`is_underflow_bin`](/slides/python-net/sv/aspose.slides.charts/iaxis/is_underflow_bin/) | Anger om underflow-bin används. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflow-bin-värdet. |
| [`is_automatic_underflow_bin`](/slides/python-net/sv/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | Anger automatiskt värde för underflow-bin. Om falskt: använd egenskapen UnderflowBin. |
| [`underflow_bin`](/slides/python-net/sv/aspose.slides.charts/iaxis/underflow_bin/) | Anger anpassat värde för underflow-bin. Tillämpas när egenskapen IsAutomaticUnderflowBin är falsk och IsUnderflowBin är sann. |
| [`text_format`](/slides/python-net/sv/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/sv/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/sv/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides.charts/iaxis/presentation/) |  |

## Metoder

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/sv/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | Ställer in egenskapen IAxis.CategoryAxisType med ett värde som bestäms automatiskt baserat på axeldatan. |

### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)