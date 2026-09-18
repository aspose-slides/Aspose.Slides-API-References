---
title: IAxis class
second_title: Aspose.Slides dla Pythona przez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.charts/iaxis/
---
## IAxis klasa

Enkapsuluje obiekt, który reprezentuje oś wykresu.

Typ IAxis udostępnia następujące elementy:

## Właściwości

| Property | Description |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/pl/aspose.slides.charts/iaxis/axis_between_categories/) | Określa, czy oś wartości przecina oś kategorii pomiędzy kategoriami.<br/>            Ta właściwość ma zastosowanie tylko do osi kategorii i nie obowiązuje w wykresach 3-D.<br/>            Odczyt/zapis **bool**. |
| [`cross_at`](/slides/python-net/pl/aspose.slides.charts/iaxis/cross_at/) | Określa punkt na osi, w którym prostopadła oś ją przecina.<br/>            Odczyt/zapis **float**. |
| [`display_unit`](/slides/python-net/pl/aspose.slides.charts/iaxis/display_unit/) | Określa wartość skalowania jednostek wyświetlania dla osi wartości.<br/>            Odczyt/zapis [`DisplayUnitType`](/slides/python-net/pl/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/pl/aspose.slides.charts/iaxis/actual_max_value/) | Określa rzeczywistą maksymalną wartość na osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [`actual_min_value`](/slides/python-net/pl/aspose.slides.charts/iaxis/actual_min_value/) | Określa rzeczywistą minimalną wartość na osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [`actual_major_unit`](/slides/python-net/pl/aspose.slides.charts/iaxis/actual_major_unit/) | Określa rzeczywistą jednostkę główną osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [`actual_minor_unit`](/slides/python-net/pl/aspose.slides.charts/iaxis/actual_minor_unit/) | Określa rzeczywistą jednostkę podrzędną osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [`actual_major_unit_scale`](/slides/python-net/pl/aspose.slides.charts/iaxis/actual_major_unit_scale/) | Określa rzeczywistą skalę jednostki głównej osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [`actual_minor_unit_scale`](/slides/python-net/pl/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | Określa rzeczywistą skalę jednostki podrzędnej osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [`is_automatic_max_value`](/slides/python-net/pl/aspose.slides.charts/iaxis/is_automatic_max_value/) | Wskazuje, czy maksymalna wartość jest przypisywana automatycznie.<br/>             Odczyt/zapis **bool**. |
| [`max_value`](/slides/python-net/pl/aspose.slides.charts/iaxis/max_value/) | Określa maksymalną wartość na osi wartości.<br/>             Odczyt/zapis **float**. |
| [`minor_unit`](/slides/python-net/pl/aspose.slides.charts/iaxis/minor_unit/) | Określa jednostki podrzędne dla osi daty lub wartości.<br/>             Odczyt/zapis **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/pl/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | Wskazuje, czy jednostka podrzędna osi jest przypisywana automatycznie.<br/>             Odczyt/zapis **bool**. |
| [`major_unit`](/slides/python-net/pl/aspose.slides.charts/iaxis/major_unit/) | Określa jednostki główne dla osi daty lub wartości.<br/>             Odczyt/zapis **float**. |
| [`is_automatic_major_unit`](/slides/python-net/pl/aspose.slides.charts/iaxis/is_automatic_major_unit/) | Wskazuje, czy jednostka główna osi jest przypisywana automatycznie.<br/>            Odczyt/zapis **bool**. |
| [`is_automatic_min_value`](/slides/python-net/pl/aspose.slides.charts/iaxis/is_automatic_min_value/) | Wskazuje, czy minimalna wartość jest przypisywana automatycznie.<br/>             Odczyt/zapis **bool**. |
| [`min_value`](/slides/python-net/pl/aspose.slides.charts/iaxis/min_value/) | Określa minimalną wartość na osi wartości.<br/>             Odczyt/zapis **float**. |
| [`is_logarithmic`](/slides/python-net/pl/aspose.slides.charts/iaxis/is_logarithmic/) | Określa, czy typ skali osi wartości jest logarytmiczny.<br/>             Odczyt/zapis **bool**. |
| [`log_base`](/slides/python-net/pl/aspose.slides.charts/iaxis/log_base/) | Określa podstawę logarytmu. Domyślna wartość to 10.<br/>             Odczyt/zapis **float**. |
| [`is_plot_order_reversed`](/slides/python-net/pl/aspose.slides.charts/iaxis/is_plot_order_reversed/) | Określa, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego.<br/>             Odczyt/zapis **bool**. |
| [`is_visible`](/slides/python-net/pl/aspose.slides.charts/iaxis/is_visible/) | Określa, czy oś jest widoczna.<br/>             Odczyt/zapis **bool**. |
| [`major_tick_mark`](/slides/python-net/pl/aspose.slides.charts/iaxis/major_tick_mark/) | Określa typ głównego znacznika podziałki dla określonej osi.<br/>             Odczyt/zapis [`TickMarkType`](/slides/python-net/pl/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/pl/aspose.slides.charts/iaxis/minor_tick_mark/) | Określa typ podrzędnego znacznika podziałki dla określonej osi.<br/>             Odczyt/zapis [`TickMarkType`](/slides/python-net/pl/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/pl/aspose.slides.charts/iaxis/tick_label_position/) | Określa pozycję etykiet znaczników podziałek na określonej osi.<br/>             Odczyt/zapis [`TickLabelPositionType`](/slides/python-net/pl/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/pl/aspose.slides.charts/iaxis/major_unit_scale/) | Określa skalę jednostki głównej dla osi daty.<br/>             Odczyt/zapis [`TimeUnitType`](/slides/python-net/pl/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/pl/aspose.slides.charts/iaxis/minor_unit_scale/) | Określa skalę jednostki głównej dla osi daty.<br/>             Odczyt/zapis [`TimeUnitType`](/slides/python-net/pl/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/pl/aspose.slides.charts/iaxis/base_unit_scale/) | Określa najmniejszą jednostkę czasu reprezentowaną na osi daty.<br/>            Odczyt/zapis [`TimeUnitType`](/slides/python-net/pl/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/pl/aspose.slides.charts/iaxis/minor_grid_lines_format/) | Określa format linii siatki podrzędnej na osi wykresu.<br/>             Tylko odczyt [`IChartLinesFormat`](/slides/python-net/pl/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/pl/aspose.slides.charts/iaxis/major_grid_lines_format/) | Określa format linii siatki głównej na osi wykresu.<br/>             Tylko odczyt [`IChartLinesFormat`](/slides/python-net/pl/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/pl/aspose.slides.charts/iaxis/show_minor_grid_lines/) | Określa, czy linie siatki podrzędnej są wyświetlane.<br/>             Tylko odczyt **bool**. |
| [`show_major_grid_lines`](/slides/python-net/pl/aspose.slides.charts/iaxis/show_major_grid_lines/) | Określa, czy linie siatki głównej są wyświetlane.<br/>             Tylko odczyt **bool**. |
| [`format`](/slides/python-net/pl/aspose.slides.charts/iaxis/format/) | Określa format osi.<br/>             Tylko odczyt [`IAxisFormat`](/slides/python-net/pl/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/pl/aspose.slides.charts/iaxis/title/) | Pobiera tytuł osi.<br/>             Tylko odczyt [`IChartTitle`](/slides/python-net/pl/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/pl/aspose.slides.charts/iaxis/cross_type/) | Określa CrossType na określonej osi, gdzie przecina ją inna oś.<br/>             Odczyt/zapis [`CrossesType`](/slides/python-net/pl/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/pl/aspose.slides.charts/iaxis/position/) | Określa położenie osi.<br/>             Odczyt/zapis [`AxisPositionType`](/slides/python-net/pl/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/pl/aspose.slides.charts/iaxis/has_title/) | Określa, czy oś ma widoczny tytuł.<br/>            Odczyt/zapis **bool**. |
| [`number_format`](/slides/python-net/pl/aspose.slides.charts/iaxis/number_format/) | Określa ciąg formatu dla etykiet osi.<br/>            Odczyt/zapis **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/pl/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | Wskazuje, czy format jest powiązany z danymi źródłowymi.<br/>            Odczyt/zapis **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/pl/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | Określa kąt obrotu etykiet podziałek<br/>            Odczyt/zapis **float**. |
| [`tick_label_spacing`](/slides/python-net/pl/aspose.slides.charts/iaxis/tick_label_spacing/) | Określa liczbę etykiet podziałek pomijanych między wyświetlanymi etykietami.<br/>            Odczyt/zapis **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/pl/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | Określa, czy wartość odstępu etykiet podziałek jest automatyczna. Jeśli false: użyj właściwości TickLabelSpacing.<br/>            Odczyt/zapis **bool**. |
| [`tick_marks_spacing`](/slides/python-net/pl/aspose.slides.charts/iaxis/tick_marks_spacing/) | Określa, ile znaczników podziałek ma być pominiętych przed narysowaniem kolejnego.<br/>            Stosowane do osi kategorii lub serii.<br/>            Odczyt/zapis **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/pl/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | Określa, czy odległość znaczników podziałek jest automatyczna. Jeśli false: użyj właściwości TickMarksSpacing.<br/>            Odczyt/zapis **bool**. |
| [`label_offset`](/slides/python-net/pl/aspose.slides.charts/iaxis/label_offset/) | Określa odległość etykiet od osi. Stosowane do osi kategorii lub daty. Wartość musi wynosić od 0% do 1000%.<br/>            Odczyt/zapis **int**. |
| [`category_axis_type`](/slides/python-net/pl/aspose.slides.charts/iaxis/category_axis_type/) | Określa typ osi kategorii.<br/>            Odczyt/zapis [`IAxis.category_axis_type`](/slides/python-net/pl/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/pl/aspose.slides.charts/iaxis/aggregation_type/) | Określa typ agregacji osi kategorii (grupowanie). Stosowane do kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| [`bin_width`](/slides/python-net/pl/aspose.slides.charts/iaxis/bin_width/) | Określa szerokość binu, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByBinWidth.<br/>            Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| [`number_of_bins`](/slides/python-net/pl/aspose.slides.charts/iaxis/number_of_bins/) | Określa liczbę binów, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByNumberOfBins.<br/>            Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| [`is_overflow_bin`](/slides/python-net/pl/aspose.slides.charts/iaxis/is_overflow_bin/) | Określa, czy zastosowano bin przepełnienia. Użyj IsAutomaticOverflowBin i OverflowBin, aby dostosować wartość binu przepełnienia. |
| [`is_automatic_overflow_bin`](/slides/python-net/pl/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | Określa automatyczną wartość binu przepełnienia. Jeśli false: użyj właściwości OverflowBin. |
| [`overflow_bin`](/slides/python-net/pl/aspose.slides.charts/iaxis/overflow_bin/) | Określa niestandardową wartość binu przepełnienia. Stosowane, gdy właściwość IsAutomaticOverflowBin jest ustawiona na false i właściwość IsOverflowBin jest równa true. |
| [`is_underflow_bin`](/slides/python-net/pl/aspose.slides.charts/iaxis/is_underflow_bin/) | Określa, czy zastosowano bin niedomiaru. Użyj IsAutomaticUnderflowBin i UnderflowBin, aby dostosować wartość binu niedomiaru. |
| [`is_automatic_underflow_bin`](/slides/python-net/pl/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | Określa automatyczną wartość binu niedomiaru. Jeśli false: użyj właściwości UnderflowBin. |
| [`underflow_bin`](/slides/python-net/pl/aspose.slides.charts/iaxis/underflow_bin/) | Określa niestandardową wartość binu niedomiaru. Stosowane, gdy właściwość IsAutomaticUnderflowBin jest ustawiona na false i właściwość IsUnderflowBin jest równa true. |
| [`text_format`](/slides/python-net/pl/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/pl/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/pl/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides.charts/iaxis/presentation/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/pl/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | Ustawia właściwość IAxis.CategoryAxisType na wartość, która jest automatycznie określana na podstawie danych osi. |

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)