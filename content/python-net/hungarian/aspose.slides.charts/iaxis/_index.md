---
title: IAxis class
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozáson keresztül
description: 
type: docs
url: /hu/aspose.slides.charts/iaxis/
---
## IAxis osztály

Összevonja azt az objektumot, amely egy diagram tengelyét reprezentálja.

Az IAxis típus a következő tagokat tartalmazza:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/hu/aspose.slides.charts/iaxis/axis_between_categories/) | Jeli, hogy az értéktengely metszi-e a kategória tengelyt a kategóriák között.<br/>            Ez a tulajdonság csak kategória tengelyekre vonatkozik, és nem vonatkozik 3D diagramokra.<br/>            Olvasás/írás **bool**. |
| [`cross_at`](/slides/python-net/hu/aspose.slides.charts/iaxis/cross_at/) | Jeli azt a pontot a tengelyen, ahol a merőleges tengely metszi azt.<br/>            Olvasás/írás **float**. |
| [`display_unit`](/slides/python-net/hu/aspose.slides.charts/iaxis/display_unit/) | Megadja az értéktengely megjelenítési egységeinek skálázási értékét.<br/>            Olvasás/írás [`DisplayUnitType`](/slides/python-net/hu/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/hu/aspose.slides.charts/iaxis/actual_max_value/) | Megadja a tengely tényleges maximális értékét. Előzőleg hívd meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [`actual_min_value`](/slides/python-net/hu/aspose.slides.charts/iaxis/actual_min_value/) | Megadja a tengely tényleges minimális értékét. Előzőleg hívd meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [`actual_major_unit`](/slides/python-net/hu/aspose.slides.charts/iaxis/actual_major_unit/) | Megadja a tengely tényleges nagy egységét. Előzőleg hívd meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [`actual_minor_unit`](/slides/python-net/hu/aspose.slides.charts/iaxis/actual_minor_unit/) | Megadja a tengely tényleges kicsi egységét. Előzőleg hívd meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [`actual_major_unit_scale`](/slides/python-net/hu/aspose.slides.charts/iaxis/actual_major_unit_scale/) | Megadja a tengely tényleges nagy egység skáláját. Előzőleg hívd meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [`actual_minor_unit_scale`](/slides/python-net/hu/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | Megadja a tengely tényleges kis egység skáláját. Előzőleg hívd meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [`is_automatic_max_value`](/slides/python-net/hu/aspose.slides.charts/iaxis/is_automatic_max_value/) | Jeli, hogy a maximális érték automatikusan van-e hozzárendelve.<br/>             Olvasás/írás **bool**. |
| [`max_value`](/slides/python-net/hu/aspose.slides.charts/iaxis/max_value/) | Jeli az értéktengely maximális értékét.<br/>             Olvasás/írás **float**. |
| [`minor_unit`](/slides/python-net/hu/aspose.slides.charts/iaxis/minor_unit/) | Jeli a dátum- vagy értéktengely kisebb egységeit.<br/>             Olvasás/írás **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/hu/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | Jeli, hogy a tengely kisebb egysége automatikusan van-e hozzárendelve.<br/>             Olvasás/írás **bool**. |
| [`major_unit`](/slides/python-net/hu/aspose.slides.charts/iaxis/major_unit/) | Jeli a dátum- vagy értéktengely nagy egységeit.<br/>             Olvasás/írás **float**. |
| [`is_automatic_major_unit`](/slides/python-net/hu/aspose.slides.charts/iaxis/is_automatic_major_unit/) | Jeli, hogy a tengely nagy egysége automatikusan van-e hozzárendelve.<br/>            Olvasás/írás **bool**. |
| [`is_automatic_min_value`](/slides/python-net/hu/aspose.slides.charts/iaxis/is_automatic_min_value/) | Jeli, hogy a minimális érték automatikusan van-e hozzárendelve.<br/>             Olvasás/írás **bool**. |
| [`min_value`](/slides/python-net/hu/aspose.slides.charts/iaxis/min_value/) | Jeli az értéktengely minimális értékét.<br/>             Olvasás/írás **float**. |
| [`is_logarithmic`](/slides/python-net/hu/aspose.slides.charts/iaxis/is_logarithmic/) | Jeli, hogy az értéktengely skálatípusa logaritmikus-e vagy sem.<br/>             Olvasás/írás **bool**. |
| [`log_base`](/slides/python-net/hu/aspose.slides.charts/iaxis/log_base/) | Jeli a logaritmikus alapot. Alapértelmezett érték 10.<br/>             Olvasás/írás **float**. |
| [`is_plot_order_reversed`](/slides/python-net/hu/aspose.slides.charts/iaxis/is_plot_order_reversed/) | Jeli, hogy a MS PowerPoint az adatpontokat utolsótól az elsőig ábrázolja-e.<br/>             Olvasás/írás **bool**. |
| [`is_visible`](/slides/python-net/hu/aspose.slides.charts/iaxis/is_visible/) | Jeli, hogy a tengely látható-e.<br/>             Olvasás/írás **bool**. |
| [`major_tick_mark`](/slides/python-net/hu/aspose.slides.charts/iaxis/major_tick_mark/) | Jeli a megadott tengely nagy jelölőjeinek típusát.<br/>             Olvasás/írás [`TickMarkType`](/slides/python-net/hu/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/hu/aspose.slides.charts/iaxis/minor_tick_mark/) | Jeli a megadott tengely kis jelölőjeinek típusát.<br/>             Olvasás/írás [`TickMarkType`](/slides/python-net/hu/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/hu/aspose.slides.charts/iaxis/tick_label_position/) | Jeli a megadott tengelyen a jelölőcímkék pozícióját.<br/>             Olvasás/írás [`TickLabelPositionType`](/slides/python-net/hu/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/hu/aspose.slides.charts/iaxis/major_unit_scale/) | Jeli a dátumtengely nagy egység skáláját.<br/>             Olvasás/írás [`TimeUnitType`](/slides/python-net/hu/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/hu/aspose.slides.charts/iaxis/minor_unit_scale/) | Jeli a dátumtengely nagy egység skáláját.<br/>             Olvasás/írás [`TimeUnitType`](/slides/python-net/hu/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/hu/aspose.slides.charts/iaxis/base_unit_scale/) | Megadja a legkisebb időegységet, amely a dátumtengelyen megjelenik.<br/>            Olvasás/írás [`TimeUnitType`](/slides/python-net/hu/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/hu/aspose.slides.charts/iaxis/minor_grid_lines_format/) | Jeli a diagram tengelyen a kisebb rácsvonalak formátumát.<br/>             Csak olvasható [`IChartLinesFormat`](/slides/python-net/hu/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/hu/aspose.slides.charts/iaxis/major_grid_lines_format/) | Jeli a diagram tengelyen a nagyobb rácsvonalak formátumát.<br/>             Csak olvasható [`IChartLinesFormat`](/slides/python-net/hu/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/hu/aspose.slides.charts/iaxis/show_minor_grid_lines/) | Jeli, hogy a kisebb rácsvonalak megjelennek-e.<br/>             Csak olvasható **bool**. |
| [`show_major_grid_lines`](/slides/python-net/hu/aspose.slides.charts/iaxis/show_major_grid_lines/) | Jeli, hogy a nagyobb rácsvonalak megjelennek-e.<br/>             Csak olvasható **bool**. |
| [`format`](/slides/python-net/hu/aspose.slides.charts/iaxis/format/) | Jeli a tengely formátumát.<br/>             Csak olvasható [`IAxisFormat`](/slides/python-net/hu/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/hu/aspose.slides.charts/iaxis/title/) | Megkapja a tengely címét.<br/>             Csak olvasható [`IChartTitle`](/slides/python-net/hu/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/hu/aspose.slides.charts/iaxis/cross_type/) | Jeli a megadott tengelyen a kereszt típusát, ahol a másik tengely keresztezi.<br/>             Olvasás/írás [`CrossesType`](/slides/python-net/hu/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/hu/aspose.slides.charts/iaxis/position/) | Jeli a tengely pozícióját.<br/>             Olvasás/írás [`AxisPositionType`](/slides/python-net/hu/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/hu/aspose.slides.charts/iaxis/has_title/) | Megállapítja, hogy a tengelynek van-e látható címe.<br/>            Olvasás/írás **bool**. |
| [`number_format`](/slides/python-net/hu/aspose.slides.charts/iaxis/number_format/) | Jeli a tengelycímkék formátumkarakterláncát.<br/>            Olvasás/írás **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/hu/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | Jeli, hogy a formátum forrásadatokhoz kapcsolódik-e.<br/>            Olvasás/írás **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/hu/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | Jeli a jelölőcímkék forgatási szögét<br/>            Olvasás/írás **float**. |
| [`tick_label_spacing`](/slides/python-net/hu/aspose.slides.charts/iaxis/tick_label_spacing/) | Megadja, hogy hány jelölőcímkét kell kihagyni a megjelenített címke között.<br/>            Olvasás/írás **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/hu/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | Megadja az automatikus jelölőcímke távolságértékét. Ha hamis: használd a TickLabelSpacing tulajdonságot.<br/>            Olvasás/írás **bool**. |
| [`tick_marks_spacing`](/slides/python-net/hu/aspose.slides.charts/iaxis/tick_marks_spacing/) | Megadja, hogy hány jelölővonalat kell kihagyni, mielőtt a következő megjelenik<br/>            rajzolva. Kategória vagy sor tengelyre alkalmazható.<br/>            Olvasás/írás **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/hu/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | Megadja az automatikus jelölővonalak távolságértékét. Ha hamis: használd a TickMarksSpacing tulajdonságot.<br/>            Olvasás/írás **bool**. |
| [`label_offset`](/slides/python-net/hu/aspose.slides.charts/iaxis/label_offset/) | Megadja a címkék távolságát a tengelytől. Kategória vagy dátumtengelyre alkalmazható. Az értéknek 0% és 1000% között kell lennie.<br/>            Olvasás/írás **int**. |
| [`category_axis_type`](/slides/python-net/hu/aspose.slides.charts/iaxis/category_axis_type/) | Megadja a kategória tengely típusát.<br/>            Olvasás/írás [`IAxis.category_axis_type`](/slides/python-net/hu/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/hu/aspose.slides.charts/iaxis/aggregation_type/) | Jeli a kategória tengely aggregációs típusát (binning). Kategóriára alkalmazható. Csak Histogram vagy HistogramPareto sorokkal használható. |
| [`bin_width`](/slides/python-net/hu/aspose.slides.charts/iaxis/bin_width/) | Megadja a bin szélességét, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth-ra van beállítva.<br/>            Kategória tengelyekre alkalmazható. Csak Histogram vagy HistogramPareto sorokkal használható. |
| [`number_of_bins`](/slides/python-net/hu/aspose.slides.charts/iaxis/number_of_bins/) | Megadja a bin-ek számát, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins-ra van beállítva.<br/>            Kategória tengelyekre alkalmazható. Csak Histogram vagy HistogramPareto sorokkal használható. |
| [`is_overflow_bin`](/slides/python-net/hu/aspose.slides.charts/iaxis/is_overflow_bin/) | Jeli, hogy az overflow bin alkalmazva van-e. Használd az IsAutomaticOverflowBin és OverflowBin elemeket az overflow bin értékének beállításához. |
| [`is_automatic_overflow_bin`](/slides/python-net/hu/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | Megadja az automatikus overflow bin értékét. Ha hamis: használd az OverflowBin tulajdonságot. |
| [`overflow_bin`](/slides/python-net/hu/aspose.slides.charts/iaxis/overflow_bin/) | Megadja az overflow bin egyéni értékét. Akkor alkalmazott, ha az IsAutomaticOverflowBin tulajdonság hamisra van állítva és az IsOverflowBin tulajdonság igaz. |
| [`is_underflow_bin`](/slides/python-net/hu/aspose.slides.charts/iaxis/is_underflow_bin/) | Jeli, hogy az underflow bin alkalmazva van-e. Használd az IsAutomaticUnderflowBin és UnderflowBin elemeket az underflow bin értékének beállításához. |
| [`is_automatic_underflow_bin`](/slides/python-net/hu/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | Megadja az automatikus underflow bin értékét. Ha hamis: használd az UnderflowBin tulajdonságot. |
| [`underflow_bin`](/slides/python-net/hu/aspose.slides.charts/iaxis/underflow_bin/) | Megadja az underflow bin egyéni értékét. Akkor alkalmazott, ha az IsAutomaticUnderflowBin tulajdonság hamisra van állítva és az IsUnderflowBin tulajdonság igaz. |
| [`text_format`](/slides/python-net/hu/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/hu/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/hu/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides.charts/iaxis/presentation/) |  |

## Metódusok

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/hu/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | Beállítja az IAxis.CategoryAxisType tulajdonságot egy, a tengely adatain alapuló automatikusan meghatározott értékkel. |

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)