---
title: ChartSeriesGroup class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup klass

Representerar en grupp av serier.

ChartSeriesGroup-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`type`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/type/) | Returnerar en typ av denna seriegrupp.<br/>            Endast läsning [`CombinableSeriesTypesGroup`](/slides/python-net/sv/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Anger om serier i denna grupp plottas på sekundär axel.<br/>            Endast läsning **bool**. |
| [`series`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/series/) | Returnerar en samling av serier.<br/>            Endast läsning [`IChartSeriesReadonlyCollection`](/slides/python-net/sv/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Tillhandahåller åtkomst till upp-/nedstaplar i linje- eller aktiediagram.<br/>            Endast läsning [`IUpDownBarsManager`](/slides/python-net/sv/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/gap_width/) | Hämtar eller anger utrymmet mellan stapel- eller kolumnkluster, som en procentandel av stapel- eller kolumnbredden.<br/>            Värdet måste vara mellan 0 och 500.<br/>            Läs/skriv **int**. |
| [`gap_depth`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/gap_depth/) | Hämtar eller anger avståndet mellan dataserier i ett 3D-diagram, som en procentandel av markörbredden.<br/>            Värdet måste vara mellan 0 och 500.<br/>            Läs/skriv **int**. |
| [`first_slice_angle`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Hämtar eller anger vinkeln på den första paj- eller munkdiagramsegmentet, <br/>            i grader (medurs från toppen, från 0 till 360 grader).<br/>            Läs/skriv **int**. |
| [`doughnut_hole_size`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Anger storleken på hålet i ett munkdiagram (kan vara mellan 0 och 90 procent <br/>            av storleken på plotområdet).<br/>            Läs/skriv **int**. |
| [`overlap`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/overlap/) | Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som en procentandel (från -100 % till 100 %).<br/>             - -100 %: Maximal avstånd (staplar är helt separerade).<br/>             - 0 %: Staplar placeras sida vid sida utan överlappning eller avstånd.<br/>             - 100 %: Maximal överlappning (staplar överlappar helt varandra).<br/>             Denna egenskap är läs/skriv **int**. |
| [`second_pie_size`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Anger storleken på den andra pajen eller stapeln i ett paj-i-paj-diagram eller <br/>            ett stapel-i-paj-diagram, som en procentandel av storleken på den första pajen (kan <br/>            vara mellan 5 och 200 procent).<br/>            Läs/skriv **int**. |
| [`bubble_size_representation`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Anger hur bubblastorleksvärden representeras i bubbeldiagrammet.<br/>            Läs/skriv [`BubbleSizeRepresentationType`](/slides/python-net/sv/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Anger ett värde som ska användas för att bestämma vilka datapunkter <br/>            som är i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. <br/>            Används tillsammans med egenskapen PieSplitBy.<br/>            Läs/skriv **float**. |
| [`pie_split_by`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Anger hur man bestämmer vilka datapunkter som är i den andra pajen eller stapeln <br/>            i ett paj-i-paj- eller stapel-i-paj-diagram.<br/>            Läs/skriv [`PieSplitType`](/slides/python-net/sv/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Anger att varje datamarkör i serien har en annan färg.<br/>            Läs/skriv **bool**. |
| [`has_series_lines`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Sant om diagrammet har serielinjer. Gäller staplade staplar och OfPie-diagram.<br/>            Läs/skriv **bool**. |
| [`hi_low_lines_format`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Anger formatet för HiLowLines. <br/>            HiLowLines tillämpas med HiLowClose, OpenHiLowClose, VolumeHiLowClose och VolumeOpenHiLowClose diagramtyper. |
| [`bubble_size_scale`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Anger skalningsfaktorn för bubbeldiagrammet (kan vara <br/>            mellan 0 och 300 procent av standardstorleken).<br/>            Läs/skriv **int**. |
| [`pie_split_custom_points`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Den anpassade split-informationen för ett paj-i-paj- eller stapel-i-paj-diagram med en anpassad split.<br/>            Innehåller datapunkter som ska ritas i den andra pajen eller stapeln i ett paj-i-paj- eller <br/>            stapel-i-paj-diagram.<br/>            Endast läsning [`PieSplitCustomPointCollection`](/slides/python-net/sv/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/chart/) | Returnerar det överordnade diagrammet.<br/>            Endast läsning [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Hämtar elementet på det angivna indexet.

## Indexer

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### Anmärkningar

1) Se sammanfattning och anmärkningar för ChartSeriesGroupCollection-klass och CombinableSeriesTypesGroup-enum.
            2) Grupp av serier innehåller vissa serieegenskaper som är gemensamma för 
            varje serie i gruppen (\"series group properties\").
            \"Series group properties\" i ChartSeriesGroup-klass är läs/skriv.
            Varje av \"series group properties\" kan ha en endaläsningsprojektion i ChartSeries-klass.


### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)