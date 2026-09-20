---
title: IAxis class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/iaxis/
---
## IAxis třída

Zapouzdřuje objekt, který představuje osu grafu.

Typ IAxis vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/cs/aspose.slides.charts/iaxis/axis_between_categories/) | Určuje, zda osa hodnot protíná osu kategorií mezi kategoriemi.<br/>            Tato vlastnost se vztahuje pouze na osy kategorií a neplatí pro 3-D grafy.<br/>            Čtení/zápis **bool**. |
| [`cross_at`](/slides/python-net/cs/aspose.slides.charts/iaxis/cross_at/) | Určuje bod na ose, kde ji protíná kolmá osa.<br/>            Čtení/zápis **float**. |
| [`display_unit`](/slides/python-net/cs/aspose.slides.charts/iaxis/display_unit/) | Určuje škálovací hodnotu zobrazovacích jednotek pro osu hodnot.<br/>            Čtení/zápis [`DisplayUnitType`](/slides/python-net/cs/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/cs/aspose.slides.charts/iaxis/actual_max_value/) | Určuje skutečnou maximální hodnotu na ose. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [`actual_min_value`](/slides/python-net/cs/aspose.slides.charts/iaxis/actual_min_value/) | Určuje skutečnou minimální hodnotu na ose. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [`actual_major_unit`](/slides/python-net/cs/aspose.slides.charts/iaxis/actual_major_unit/) | Určuje skutečnou hlavní jednotku osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [`actual_minor_unit`](/slides/python-net/cs/aspose.slides.charts/iaxis/actual_minor_unit/) | Určuje skutečnou vedlejší jednotku osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [`actual_major_unit_scale`](/slides/python-net/cs/aspose.slides.charts/iaxis/actual_major_unit_scale/) | Určuje skutečnou míru hlavní jednotky osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [`actual_minor_unit_scale`](/slides/python-net/cs/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | Určuje skutečnou míru vedlejší jednotky osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [`is_automatic_max_value`](/slides/python-net/cs/aspose.slides.charts/iaxis/is_automatic_max_value/) | Indikuje, zda je maximální hodnota přiřazena automaticky.<br/>             Čtení/zápis **bool**. |
| [`max_value`](/slides/python-net/cs/aspose.slides.charts/iaxis/max_value/) | Určuje maximální hodnotu na ose hodnot.<br/>             Čtení/zápis **float**. |
| [`minor_unit`](/slides/python-net/cs/aspose.slides.charts/iaxis/minor_unit/) | Určuje vedlejší jednotky pro datumovou nebo hodnotovou osu.<br/>             Čtení/zápis **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/cs/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | Indikuje, zda je vedlejší jednotka osy přiřazena automaticky.<br/>             Čtení/zápis **bool**. |
| [`major_unit`](/slides/python-net/cs/aspose.slides.charts/iaxis/major_unit/) | Určuje hlavní jednotky pro datumovou nebo hodnotovou osu.<br/>             Čtení/zápis **float**. |
| [`is_automatic_major_unit`](/slides/python-net/cs/aspose.slides.charts/iaxis/is_automatic_major_unit/) | Indikuje, zda je hlavní jednotka osy přiřazena automaticky.<br/>            Čtení/zápis **bool**. |
| [`is_automatic_min_value`](/slides/python-net/cs/aspose.slides.charts/iaxis/is_automatic_min_value/) | Indikuje, zda je minimální hodnota přiřazena automaticky.<br/>             Čtení/zápis **bool**. |
| [`min_value`](/slides/python-net/cs/aspose.slides.charts/iaxis/min_value/) | Určuje minimální hodnotu na ose hodnot.<br/>             Čtení/zápis **float**. |
| [`is_logarithmic`](/slides/python-net/cs/aspose.slides.charts/iaxis/is_logarithmic/) | Určuje, zda je typ měřítka osy hodnot logaritmický či nikoli.<br/>             Čtení/zápis **bool**. |
| [`log_base`](/slides/python-net/cs/aspose.slides.charts/iaxis/log_base/) | Určuje logaritmickou základnu. Výchozí hodnota je 10.<br/>             Čtení/zápis **float**. |
| [`is_plot_order_reversed`](/slides/python-net/cs/aspose.slides.charts/iaxis/is_plot_order_reversed/) | Určuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu.<br/>             Čtení/zápis **bool**. |
| [`is_visible`](/slides/python-net/cs/aspose.slides.charts/iaxis/is_visible/) | Určuje, zda je osa viditelná.<br/>             Čtení/zápis **bool**. |
| [`major_tick_mark`](/slides/python-net/cs/aspose.slides.charts/iaxis/major_tick_mark/) | Určuje typ hlavního značkovacího číselníku pro zadanou osu.<br/>             Čtení/zápis [`TickMarkType`](/slides/python-net/cs/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/cs/aspose.slides.charts/iaxis/minor_tick_mark/) | Určuje typ vedlejšího značkovacího číselníku pro zadanou osu.<br/>             Čtení/zápis [`TickMarkType`](/slides/python-net/cs/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/cs/aspose.slides.charts/iaxis/tick_label_position/) | Určuje pozici popisků značek na zadané ose.<br/>             Čtení/zápis [`TickLabelPositionType`](/slides/python-net/cs/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/cs/aspose.slides.charts/iaxis/major_unit_scale/) | Určuje míru hlavní jednotky pro datumovou osu.<br/>             Čtení/zápis [`TimeUnitType`](/slides/python-net/cs/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/cs/aspose.slides.charts/iaxis/minor_unit_scale/) | Určuje míru hlavní jednotky pro datumovou osu.<br/>             Čtení/zápis [`TimeUnitType`](/slides/python-net/cs/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/cs/aspose.slides.charts/iaxis/base_unit_scale/) | Určuje nejmenší časovou jednotku, která je zobrazena na datumové ose.<br/>            Čtení/zápis [`TimeUnitType`](/slides/python-net/cs/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/cs/aspose.slides.charts/iaxis/minor_grid_lines_format/) | Určuje formát vedlejších mřížkových čar na ose grafu.<br/>             Pouze pro čtení [`IChartLinesFormat`](/slides/python-net/cs/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/cs/aspose.slides.charts/iaxis/major_grid_lines_format/) | Určuje formát hlavních mřížkových čar na ose grafu.<br/>             Pouze pro čtení [`IChartLinesFormat`](/slides/python-net/cs/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/cs/aspose.slides.charts/iaxis/show_minor_grid_lines/) | Určuje, zda jsou vedlejší mřížkové čáry zobrazeny.<br/>             Pouze pro čtení **bool**. |
| [`show_major_grid_lines`](/slides/python-net/cs/aspose.slides.charts/iaxis/show_major_grid_lines/) | Určuje, zda jsou hlavní mřížkové čáry zobrazeny.<br/>             Pouze pro čtení **bool**. |
| [`format`](/slides/python-net/cs/aspose.slides.charts/iaxis/format/) | Určuje formát osy.<br/>             Pouze pro čtení [`IAxisFormat`](/slides/python-net/cs/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/cs/aspose.slides.charts/iaxis/title/) | Získá název osy.<br/>             Pouze pro čtení [`IChartTitle`](/slides/python-net/cs/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/cs/aspose.slides.charts/iaxis/cross_type/) | Určuje typ protnutí (CrossType) na zadané ose, kde ji protíná druhá osa.<br/>             Čtení/zápis [`CrossesType`](/slides/python-net/cs/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/cs/aspose.slides.charts/iaxis/position/) | Určuje polohu osy.<br/>             Čtení/zápis [`AxisPositionType`](/slides/python-net/cs/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/cs/aspose.slides.charts/iaxis/has_title/) | Určuje, zda má osa viditelný název.<br/>            Čtení/zápis **bool**. |
| [`number_format`](/slides/python-net/cs/aspose.slides.charts/iaxis/number_format/) | Určuje formátovací řetězec pro popisky osy.<br/>            Čtení/zápis **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/cs/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | Ukazuje, zda je formát propojený se zdrojovými daty.<br/>            Čtení/zápis **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/cs/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | Určuje úhel otočení popisků značek<br/>            Čtení/zápis **float**. |
| [`tick_label_spacing`](/slides/python-net/cs/aspose.slides.charts/iaxis/tick_label_spacing/) | Určuje, kolik popisků značek se má přeskočit mezi vykreslenými popisky.<br/>            Čtení/zápis **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/cs/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | Určuje automatickou hodnotu rozestupu popisků značek. Pokud ne: použijte vlastnost TickLabelSpacing.<br/>            Čtení/zápis **bool**. |
| [`tick_marks_spacing`](/slides/python-net/cs/aspose.slides.charts/iaxis/tick_marks_spacing/) | Určuje, kolik značek se má přeskočit před tím, než bude další <br/>            vykreslena. Používá se u osy kategorií nebo řad.<br/>            Čtení/zápis **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/cs/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | Určuje automatickou hodnotu rozestupu značek. Pokud ne: použijte vlastnost TickMarksSpacing.<br/>            Čtení/zápis **bool**. |
| [`label_offset`](/slides/python-net/cs/aspose.slides.charts/iaxis/label_offset/) | Určuje vzdálenost popisků od osy. Používá se u osy kategorií nebo dat. Hodnota musí být mezi 0 % a 1000 %.<br/>            Čtení/zápis **int**. |
| [`category_axis_type`](/slides/python-net/cs/aspose.slides.charts/iaxis/category_axis_type/) | Určuje typ osy kategorií.<br/>            Čtení/zápis [`IAxis.category_axis_type`](/slides/python-net/cs/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/cs/aspose.slides.charts/iaxis/aggregation_type/) | Určuje typ agregace osy kategorií (rozdělení do košů). Používá se u kategorií. Pouze s řadami Histogram nebo HistogramPareto. |
| [`bin_width`](/slides/python-net/cs/aspose.slides.charts/iaxis/bin_width/) | Určuje šířku koše, když je vlastnost AggregationType nastavena na AxisAggregationType.ByBinWidth.<br/>            Používá se u os kategorií. Pouze s řadami Histogram nebo HistogramPareto. |
| [`number_of_bins`](/slides/python-net/cs/aspose.slides.charts/iaxis/number_of_bins/) | Určuje počet košů, když je vlastnost AggregationType nastavena na AxisAggregationType.ByNumberOfBins.<br/>            Používá se u os kategorií. Pouze s řadami Histogram nebo HistogramPareto. |
| [`is_overflow_bin`](/slides/python-net/cs/aspose.slides.charts/iaxis/is_overflow_bin/) | Určuje, zda je použito přetečení koše. Použijte IsAutomaticOverflowBin a OverflowBin k úpravě hodnoty přetečení koše. |
| [`is_automatic_overflow_bin`](/slides/python-net/cs/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | Určuje automatickou hodnotu přetečení koše. Pokud ne: použijte vlastnost OverflowBin. |
| [`overflow_bin`](/slides/python-net/cs/aspose.slides.charts/iaxis/overflow_bin/) | Určuje vlastní hodnotu přetečení koše. Používá se, když je vlastnost IsAutomaticOverflowBin nastavena na false a vlastnost IsOverflowBin je true. |
| [`is_underflow_bin`](/slides/python-net/cs/aspose.slides.charts/iaxis/is_underflow_bin/) | Určuje, zda je použito podtečení koše. Použijte IsAutomaticUnderflowBin a UnderflowBin k úpravě hodnoty podtečení koše. |
| [`is_automatic_underflow_bin`](/slides/python-net/cs/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | Určuje automatickou hodnotu podtečení koše. Pokud ne: použijte vlastnost UnderflowBin. |
| [`underflow_bin`](/slides/python-net/cs/aspose.slides.charts/iaxis/underflow_bin/) | Určuje vlastní hodnotu podtečení koše. Používá se, když je vlastnost IsAutomaticUnderflowBin nastavena na false a vlastnost IsUnderflowBin je true. |
| [`text_format`](/slides/python-net/cs/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/cs/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/cs/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides.charts/iaxis/presentation/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/cs/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | Nastaví vlastnost IAxis.CategoryAxisType na hodnotu, která je automaticky určena na základě dat osy. |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)