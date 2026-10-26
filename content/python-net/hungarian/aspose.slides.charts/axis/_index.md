---
title: Axis class
second_title: Aspose.Slides a Python számára .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides.charts/axis/
---
## Axis osztály

Befoglalja azt az objektumot, amely egy diagram tengelyét képviseli.

Az Axis típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`chart`](/slides/python-net/hu/aspose.slides.charts/axis/chart/) | Visszaadja a szülő diagramot.<br/>            Csak olvasható [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/hu/aspose.slides.charts/axis/axis_between_categories/) | Jelöli, hogy az érték tengely keresztezi-e a kategória tengelyt a kategóriák között.<br/>             Ez a tulajdonság csak a kategória tengelyekre vonatkozik, és nem érvényes 3D diagramokra.<br/>             Olvasás/írás **bool**. |
| [`category_axis_type`](/slides/python-net/hu/aspose.slides.charts/axis/category_axis_type/) | Megadja a kategória tengely típusát.<br/>            Olvasás/írás [`CategoryAxisType`](/slides/python-net/hu/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/hu/aspose.slides.charts/axis/cross_at/) | Jelöli azt a pontot a tengelyen, ahol a merőleges tengely áthalad rajta.<br/>             Olvasás/írás **float**. |
| [`display_unit`](/slides/python-net/hu/aspose.slides.charts/axis/display_unit/) | Megadja az érték tengely megjelenítési egységeinek méretezési értékét.<br/>             Olvasás/írás [`DisplayUnitType`](/slides/python-net/hu/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/hu/aspose.slides.charts/axis/actual_max_value/) | Megadja a tengely tényleges legnagyobb értékét. Előzőleg hívd meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [`actual_min_value`](/slides/python-net/hu/aspose.slides.charts/axis/actual_min_value/) | Megadja a tengely tényleges legkisebb értékét. Előzőleg hívd meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [`actual_major_unit`](/slides/python-net/hu/aspose.slides.charts/axis/actual_major_unit/) | Megadja a tengely tényleges fő egységét. Előzőleg hívd meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [`actual_minor_unit`](/slides/python-net/hu/aspose.slides.charts/axis/actual_minor_unit/) | Megadja a tengely tényleges alárendelt egységét. Előzőleg hívd meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [`actual_major_unit_scale`](/slides/python-net/hu/aspose.slides.charts/axis/actual_major_unit_scale/) | Megadja a tengely tényleges fő egység skáláját. Előzőleg hívd meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [`actual_minor_unit_scale`](/slides/python-net/hu/aspose.slides.charts/axis/actual_minor_unit_scale/) | Megadja a tengely tényleges alárendelt egység skáláját. Előzőleg hívd meg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez. |
| [`is_automatic_max_value`](/slides/python-net/hu/aspose.slides.charts/axis/is_automatic_max_value/) | J elzi, hogy a legnagyobb érték automatikusan van-e hozzárendelve.<br/>             Olvasás/írás **bool**. |
| [`max_value`](/slides/python-net/hu/aspose.slides.charts/axis/max_value/) | Jelöli az érték tengely maximális értékét.<br/>             Olvasás/írás **float**. |
| [`minor_unit`](/slides/python-net/hu/aspose.slides.charts/axis/minor_unit/) | Jelöli a dátum vagy érték tengely alárendelt egységeit.<br/>             Olvasás/írás **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/hu/aspose.slides.charts/axis/is_automatic_minor_unit/) | Jelzi, hogy a tengely alárendelt egysége automatikusan van-e hozzárendelve.<br/>             Olvasás/írás **bool**. |
| [`major_unit`](/slides/python-net/hu/aspose.slides.charts/axis/major_unit/) | Jelöli a dátum vagy érték tengely fő egységeit.<br/>             Olvasás/írás **float**. |
| [`is_automatic_major_unit`](/slides/python-net/hu/aspose.slides.charts/axis/is_automatic_major_unit/) | Jelzi, hogy a tengely fő egysége automatikusan van-e hozzárendelve.<br/>            Olvasás/írás **bool**. |
| [`is_automatic_min_value`](/slides/python-net/hu/aspose.slides.charts/axis/is_automatic_min_value/) | Jelzi, hogy a legkisebb érték automatikusan van-e hozzárendelve.<br/>             Olvasás/írás **bool**. |
| [`min_value`](/slides/python-net/hu/aspose.slides.charts/axis/min_value/) | Jelöli az érték tengely legkisebb értékét.<br/>             Olvasás/írás **float**. |
| [`is_logarithmic`](/slides/python-net/hu/aspose.slides.charts/axis/is_logarithmic/) | Jelöli, hogy az érték tengely skála típusa logaritmikus-e vagy sem.<br/>             Olvasás/írás **bool**. |
| [`log_base`](/slides/python-net/hu/aspose.slides.charts/axis/log_base/) | Jelöli a logaritmikus alapot. Alapértelmezett érték 10.<br/>             Olvasás/írás **float**. |
| [`is_plot_order_reversed`](/slides/python-net/hu/aspose.slides.charts/axis/is_plot_order_reversed/) | Jelöli, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja-e.<br/>             Olvasás/írás **bool**. |
| [`is_visible`](/slides/python-net/hu/aspose.slides.charts/axis/is_visible/) | Jelöli, hogy a tengely látható-e.<br/>             Olvasás/írás **bool**. |
| [`major_tick_mark`](/slides/python-net/hu/aspose.slides.charts/axis/major_tick_mark/) | Jelöli a megadott tengely fő jelölőjelek típusát.<br/>             Olvasás/írás [`TickMarkType`](/slides/python-net/hu/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/hu/aspose.slides.charts/axis/minor_tick_mark/) | Jelöli a megadott tengely alárendelt jelölőjelek típusát.<br/>             Olvasás/írás [`TickMarkType`](/slides/python-net/hu/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/hu/aspose.slides.charts/axis/tick_label_position/) | Jelöli a jelölőcímkék pozícióját a megadott tengelyen.<br/>             Olvasás/írás [`TickLabelPositionType`](/slides/python-net/hu/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/hu/aspose.slides.charts/axis/major_unit_scale/) | Jelöli a dátum tengely fő egység skáláját.<br/>             Olvasás/írás [`TimeUnitType`](/slides/python-net/hu/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/hu/aspose.slides.charts/axis/minor_unit_scale/) | Jelöli a dátum tengely fő egység skáláját.<br/>             Olvasás/írás [`TimeUnitType`](/slides/python-net/hu/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/hu/aspose.slides.charts/axis/base_unit_scale/) | Megadja a legkisebb időegységet, amely a dátum tengelyen megjelenik.<br/>            Olvasás/írás [`TimeUnitType`](/slides/python-net/hu/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/hu/aspose.slides.charts/axis/minor_grid_lines_format/) | Jelöli a diagram tengely alárendelt rácsvonalainak formátumát.<br/>             Csak olvasható [`IChartLinesFormat`](/slides/python-net/hu/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/hu/aspose.slides.charts/axis/major_grid_lines_format/) | Jelöli a diagram tengely fő rácsvonalainak formátumát.<br/>             Csak olvasható [`IChartLinesFormat`](/slides/python-net/hu/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/hu/aspose.slides.charts/axis/show_minor_grid_lines/) | Az alárendelt rácsvonal elrejtéséhez állítsd a MinorGridLinesFormat.Line.FillFormat.FillType értékét FillType.NoFill-re.<br/>            Csak olvasható **bool**. |
| [`show_major_grid_lines`](/slides/python-net/hu/aspose.slides.charts/axis/show_major_grid_lines/) | A fő rácsvonal elrejtéséhez állítsd a MajorGridLinesFormat.Line.FillFormat.FillType értékét FillType.NoFill-re.<br/>            Csak olvasható **bool**. |
| [`format`](/slides/python-net/hu/aspose.slides.charts/axis/format/) | Jelöli a tengely formátumát.<br/>             Csak olvasható [`IAxisFormat`](/slides/python-net/hu/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/hu/aspose.slides.charts/axis/text_format/) | Jelöli a szöveg formátumát.<br/>             Csak olvasható [`IChartTextFormat`](/slides/python-net/hu/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/hu/aspose.slides.charts/axis/title/) | Lekéri a tengely címét.<br/>             Csak olvasható [`IChartTitle`](/slides/python-net/hu/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/hu/aspose.slides.charts/axis/cross_type/) | Jelöli a CrossType értékét a megadott tengelyen, ahol a másik tengely keresztezi.<br/>             Olvasás/írás [`CrossesType`](/slides/python-net/hu/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/hu/aspose.slides.charts/axis/position/) | Jelöli a tengely pozícióját.<br/>             Olvasás/írás [`AxisPositionType`](/slides/python-net/hu/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/hu/aspose.slides.charts/axis/has_title/) | Meghatározza, hogy a tengelynek van-e látható címe.<br/>            Olvasás/írás **bool**. |
| [`number_format`](/slides/python-net/hu/aspose.slides.charts/axis/number_format/) | Jelöli a tengelycímkék formátumkarakterláncát.<br/>            Olvasás/írás **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/hu/aspose.slides.charts/axis/is_number_format_linked_to_source/) | Jelzi, hogy a formátum kapcsolódik-e a forrásadatokhoz.<br/>            Olvasás/írás **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/hu/aspose.slides.charts/axis/tick_label_rotation_angle/) | Jelöli a jelölőcímkék forgásszögét.<br/>            Olvasás/írás **float**. |
| [`tick_label_spacing`](/slides/python-net/hu/aspose.slides.charts/axis/tick_label_spacing/) | Megadja, hány jelölőcímkét kell kihagyni a megjelenített címke között. Alkalmazható kategória vagy sorozat tengelyre.<br/>            Olvasás/írás **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/hu/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | Megadja az automatikus jelölőcímke távolság értékét. Ha hamis, használja a TickLabelSpacing tulajdonságot.<br/>            Olvasás/írás **bool**. |
| [`tick_marks_spacing`](/slides/python-net/hu/aspose.slides.charts/axis/tick_marks_spacing/) | Megadja, hány jelölőt kell kihagyni a következő megjelenítése előtt.<br/>            Alkalmazható kategória vagy sorozat tengelyre.<br/>            Olvasás/írás **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/hu/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | Megadja az automatikus jelölő távolság értékét. Ha hamis, használja a TickMarksSpacing tulajdonságot.<br/>            Olvasás/írás **bool**. |
| [`label_offset`](/slides/python-net/hu/aspose.slides.charts/axis/label_offset/) | Megadja a címkék távolságát a tengelytől. Alkalmazható kategória vagy dátum tengelyre. Az értéknek 0% és 1000% között kell lennie.<br/>            Olvasás/írás **int**. |
| [`aggregation_type`](/slides/python-net/hu/aspose.slides.charts/axis/aggregation_type/) | Jelöli a kategória tengely aggregációs típusát (csoportosítás). Alkalmazható kategóriára. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| [`bin_width`](/slides/python-net/hu/aspose.slides.charts/axis/bin_width/) | Megadja a bin szélességét, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth.<br/>            Alkalmazható kategória tengelyekre. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| [`number_of_bins`](/slides/python-net/hu/aspose.slides.charts/axis/number_of_bins/) | Megadja a bin-ek számát, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins.<br/>            Alkalmazható kategória tengelyekre. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| [`is_overflow_bin`](/slides/python-net/hu/aspose.slides.charts/axis/is_overflow_bin/) | Megadja, hogy az overflow bin alkalmazva van-e. Használd az IsAutomaticOverflowBin és OverflowBin értékeket az overflow bin értékének beállításához. |
| [`is_automatic_overflow_bin`](/slides/python-net/hu/aspose.slides.charts/axis/is_automatic_overflow_bin/) | Megadja az automatikus overflow bin értékét. Ha hamis, használd az OverflowBin tulajdonságot. |
| [`overflow_bin`](/slides/python-net/hu/aspose.slides.charts/axis/overflow_bin/) | Megadja az overflow bin egyéni értékét. Alkalmazásra kerül, ha az IsAutomaticOverflowBin tulajdonság hamisra van állítva és az IsOverflowBin tulajdonság igaz. |
| [`is_underflow_bin`](/slides/python-net/hu/aspose.slides.charts/axis/is_underflow_bin/) | Megadja, hogy az underflow bin alkalmazva van-e. Használd az IsAutomaticUnderflowBin és UnderflowBin értékeket az underflow bin értékének beállításához. |
| [`is_automatic_underflow_bin`](/slides/python-net/hu/aspose.slides.charts/axis/is_automatic_underflow_bin/) | Megadja az automatikus underflow bin értékét. Ha hamis, használd az UnderflowBin tulajdonságot. |
| [`underflow_bin`](/slides/python-net/hu/aspose.slides.charts/axis/underflow_bin/) | Megadja az underflow bin egyéni értékét. Alkalmazásra kerül, ha az IsAutomaticUnderflowBin tulajdonság hamisra van állítva és az IsUnderflowBin tulajdonság igaz. |
| [`slide`](/slides/python-net/hu/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides.charts/axis/presentation/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/hu/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | Beállítja az IAxis.CategoryAxisType tulajdonságot egy olyan értékkel, amely automatikusan kerül meghatározásra a tengely adatai alapján. |

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)