---
title: Axis class
second_title: Aspose.Slides dla Pythona przez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.charts/axis/
---
## Axis klasa

Enkapsuluje obiekt, który reprezentuje oś wykresu.

Typ Axis udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`chart`](/slides/python-net/pl/aspose.slides.charts/axis/chart/) | Zwraca wykres nadrzędny.<br/>            Tylko do odczytu [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/pl/aspose.slides.charts/axis/axis_between_categories/) | Określa, czy oś wartości przecina oś kategorii pomiędzy kategoriami.<br/>             Właściwość ta ma zastosowanie tylko do osi kategorii i nie ma zastosowania do wykresów 3-D.<br/>             Odczyt/zapis **bool**. |
| [`category_axis_type`](/slides/python-net/pl/aspose.slides.charts/axis/category_axis_type/) | Określa typ osi kategorii.<br/>            Odczyt/zapis [`CategoryAxisType`](/slides/python-net/pl/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/pl/aspose.slides.charts/axis/cross_at/) | Reprezentuje punkt na osi, w którym prostopadła oś ją przecina.<br/>             Odczyt/zapis **float**. |
| [`display_unit`](/slides/python-net/pl/aspose.slides.charts/axis/display_unit/) | Określa wartość skalowania jednostek wyświetlania dla osi wartości.<br/>             Odczyt/zapis [`DisplayUnitType`](/slides/python-net/pl/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/pl/aspose.slides.charts/axis/actual_max_value/) | Określa rzeczywistą maksymalną wartość na osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [`actual_min_value`](/slides/python-net/pl/aspose.slides.charts/axis/actual_min_value/) | Określa rzeczywistą minimalną wartość na osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [`actual_major_unit`](/slides/python-net/pl/aspose.slides.charts/axis/actual_major_unit/) | Określa rzeczywistą jednostkę główną osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [`actual_minor_unit`](/slides/python-net/pl/aspose.slides.charts/axis/actual_minor_unit/) | Określa rzeczywistą jednostkę poboczną osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [`actual_major_unit_scale`](/slides/python-net/pl/aspose.slides.charts/axis/actual_major_unit_scale/) | Określa rzeczywistą skalę jednostki głównej osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [`actual_minor_unit_scale`](/slides/python-net/pl/aspose.slides.charts/axis/actual_minor_unit_scale/) | Określa rzeczywistą skalę jednostki pobocznej osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [`is_automatic_max_value`](/slides/python-net/pl/aspose.slides.charts/axis/is_automatic_max_value/) | Wskazuje, czy maksymalna wartość jest przypisywana automatycznie.<br/>             Odczyt/zapis **bool**. |
| [`max_value`](/slides/python-net/pl/aspose.slides.charts/axis/max_value/) | Reprezentuje maksymalną wartość na osi wartości.<br/>             Odczyt/zapis **float**. |
| [`minor_unit`](/slides/python-net/pl/aspose.slides.charts/axis/minor_unit/) | Reprezentuje jednostki poboczne dla osi daty lub wartości.<br/>             Odczyt/zapis **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/pl/aspose.slides.charts/axis/is_automatic_minor_unit/) | Wskazuje, czy jednostka poboczna osi jest przypisywana automatycznie.<br/>             Odczyt/zapis **bool**. |
| [`major_unit`](/slides/python-net/pl/aspose.slides.charts/axis/major_unit/) | Reprezentuje jednostki główne dla osi daty lub wartości.<br/>             Odczyt/zapis **float**. |
| [`is_automatic_major_unit`](/slides/python-net/pl/aspose.slides.charts/axis/is_automatic_major_unit/) | Wskazuje, czy jednostka główna osi jest przypisywana automatycznie. <br/>            Odczyt/zapis **bool**. |
| [`is_automatic_min_value`](/slides/python-net/pl/aspose.slides.charts/axis/is_automatic_min_value/) | Wskazuje, czy minimalna wartość jest przypisywana automatycznie.<br/>             Odczyt/zapis **bool**. |
| [`min_value`](/slides/python-net/pl/aspose.slides.charts/axis/min_value/) | Reprezentuje minimalną wartość na osi wartości.<br/>             Odczyt/zapis **float**. |
| [`is_logarithmic`](/slides/python-net/pl/aspose.slides.charts/axis/is_logarithmic/) | Określa, czy typ skali osi wartości jest logarytmiczny.<br/>             Odczyt/zapis **bool**. |
| [`log_base`](/slides/python-net/pl/aspose.slides.charts/axis/log_base/) | Reprezentuje podstawę logarytmu. Domyślna wartość to 10.<br/>             Odczyt/zapis **float**. |
| [`is_plot_order_reversed`](/slides/python-net/pl/aspose.slides.charts/axis/is_plot_order_reversed/) | Określa, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego.<br/>             Odczyt/zapis **bool**. |
| [`is_visible`](/slides/python-net/pl/aspose.slides.charts/axis/is_visible/) | Określa, czy oś jest widoczna.<br/>             Odczyt/zapis **bool**. |
| [`major_tick_mark`](/slides/python-net/pl/aspose.slides.charts/axis/major_tick_mark/) | Określa typ głównego znacznika podziałki dla określonej osi.<br/>             Odczyt/zapis [`TickMarkType`](/slides/python-net/pl/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/pl/aspose.slides.charts/axis/minor_tick_mark/) | Określa typ pobocznego znacznika podziałki dla określonej osi.<br/>             Odczyt/zapis [`TickMarkType`](/slides/python-net/pl/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/pl/aspose.slides.charts/axis/tick_label_position/) | Określa położenie etykiet znacznika podziałki na określonej osi.<br/>             Odczyt/zapis [`TickLabelPositionType`](/slides/python-net/pl/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/pl/aspose.slides.charts/axis/major_unit_scale/) | Reprezentuje skalę jednostki głównej dla osi daty.<br/>             Odczyt/zapis [`TimeUnitType`](/slides/python-net/pl/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/pl/aspose.slides.charts/axis/minor_unit_scale/) | Reprezentuje skalę jednostki głównej dla osi daty.<br/>             Odczyt/zapis [`TimeUnitType`](/slides/python-net/pl/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/pl/aspose.slides.charts/axis/base_unit_scale/) | Określa najmniejszą jednostkę czasu reprezentowaną na osi daty.<br/>            Odczyt/zapis [`TimeUnitType`](/slides/python-net/pl/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/pl/aspose.slides.charts/axis/minor_grid_lines_format/) | Reprezentuje format linii siatki pobocznej na osi wykresu.<br/>             Tylko do odczytu [`IChartLinesFormat`](/slides/python-net/pl/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/pl/aspose.slides.charts/axis/major_grid_lines_format/) | Reprezentuje format linii siatki głównej na osi wykresu.<br/>             Tylko do odczytu [`IChartLinesFormat`](/slides/python-net/pl/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/pl/aspose.slides.charts/axis/show_minor_grid_lines/) | Aby ukryć linię siatki pobocznej, ustaw MinorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill.<br/>            Tylko do odczytu **bool**. |
| [`show_major_grid_lines`](/slides/python-net/pl/aspose.slides.charts/axis/show_major_grid_lines/) | Aby ukryć linię siatki głównej, ustaw MajorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill.<br/>            Tylko do odczytu **bool**. |
| [`format`](/slides/python-net/pl/aspose.slides.charts/axis/format/) | Reprezentuje format osi.<br/>             Tylko do odczytu [`IAxisFormat`](/slides/python-net/pl/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/pl/aspose.slides.charts/axis/text_format/) | Reprezentuje format tekstu.<br/>             Tylko do odczytu [`IChartTextFormat`](/slides/python-net/pl/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/pl/aspose.slides.charts/axis/title/) | Pobiera tytuł osi.<br/>             Tylko do odczytu [`IChartTitle`](/slides/python-net/pl/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/pl/aspose.slides.charts/axis/cross_type/) | Reprezentuje CrossType na określonej osi, w miejscu przecięcia z drugą osią.<br/>             Odczyt/zapis [`CrossesType`](/slides/python-net/pl/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/pl/aspose.slides.charts/axis/position/) | Reprezentuje położenie osi.<br/>             Odczyt/zapis [`AxisPositionType`](/slides/python-net/pl/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/pl/aspose.slides.charts/axis/has_title/) | Określa, czy oś ma widoczny tytuł.<br/>            Odczyt/zapis **bool**. |
| [`number_format`](/slides/python-net/pl/aspose.slides.charts/axis/number_format/) | Reprezentuje ciąg formatu dla etykiet osi.<br/>            Odczyt/zapis **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/pl/aspose.slides.charts/axis/is_number_format_linked_to_source/) | Wskazuje, czy format jest powiązany z danymi źródłowymi.<br/>            Odczyt/zapis **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/pl/aspose.slides.charts/axis/tick_label_rotation_angle/) | Reprezentuje kąt obrotu etykiet podziałek.<br/>            Odczyt/zapis **float**. |
| [`tick_label_spacing`](/slides/python-net/pl/aspose.slides.charts/axis/tick_label_spacing/) | Określa, ile etykiet podziałek pominąć między narysowanymi etykietami. Stosowane do osi kategorii lub serii.<br/>            Odczyt/zapis **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/pl/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | Określa automatyczną wartość odstępu etykiet podziałek. Jeśli false: użyj właściwości TickLabelSpacing.<br/>            Odczyt/zapis **bool**. |
| [`tick_marks_spacing`](/slides/python-net/pl/aspose.slides.charts/axis/tick_marks_spacing/) | Określa, ile znaczników podziałek pominąć przed narysowaniem kolejnego.<br/>            Stosowane do osi kategorii lub serii.<br/>            Odczyt/zapis **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/pl/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | Określa automatyczną wartość odstępu znaczników podziałek. Jeśli false: użyj właściwości TickMarksSpacing.<br/>            Odczyt/zapis **bool**. |
| [`label_offset`](/slides/python-net/pl/aspose.slides.charts/axis/label_offset/) | Określa odległość etykiet od osi. Stosowane do osi kategorii lub daty. Wartość musi być pomiędzy 0% a 1000%.<br/>            Odczyt/zapis **int**. |
| [`aggregation_type`](/slides/python-net/pl/aspose.slides.charts/axis/aggregation_type/) | Reprezentuje typ agregacji osi kategorii (grupowanie). Stosowane do kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| [`bin_width`](/slides/python-net/pl/aspose.slides.charts/axis/bin_width/) | Określa szerokość przedziału, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByBinWidth.<br/>            Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| [`number_of_bins`](/slides/python-net/pl/aspose.slides.charts/axis/number_of_bins/) | Określa liczbę przedziałów, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByNumberOfBins.<br/>            Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| [`is_overflow_bin`](/slides/python-net/pl/aspose.slides.charts/axis/is_overflow_bin/) | Określa, czy zastosowano przedział przepełnienia. Użyj IsAutomaticOverflowBin i OverflowBin, aby dostosować wartość przedziału przepełnienia. |
| [`is_automatic_overflow_bin`](/slides/python-net/pl/aspose.slides.charts/axis/is_automatic_overflow_bin/) | Określa automatyczną wartość przedziału przepełnienia. Jeśli false: użyj właściwości OverflowBin. |
| [`overflow_bin`](/slides/python-net/pl/aspose.slides.charts/axis/overflow_bin/) | Określa niestandardową wartość przedziału przepełnienia. Stosowane, gdy właściwość IsAutomaticOverflowBin jest ustawiona na false i właściwość IsOverflowBin jest równa true. |
| [`is_underflow_bin`](/slides/python-net/pl/aspose.slides.charts/axis/is_underflow_bin/) | Określa, czy zastosowano przedział niedoboru. Użyj IsAutomaticUnderflowBin i UnderflowBin, aby dostosować wartość przedziału niedoboru. |
| [`is_automatic_underflow_bin`](/slides/python-net/pl/aspose.slides.charts/axis/is_automatic_underflow_bin/) | Określa automatyczną wartość przedziału niedoboru. Jeśli false: użyj właściwości UnderflowBin. |
| [`underflow_bin`](/slides/python-net/pl/aspose.slides.charts/axis/underflow_bin/) | Określa niestandardową wartość przedziału niedoboru. Stosowane, gdy właściwość IsAutomaticUnderflowBin jest ustawiona na false i właściwość IsUnderflowBin jest równa true. |
| [`slide`](/slides/python-net/pl/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides.charts/axis/presentation/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/pl/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | Ustawia właściwość IAxis.CategoryAxisType na wartość automatycznie określaną na podstawie danych osi. |

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)