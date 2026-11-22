---
title: IChartSeriesGroup class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup klass

Representerar grupp av serier.

IChartSeriesGroup-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`type`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/type/) | Returnerar en typ av denna seriegroupp.<br/>            Skrivskyddad [`CombinableSeriesTypesGroup`](/slides/python-net/sv/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Indikerar om serierna i denna grupp plottas på sekundär axel.<br/>            Skrivskyddad **bool**. |
| [`series`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/series/) | Returnerar en skrivskyddad samling av diagramserier.<br/>            Skrivskyddad [`IChartSeriesReadonlyCollection`](/slides/python-net/sv/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Tillhandahåller åtkomst till upp/ner staplar i linje- eller aktiediagram.<br/>            Skrivskyddad [`IUpDownBarsManager`](/slides/python-net/sv/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/gap_width/) | Hämtar eller ställer in avståndet mellan stapel- eller kolumnkluster, som en procentandel av stapel- eller kolumnbredden.<br/>            Värdet måste vara mellan 0 och 500.<br/>            Läs/skriv **int**. |
| [`gap_depth`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Hämtar eller ställer in avståndet mellan dataserier i ett 3D-diagram, som en procentandel av markörens bredd.<br/>            Värdet måste vara mellan 0 och 500.<br/>            Läs/skriv **int**. |
| [`first_slice_angle`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Hämtar eller ställer in vinkeln på det första paj- eller donutdiagrammets segment, <br/>            i grader (medurs från upp, från 0 till 360 grader).<br/>            Läs/skriv **int**. |
| [`is_color_varied`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Anger att varje datamarkör i serien har en annan färg.<br/>            Läs/skriv **bool**. |
| [`has_series_lines`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Sant om diagrammet har serielinjer. Tillämpas på staplade stapeldiagram och OfPie-diagram.<br/>            Läs/skriv **bool**. |
| [`overlap`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/overlap/) | Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som en procentandel (från -100% till 100%).<br/>             - -100%: Maximum spacing (bars are completely separated).<br/>             - 0%: Bars are placed side by side without overlap or spacing.<br/>             - 100%: Maximum overlap (bars completely overlap each other).<br/>             Denna egenskap är Läs/skriv **int**. |
| [`second_pie_size`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Anger storleken på den andra pajen eller stapeln i ett paj-av-paj-diagram eller <br/>            ett stapel-av-paj-diagram, som en procentandel av storleken på den första pajen (kan <br/>            vara mellan 5 och 200%).<br/>            Läs/skriv **int**. |
| [`pie_split_position`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Anger ett värde som ska användas för att bestämma vilka datapunkter <br/>            som är i den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram. <br/>            Används tillsammans med egenskapen PieSplitBy.<br/>            Läs/skriv **float**. |
| [`pie_split_by`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Anger hur man bestämmer vilka datapunkter som är i den andra pajen eller stapeln <br/>            i ett paj-av-paj- eller stapel-av-paj-diagram.<br/>            Läs/skriv [`PieSplitType`](/slides/python-net/sv/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Den anpassade delningsinformationen för ett paj-av-paj- eller stapel-av-paj-diagram med en anpassad delning.<br/>            Innehåller datapunkter som ska ritas i den andra pajen eller stapeln i ett paj-av-paj- eller <br/>            stapel-av-paj-diagram.<br/>            Skrivskyddad [`IPieSplitCustomPointCollection`](/slides/python-net/sv/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Anger storleken på hålet i ett donutdiagram (kan vara mellan 10 och 90% av storleken på plot-området).<br/>            Läs/skriv **int**. |
| [`bubble_size_scale`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Anger skalningsfaktorn för bubbel-diagrammet (kan vara <br/>            mellan 0 och 300% av standardstorleken).<br/>            Läs/skriv **int**. |
| [`hi_low_lines_format`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Anger HiLowLines-format. <br/>            HiLowLines används med HiLowClose, OpenHiLowClose, VolumeHiLowClose och VolumeOpenHiLowClose-diagramtyper. |
| [`bubble_size_representation`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Anger hur bubbelstorleksvärden representeras i bubbeldiagrammet.<br/>            Läs/skriv [`BubbleSizeRepresentationType`](/slides/python-net/sv/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Hämtar elementet på det angivna indexet.

## Indexer

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |


### Anmärkningar

1) Se sammanfattning och anmärkningar för ChartSeriesGroupCollection klass och CombinableSeriesTypesGroup enum.  
2) Grupp av serier innehåller vissa serieegenskaper som är gemensamma för varje serie i gruppen ("series group properties").  
"Series group properties" i ChartSeries klass är Läs/skriv.  
Varje av "series group properties" kan ha en skrivskyddad projektion i ChartSeries klass.

### Se också
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)