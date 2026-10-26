---
title: IChartSeriesGroup class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup klass

Representerar en grupp av serier.

IChartSeriesGroup-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`type`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/type/) | Returnerar en typ av denna seriegrupp.<br/>            Skrivskyddad [`CombinableSeriesTypesGroup`](/slides/python-net/sv/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Anger om serierna i denna grupp plottas på sekundär axel.<br/>            Skrivskyddad **bool**. |
| [`series`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/series/) | Returnerar en skrivskyddad samling av diagramserier.<br/>            Skrivskyddad [`IChartSeriesReadonlyCollection`](/slides/python-net/sv/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Tillhandahåller åtkomst till upp/ner-staplar för linje- eller aktiediagram.<br/>            Skrivskyddad [`IUpDownBarsManager`](/slides/python-net/sv/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/gap_width/) | Anger avståndet mellan stapel- eller kolumnkluster som en procentsats av stapel- eller kolumnbredden.<br/>            Läs/skriv **int**. |
| [`gap_depth`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Returnerar eller sätter avståndet, som en procentsats av markörens bredd, mellan dataserier i ett 3D-diagram.<br/>            Läs/skriv **int**. |
| [`first_slice_angle`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Hämtar eller anger vinkeln för den första paj- eller munkdiagramdelen, <br/>            i grader (medurs från uppåt, från 0 till 360 grader).<br/>            Läs/skriv **int**. |
| [`is_color_varied`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Anger att varje datapunkt i serien har en annan färg.<br/>            Läs/skriv **bool**. |
| [`has_series_lines`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Sant om diagrammet har serielinjer. Gäller staplade stapeldiagram och OfPie-diagram.<br/>            Läs/skriv **bool**. |
| [`overlap`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/overlap/) | Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som en procentsats (från -100 % till 100 %).<br/>             - -100 %: Maximal avstånd (staplarna är helt separerade).<br/>             - 0 %: Staplarna placeras sida vid sida utan överlappning eller avstånd.<br/>             - 100 %: Maximal överlappning (staplarna överlappar varandra helt).<br/>             Denna egenskap är läs/skriv **int**. |
| [`second_pie_size`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Anger storleken på den andra paj- eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram, som en procentsats av storleken på den första pajen (kan <br/>            vara mellan 5 och 200 %).<br/>            Läs/skriv **int**. |
| [`pie_split_position`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Anger ett värde som ska användas för att bestämma vilka datapunkter <br/>            som ingår i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. <br/>            Används tillsammans med egenskapen PieSplitBy.<br/>            Läs/skriv **float**. |
| [`pie_split_by`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Anger hur man bestämmer vilka datapunkter som ingår i den andra pajen eller stapeln <br/>            i ett paj-i-paj- eller stapel-i-paj-diagram.<br/>            Läs/skriv [`PieSplitType`](/slides/python-net/sv/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Den anpassade split-informationen för ett paj-i-paj- eller stapel-i-paj-diagram med anpassad split.<br/>            Innehåller datapunkter som ska ritas i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram.<br/>            Skrivskyddad [`IPieSplitCustomPointCollection`](/slides/python-net/sv/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Anger storleken på hålet i ett munkdiagram (kan vara mellan 10 och 90 % av plot-områdets storlek).<br/>            Läs/skriv **int**. |
| [`bubble_size_scale`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Anger skalfaktorn för bubbeldiagrammet (kan vara <br/>            mellan 0 och 300 % av standardstorleken).<br/>            Läs/skriv **int**. |
| [`hi_low_lines_format`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Anger format för HiLowLines. <br/>            HiLowLines tillämpas med HiLowClose, OpenHiLowClose, VolumeHiLowClose och VolumeOpenHiLowClose diagramtyper. |
| [`bubble_size_representation`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Anger hur bubblestorleksvärden representeras i bubbeldiagrammet.<br/>            Läs/skriv [`BubbleSizeRepresentationType`](/slides/python-net/sv/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Hämtar elementet på det angivna indexet.

## Indexör

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |


### Anmärkningar

1) Se sammanfattning och anmärkningar för klassen ChartSeriesGroupCollection och enum CombinableSeriesTypesGroup.  
2) En grupp av serier innehåller vissa serieegenskaper som är gemensamma för varje serie i gruppen ("seriegruppsegenskaper").  
   "Seriegruppsegenskaper" i klassen ChartSeriesGroup är läs/skriv.  
   Varje "seriegruppsegenskap" kan ha en skrivskyddad projektion i klassen ChartSeries.

### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)