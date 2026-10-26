---
title: Axis class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/axis/
---
## Axis třída

Zapouzdřuje objekt, který představuje osu grafu.

Typ Axis vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`chart`](/slides/python-net/cs/aspose.slides.charts/axis/chart/) | Vrací nadřazený graf.<br/>            Pouze ke čtení [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/cs/aspose.slides.charts/axis/axis_between_categories/) | Určuje, zda osa hodnot protíná osu kategorií mezi kategoriemi.<br/>             Tato vlastnost se vztahuje pouze na osy kategorií a neplatí pro 3D grafy.<br/>             Čtení/zápis **bool**. |
| [`category_axis_type`](/slides/python-net/cs/aspose.slides.charts/axis/category_axis_type/) | Určuje typ osy kategorií.<br/>            Čtení/zápis [`CategoryAxisType`](/slides/python-net/cs/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/cs/aspose.slides.charts/axis/cross_at/) | Určuje bod na ose, kde křížová osa protíná tuto osu.<br/>             Čtení/zápis **float**. |
| [`display_unit`](/slides/python-net/cs/aspose.slides.charts/axis/display_unit/) | Určuje škálovací hodnotu zobrazovacích jednotek pro osu hodnot.<br/>             Čtení/zápis [`DisplayUnitType`](/slides/python-net/cs/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/cs/aspose.slides.charts/axis/actual_max_value/) | Určuje skutečnou maximální hodnotu na ose. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [`actual_min_value`](/slides/python-net/cs/aspose.slides.charts/axis/actual_min_value/) | Určuje skutečnou minimální hodnotu na ose. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [`actual_major_unit`](/slides/python-net/cs/aspose.slides.charts/axis/actual_major_unit/) | Určuje skutečnou hlavní jednotku osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [`actual_minor_unit`](/slides/python-net/cs/aspose.slides.charts/axis/actual_minor_unit/) | Určuje skutečnou podřadnou jednotku osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [`actual_major_unit_scale`](/slides/python-net/cs/aspose.slides.charts/axis/actual_major_unit_scale/) | Určuje skutečné měřítko hlavní jednotky osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [`actual_minor_unit_scale`](/slides/python-net/cs/aspose.slides.charts/axis/actual_minor_unit_scale/) | Určuje skutečné měřítko podřadné jednotky osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [`is_automatic_max_value`](/slides/python-net/cs/aspose.slides.charts/axis/is_automatic_max_value/) | Udává, zda je maximální hodnota přiřazena automaticky.<br/>             Čtení/zápis **bool**. |
| [`max_value`](/slides/python-net/cs/aspose.slides.charts/axis/max_value/) | Určuje maximální hodnotu na ose hodnot.<br/>             Čtení/zápis **float**. |
| [`minor_unit`](/slides/python-net/cs/aspose.slides.charts/axis/minor_unit/) | Určuje podřadné jednotky pro datumovou nebo hodnotovou osu.<br/>             Čtení/zápis **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/cs/aspose.slides.charts/axis/is_automatic_minor_unit/) | Udává, zda je podřadná jednotka osy přiřazena automaticky.<br/>             Čtení/zápis **bool**. |
| [`major_unit`](/slides/python-net/cs/aspose.slides.charts/axis/major_unit/) | Určuje hlavní jednotky pro datumovou nebo hodnotovou osu.<br/>             Čtení/zápis **float**. |
| [`is_automatic_major_unit`](/slides/python-net/cs/aspose.slides.charts/axis/is_automatic_major_unit/) | Udává, zda je hlavní jednotka osy přiřazena automaticky.<br/>            Čtení/zápis **bool**. |
| [`is_automatic_min_value`](/slides/python-net/cs/aspose.slides.charts/axis/is_automatic_min_value/) | Udává, zda je minimální hodnota přiřazena automaticky.<br/>             Čtení/zápis **bool**. |
| [`min_value`](/slides/python-net/cs/aspose.slides.charts/axis/min_value/) | Určuje minimální hodnotu na ose hodnot.<br/>             Čtení/zápis **float**. |
| [`is_logarithmic`](/slides/python-net/cs/aspose.slides.charts/axis/is_logarithmic/) | Určuje, zda je typ měřítka osy hodnot logaritmický nebo ne.<br/>             Čtení/zápis **bool**. |
| [`log_base`](/slides/python-net/cs/aspose.slides.charts/axis/log_base/) | Určuje logaritmickou základnu. Výchozí hodnota je 10.<br/>             Čtení/zápis **float**. |
| [`is_plot_order_reversed`](/slides/python-net/cs/aspose.slides.charts/axis/is_plot_order_reversed/) | Určuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu.<br/>             Čtení/zápis **bool**. |
| [`is_visible`](/slides/python-net/cs/aspose.slides.charts/axis/is_visible/) | Určuje, zda je osa viditelná.<br/>             Čtení/zápis **bool**. |
| [`major_tick_mark`](/slides/python-net/cs/aspose.slides.charts/axis/major_tick_mark/) | Určuje typ hlavního značkovacího tahu pro zadanou osu.<br/>             Čtení/zápis [`TickMarkType`](/slides/python-net/cs/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/cs/aspose.slides.charts/axis/minor_tick_mark/) | Určuje typ podřadného značkovacího tahu pro zadanou osu.<br/>             Čtení/zápis [`TickMarkType`](/slides/python-net/cs/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/cs/aspose.slides.charts/axis/tick_label_position/) | Určuje pozici popisků značkovacích tahů na zadané ose.<br/>             Čtení/zápis [`TickLabelPositionType`](/slides/python-net/cs/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/cs/aspose.slides.charts/axis/major_unit_scale/) | Určuje měřítko hlavní jednotky pro datumovou osu.<br/>             Čtení/zápis [`TimeUnitType`](/slides/python-net/cs/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/cs/aspose.slides.charts/axis/minor_unit_scale/) | Určuje měřítko hlavní jednotky pro datumovou osu.<br/>             Čtení/zápis [`TimeUnitType`](/slides/python-net/cs/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/cs/aspose.slides.charts/axis/base_unit_scale/) | Určuje nejmenší časovou jednotku, která je zobrazena na datumové ose.<br/>            Čtení/zápis [`TimeUnitType`](/slides/python-net/cs/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/cs/aspose.slides.charts/axis/minor_grid_lines_format/) | Určuje formát podřadných mřížkových čar na ose grafu.<br/>             Pouze ke čtení [`IChartLinesFormat`](/slides/python-net/cs/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/cs/aspose.slides.charts/axis/major_grid_lines_format/) | Určuje formát hlavních mřížkových čar na ose grafu.<br/>             Pouze ke čtení [`IChartLinesFormat`](/slides/python-net/cs/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/cs/aspose.slides.charts/axis/show_minor_grid_lines/) | Pro skrytí podřadné mřížkové čáry nastavte MinorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill.<br/>            Pouze ke čtení **bool**. |
| [`show_major_grid_lines`](/slides/python-net/cs/aspose.slides.charts/axis/show_major_grid_lines/) | Pro skrytí hlavní mřížkové čáry nastavte MajorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill.<br/>            Pouze ke čtení **bool**. |
| [`format`](/slides/python-net/cs/aspose.slides.charts/axis/format/) | Určuje formát osy.<br/>             Pouze ke čtení [`IAxisFormat`](/slides/python-net/cs/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/cs/aspose.slides.charts/axis/text_format/) | Určuje formát textu.<br/>             Pouze ke čtení [`IChartTextFormat`](/slides/python-net/cs/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/cs/aspose.slides.charts/axis/title/) | Získá název osy.<br/>             Pouze ke čtení [`IChartTitle`](/slides/python-net/cs/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/cs/aspose.slides.charts/axis/cross_type/) | Určuje CrossType na zadané ose, kde se protíná druhá osa.<br/>             Čtení/zápis [`CrossesType`](/slides/python-net/cs/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/cs/aspose.slides.charts/axis/position/) | Určuje pozici osy.<br/>             Čtení/zápis [`AxisPositionType`](/slides/python-net/cs/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/cs/aspose.slides.charts/axis/has_title/) | Určuje, zda má osa viditelný název.<br/>            Čtení/zápis **bool**. |
| [`number_format`](/slides/python-net/cs/aspose.slides.charts/axis/number_format/) | Určuje formátovací řetězec pro popisky osy.<br/>            Čtení/zápis **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/cs/aspose.slides.charts/axis/is_number_format_linked_to_source/) | Udává, zda je formát propojen se zdrojovými daty.<br/>            Čtení/zápis **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/cs/aspose.slides.charts/axis/tick_label_rotation_angle/) | Určuje úhel otočení popisků značkovacích tahů.<br/>            Čtení/zápis **float**. |
| [`tick_label_spacing`](/slides/python-net/cs/aspose.slides.charts/axis/tick_label_spacing/) | Určuje, kolik popisků značkovacích tahů se má přeskočit mezi vykreslenými popisky. Používá se pro osu kategorií nebo sérií.<br/>            Čtení/zápis **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/cs/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | Určuje automatickou hodnotu rozestupu popisků značkovacích tahů. Pokud je false, použijte vlastnost TickLabelSpacing.<br/>            Čtení/zápis **bool**. |
| [`tick_marks_spacing`](/slides/python-net/cs/aspose.slides.charts/axis/tick_marks_spacing/) | Určuje, kolik značkovacích tahů se má přeskočit před tím, než bude další <br/>            vykreslen. Používá se pro osu kategorií nebo sérií.<br/>            Čtení/zápis **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/cs/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | Určuje automatickou hodnotu rozestupu značkovacích tahů. Pokud je false, použijte vlastnost TickMarksSpacing.<br/>            Čtení/zápis **bool**. |
| [`label_offset`](/slides/python-net/cs/aspose.slides.charts/axis/label_offset/) | Určuje vzdálenost popisků od osy. Používá se pro osu kategorií nebo datumů. Hodnota musí být mezi 0 % a 1000 %.<br/>            Čtení/zápis **int**. |
| [`aggregation_type`](/slides/python-net/cs/aspose.slides.charts/axis/aggregation_type/) | Určuje typ agregace osy kategorií (skupinování). Používá se pro kategorie. Pouze s řadami Histogram nebo HistogramPareto. |
| [`bin_width`](/slides/python-net/cs/aspose.slides.charts/axis/bin_width/) | Určuje šířku binu, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByBinWidth.<br/>            Používá se pro osy kategorií. Pouze s řadami Histogram nebo HistogramPareto. |
| [`number_of_bins`](/slides/python-net/cs/aspose.slides.charts/axis/number_of_bins/) | Určuje počet binů, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByNumberOfBins.<br/>            Používá se pro osy kategorií. Pouze s řadami Histogram nebo HistogramPareto. |
| [`is_overflow_bin`](/slides/python-net/cs/aspose.slides.charts/axis/is_overflow_bin/) | Určuje, zda je aplikován přeplňovací bin. Použijte IsAutomaticOverflowBin a OverflowBin k úpravě hodnoty přeplňovacího binu. |
| [`is_automatic_overflow_bin`](/slides/python-net/cs/aspose.slides.charts/axis/is_automatic_overflow_bin/) | Určuje automatickou hodnotu přeplňovacího binu. Pokud je false, použijte vlastnost OverflowBin. |
| [`overflow_bin`](/slides/python-net/cs/aspose.slides.charts/axis/overflow_bin/) | Určuje vlastní hodnotu přeplňovacího binu. Používá se, když je vlastnost IsAutomaticOverflowBin nastavena na false a vlastnost IsOverflowBin je true. |
| [`is_underflow_bin`](/slides/python-net/cs/aspose.slides.charts/axis/is_underflow_bin/) | Určuje, zda je aplikován podplňovací bin. Použijte IsAutomaticUnderflowBin a UnderflowBin k úpravě hodnoty podplňovacího binu. |
| [`is_automatic_underflow_bin`](/slides/python-net/cs/aspose.slides.charts/axis/is_automatic_underflow_bin/) | Určuje automatickou hodnotu podplňovacího binu. Pokud je false, použijte vlastnost UnderflowBin. |
| [`underflow_bin`](/slides/python-net/cs/aspose.slides.charts/axis/underflow_bin/) | Určuje vlastní hodnotu podplňovacího binu. Používá se, když je vlastnost IsAutomaticUnderflowBin nastavena na false a vlastnost IsUnderflowBin je true. |
| [`slide`](/slides/python-net/cs/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides.charts/axis/presentation/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/cs/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | Nastaví vlastnost IAxis.CategoryAxisType na hodnotu, která je automaticky určena na základě dat osy. |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)