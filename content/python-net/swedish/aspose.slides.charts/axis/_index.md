---
title: Axis class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/axis/
---
## Axis klass

Inkapslar objektet som representerar ett diagramaxel.

Axis-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`chart`](/slides/python-net/sv/aspose.slides.charts/axis/chart/) | Returnerar det överordnade diagrammet.<br/>            Skrivskyddad [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/sv/aspose.slides.charts/axis/axis_between_categories/) | Representerar om värdeaxeln korsar kategoriaxeln mellan kategorier.<br/>             Denna egenskap gäller endast för kategoriaxlar och gäller inte för 3-D-diagram.<br/>             Läs/skriv **bool**. |
| [`category_axis_type`](/slides/python-net/sv/aspose.slides.charts/axis/category_axis_type/) | Anger typen för kategoriaxeln.<br/>            Läs/skriv [`CategoryAxisType`](/slides/python-net/sv/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/sv/aspose.slides.charts/axis/cross_at/) | Representerar punkten på axeln där den vinkelräta axeln korsar den.<br/>             Läs/skriv **float**. |
| [`display_unit`](/slides/python-net/sv/aspose.slides.charts/axis/display_unit/) | Anger skalningsvärdet för visningsenheterna för värdeaxeln.<br/>             Läs/skriv [`DisplayUnitType`](/slides/python-net/sv/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/sv/aspose.slides.charts/axis/actual_max_value/) | Anger det faktiska maximala värdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [`actual_min_value`](/slides/python-net/sv/aspose.slides.charts/axis/actual_min_value/) | Anger det faktiska minimivärdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [`actual_major_unit`](/slides/python-net/sv/aspose.slides.charts/axis/actual_major_unit/) | Anger den faktiska huvudenheten för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [`actual_minor_unit`](/slides/python-net/sv/aspose.slides.charts/axis/actual_minor_unit/) | Anger den faktiska mindre enheten för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [`actual_major_unit_scale`](/slides/python-net/sv/aspose.slides.charts/axis/actual_major_unit_scale/) | Anger den faktiska skalan för huvud enheten på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [`actual_minor_unit_scale`](/slides/python-net/sv/aspose.slides.charts/axis/actual_minor_unit_scale/) | Anger den faktiska skalan för mindre enheten på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [`is_automatic_max_value`](/slides/python-net/sv/aspose.slides.charts/axis/is_automatic_max_value/) | Indikerar om maxvärdet tilldelas automatiskt.<br/>             Läs/skriv **bool**. |
| [`max_value`](/slides/python-net/sv/aspose.slides.charts/axis/max_value/) | Representerar det maximala värdet på värdeaxeln.<br/>             Läs/skriv **float**. |
| [`minor_unit`](/slides/python-net/sv/aspose.slides.charts/axis/minor_unit/) | Representerar de mindre enheterna för datum- eller värdeaxeln.<br/>             Läs/skriv **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/sv/aspose.slides.charts/axis/is_automatic_minor_unit/) | Indikerar om den mindre enheten för axeln tilldelas automatiskt.<br/>             Läs/skriv **bool**. |
| [`major_unit`](/slides/python-net/sv/aspose.slides.charts/axis/major_unit/) | Representerar de större enheterna för datum- eller värdeaxeln.<br/>             Läs/skriv **float**. |
| [`is_automatic_major_unit`](/slides/python-net/sv/aspose.slides.charts/axis/is_automatic_major_unit/) | Indikerar om den större enheten för axeln tilldelas automatiskt. <br/>            Läs/skriv **bool**. |
| [`is_automatic_min_value`](/slides/python-net/sv/aspose.slides.charts/axis/is_automatic_min_value/) | Indikerar om minvärdet tilldelas automatiskt.<br/>             Läs/skriv **bool**. |
| [`min_value`](/slides/python-net/sv/aspose.slides.charts/axis/min_value/) | Representerar det minsta värdet på värdeaxeln.<br/>             Läs/skriv **float**. |
| [`is_logarithmic`](/slides/python-net/sv/aspose.slides.charts/axis/is_logarithmic/) | Representerar om skaletypen för värdeaxeln är logaritmisk eller inte.<br/>             Läs/skriv **bool**. |
| [`log_base`](/slides/python-net/sv/aspose.slides.charts/axis/log_base/) | Representerar den logaritmiska basen. Standardvärdet är 10.<br/>             Läs/skriv **float**. |
| [`is_plot_order_reversed`](/slides/python-net/sv/aspose.slides.charts/axis/is_plot_order_reversed/) | Representerar om MS PowerPoint ritar datapunkter från sista till första.<br/>             Läs/skriv **bool**. |
| [`is_visible`](/slides/python-net/sv/aspose.slides.charts/axis/is_visible/) | Representerar om axeln är synlig.<br/>             Läs/skriv **bool**. |
| [`major_tick_mark`](/slides/python-net/sv/aspose.slides.charts/axis/major_tick_mark/) | Representerar typen av huvudstap för den angivna axeln.<br/>             Läs/skriv [`TickMarkType`](/slides/python-net/sv/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/sv/aspose.slides.charts/axis/minor_tick_mark/) | Representerar typen av mindre stapel för den angivna axeln.<br/>             Läs/skriv [`TickMarkType`](/slides/python-net/sv/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/sv/aspose.slides.charts/axis/tick_label_position/) | Representerar positionen för stapel-etikett på den angivna axeln.<br/>             Läs/skriv [`TickLabelPositionType`](/slides/python-net/sv/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/sv/aspose.slides.charts/axis/major_unit_scale/) | Representerar huvudenhetsskalningen för datumaxeln.<br/>             Läs/skriv [`TimeUnitType`](/slides/python-net/sv/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/sv/aspose.slides.charts/axis/minor_unit_scale/) | Representerar huvudenhetsskalningen för datumaxeln.<br/>             Läs/skriv [`TimeUnitType`](/slides/python-net/sv/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/sv/aspose.slides.charts/axis/base_unit_scale/) | Anger den minsta tidsenheten som representeras på datumaxeln.<br/>            Läs/skriv [`TimeUnitType`](/slides/python-net/sv/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/sv/aspose.slides.charts/axis/minor_grid_lines_format/) | Representerar formatet för mindre rutnät på en diagramaxel.<br/>             Skrivskyddad [`IChartLinesFormat`](/slides/python-net/sv/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/sv/aspose.slides.charts/axis/major_grid_lines_format/) | Representerar formatet för större rutnät på en diagramaxel.<br/>             Skrivskyddad [`IChartLinesFormat`](/slides/python-net/sv/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/sv/aspose.slides.charts/axis/show_minor_grid_lines/) | För att dölja mindre rutnät, sätt MinorGridLinesFormat.Line.FillFormat.FillType till FillType.NoFill.<br/>            Skrivskyddad **bool**. |
| [`show_major_grid_lines`](/slides/python-net/sv/aspose.slides.charts/axis/show_major_grid_lines/) | För att dölja större rutnät, sätt MajorGridLinesFormat.Line.FillFormat.FillType till FillType.NoFill.<br/>            Skrivskyddad **bool**. |
| [`format`](/slides/python-net/sv/aspose.slides.charts/axis/format/) | Representerar formatet för axeln.<br/>             Skrivskyddad [`IAxisFormat`](/slides/python-net/sv/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/sv/aspose.slides.charts/axis/text_format/) | Representerar formatet för text.<br/>             Skrivskyddad [`IChartTextFormat`](/slides/python-net/sv/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/sv/aspose.slides.charts/axis/title/) | Hämtar axelns titel.<br/>             Skrivskyddad [`IChartTitle`](/slides/python-net/sv/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/sv/aspose.slides.charts/axis/cross_type/) | Representerar CrossType på den angivna axeln där den andra axeln korsar.<br/>             Läs/skriv [`CrossesType`](/slides/python-net/sv/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/sv/aspose.slides.charts/axis/position/) | Representerar axelns position.<br/>             Läs/skriv [`AxisPositionType`](/slides/python-net/sv/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/sv/aspose.slides.charts/axis/has_title/) | Bestämmer om en axel har en synlig titel.<br/>            Läs/skriv **bool**. |
| [`number_format`](/slides/python-net/sv/aspose.slides.charts/axis/number_format/) | Representerar formatsträngen för axeletiketterna.<br/>            Läs/skriv **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/sv/aspose.slides.charts/axis/is_number_format_linked_to_source/) | Indikerar om formatet är länkat till källdata.<br/>            Läs/skriv **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/sv/aspose.slides.charts/axis/tick_label_rotation_angle/) | Representerar rotationsvinkeln för stapel-etiketter.<br/>            Läs/skriv **float**. |
| [`tick_label_spacing`](/slides/python-net/sv/aspose.slides.charts/axis/tick_label_spacing/) | Anger hur många stapel-etiketter som ska hoppas över mellan de som ritas. Gäller för kategori- eller serieaxel.<br/>            Läs/skriv **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/sv/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | Anger värdet för automatisk stapel-etikettavstånd. Om falskt: använd TickLabelSpacing-egenskapen.<br/>            Läs/skriv **bool**. |
| [`tick_marks_spacing`](/slides/python-net/sv/aspose.slides.charts/axis/tick_marks_spacing/) | Anger hur många staplar som ska hoppas över innan nästa ska <br/>            ritas. Gäller för kategori- eller serieaxel.<br/>            Läs/skriv **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/sv/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | Anger värdet för automatisk stapel-avstånd. Om falskt: använd TickMarksSpacing-egenskapen.<br/>            Läs/skriv **bool**. |
| [`label_offset`](/slides/python-net/sv/aspose.slides.charts/axis/label_offset/) | Anger avståndet för etiketter från axeln. Gäller för kategori- eller datumaxel. Värdet måste ligga mellan 0 % och 1000 %.<br/>            Läs/skriv **int**. |
| [`aggregation_type`](/slides/python-net/sv/aspose.slides.charts/axis/aggregation_type/) | Representerar aggregeringstypen för kategoriaxeln (binning). Gäller för kategori. Används endast med Histogram- eller HistogramPareto-serier. |
| [`bin_width`](/slides/python-net/sv/aspose.slides.charts/axis/bin_width/) | Anger binbredd när AggregationType-egenskapen är satt till AxisAggregationType.ByBinWidth.<br/>            Gäller för kategori-axlar. Används endast med Histogram- eller HistogramPareto-serier. |
| [`number_of_bins`](/slides/python-net/sv/aspose.slides.charts/axis/number_of_bins/) | Anger antalet bin när AggregationType-egenskapen är satt till AxisAggregationType.ByNumberOfBins.<br/>            Gäller för kategori-axlar. Används endast med Histogram- eller HistogramPareto-serier. |
| [`is_overflow_bin`](/slides/python-net/sv/aspose.slides.charts/axis/is_overflow_bin/) | Anger om overflow-bin tillämpas. Använd IsAutomaticOverflowBin och OverflowBin för att justera overflow-bin-värdet. |
| [`is_automatic_overflow_bin`](/slides/python-net/sv/aspose.slides.charts/axis/is_automatic_overflow_bin/) | Anger automatiskt overflow-bin-värde. Om falskt: använd OverflowBin-egenskapen. |
| [`overflow_bin`](/slides/python-net/sv/aspose.slides.charts/axis/overflow_bin/) | Anger anpassat värde för overflow-bin. Tillämpas när IsAutomaticOverflowBin-egenskapen är falsk och IsOverflowBin-egenskapen är sann. |
| [`is_underflow_bin`](/slides/python-net/sv/aspose.slides.charts/axis/is_underflow_bin/) | Anger om underflow-bin tillämpas. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflow-bin-värdet. |
| [`is_automatic_underflow_bin`](/slides/python-net/sv/aspose.slides.charts/axis/is_automatic_underflow_bin/) | Anger automatiskt underflow-bin-värde. Om falskt: använd UnderflowBin-egenskapen. |
| [`underflow_bin`](/slides/python-net/sv/aspose.slides.charts/axis/underflow_bin/) | Anger anpassat värde för underflow-bin. Tillämpas när IsAutomaticUnderflowBin-egenskapen är falsk och IsUnderflowBin-egenskapen är sann. |
| [`slide`](/slides/python-net/sv/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides.charts/axis/presentation/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/sv/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | Anger IAxis.CategoryAxisType-egenskapen med ett värde som bestäms automatiskt baserat på axeldata. |

### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)