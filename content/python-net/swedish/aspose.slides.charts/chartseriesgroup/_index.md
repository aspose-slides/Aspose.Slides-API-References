---
title: ChartSeriesGroup class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup klass

Representerar en grupp av serier.

Typen ChartSeriesGroup exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`type`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/type/) | Returnerar en typ av den här seriegruppen.<br/>            Endast läsning [`CombinableSeriesTypesGroup`](/slides/python-net/sv/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Indikerar om serier i den här gruppen plottas på sekundär axel.<br/>            Endast läsning **bool**. |
| [`series`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/series/) | Returnerar en samling av serier.<br/>            Enda läsning [`IChartSeriesReadonlyCollection`](/slides/python-net/sv/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Tillhandahåller åtkomst till upp/ner-staplar i linje- eller aktiediagram.<br/>            Endast läsning [`IUpDownBarsManager`](/slides/python-net/sv/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/gap_width/) | Anger avståndet mellan stapel- eller kolumnkluster, som en procentsats av stapel- eller kolumnbredden.<br/>            Läs/skriv **int**. |
| [`gap_depth`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/gap_depth/) | Returnerar eller anger avståndet, som en procentsats av markörens bredd, mellan dataserier i ett 3D-diagram.<br/>            Läs/skriv **int**. |
| [`first_slice_angle`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Hämtar eller anger vinkeln för den första paj- eller munkdiagram-slice, <br/>            i grader (medurs från upp, från 0 till 360 grader).<br/>            Läs/skriv **int**. |
| [`doughnut_hole_size`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Anger storleken på hålet i ett munkdiagram (kan vara mellan 0 och 90 procent <br/>            av storleken på plot-området).<br/>            Läs/skriv **int**. |
| [`overlap`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/overlap/) | Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som en procentsats (från -100 % till 100 %).<br/>             - -100 %: Maximalt avstånd (staplar är helt separerade).<br/>             - 0 %: Staplar placeras sida-vid-sida utan överlappning eller avstånd.<br/>             - 100 %: Maximal överlappning (staplar överlappar varandra helt).<br/>            Denna egenskap är läs/skriv **int**. |
| [`second_pie_size`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Anger storleken på den andra pajen eller stapeln i ett paj-av-paj-diagram eller <br/>            ett stapel-av-paj-diagram, som en procentsats av storleken på den första pajen (kan <br/>            vara mellan 5 och 200 procent).<br/>            Läs/skriv **int**. |
| [`bubble_size_representation`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Anger hur bubbelstorleksvärden representeras i bubbel-diagrammet.<br/>            Läs/skriv [`BubbleSizeRepresentationType`](/slides/python-net/sv/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Anger ett värde som ska användas för att bestämma vilka datapunkter <br/>            som är i den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram. <br/>            Används tillsammans med egenskapen PieSplitBy.<br/>            Läs/skriv **float**. |
| [`pie_split_by`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Anger hur man bestämmer vilka datapunkter som är i den andra pajen eller stapeln <br/>            i ett paj-av-paj- eller stapel-av-paj-diagram.<br/>            Läs/skriv [`PieSplitType`](/slides/python-net/sv/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Anger att varje datamarkör i serien har en annan färg.<br/>            Läs/skriv **bool**. |
| [`has_series_lines`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Sant om diagrammet har serielinjer. Tillämpas på staplade staplar och OfPie-diagram.<br/>            Läs/skriv **bool**. |
| [`hi_low_lines_format`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Anger HiLowLines-format. <br/>            HiLowLines tillämpas med diagramtyperna HiLowClose, OpenHiLowClose, VolumeHiLowClose och VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Anger skalafaktorn för bubbel-diagrammet (kan vara <br/>            mellan 0 och 300 procent av standardstorleken).<br/>            Läs/skriv **int**. |
| [`pie_split_custom_points`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Den anpassade split-informationen för ett paj-av-paj- eller stapel-av-paj-diagram med en anpassad split.<br/>            Innehåller datapunkter som ska ritas i den andra pajen eller stapeln i ett paj-av-paj- eller <br/>            stapel-av-paj-diagram.<br/>            Endast läsning [`PieSplitCustomPointCollection`](/slides/python-net/sv/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/chart/) | Returnerar föräldradiagrammet.<br/>            Endast läsning [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Hämtar elementet på det angivna indexet.

## Indexer

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### Anmärkningar

1) Se sammanfattning och anmärkningar för klassen ChartSeriesGroupCollection och enum CombinableSeriesTypesGroup.
2) En grupp av serier innehåller vissa serieegenskaper som är gemensamma för 
   varje serie i gruppen ("seriegruppsegenskaper").
   "Seriegruppsegenskaper" i klassen ChartSeriesGroup är läs/skriv.
   Varje av "seriegruppsegenskaper" kan ha en skrivskyddad projektion i klassen ChartSeries.


### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)