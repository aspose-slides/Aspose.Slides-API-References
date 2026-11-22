---
title: IChartSeriesGroup class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup třída

Představuje skupinu řad.

Typ IChartSeriesGroup exponuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/type/) | Vrací typ této skupiny řad.<br/>            Pouze ke čtení [`CombinableSeriesTypesGroup`](/slides/python-net/cs/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Určuje, zda jsou řady této skupiny vykresleny na sekundární ose.<br/>            Pouze ke čtení **bool**. |
| [`series`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/series/) | Vrací jen pro čtení kolekci řad grafu.<br/>            Pouze ke čtení [`IChartSeriesReadonlyCollection`](/slides/python-net/cs/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Poskytuje přístup k horním/dolním pruhům v čárovém nebo burzovním grafu.<br/>            Pouze ke čtení [`IUpDownBarsManager`](/slides/python-net/cs/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/gap_width/) | Získá nebo nastaví mezeru mezi shluky pruhů nebo sloupců jako procento šířky pruhu nebo sloupce.<br/>            Hodnota musí být mezi 0 a 500.<br/>            Čtení/zápis **int**. |
| [`gap_depth`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Získá nebo nastaví vzdálenost mezi datovými řadami ve 3D grafu jako procento šířky značky.<br/>            Hodnota musí být mezi 0 a 500.<br/>            Čtení/zápis **int**. |
| [`first_slice_angle`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Získá nebo nastaví úhel první výseče koláčového nebo prstencového grafu, <br/>            ve stupních (ve směru hodinových ručiček od shora, od 0 do 360 stupňů).<br/>            Čtení/zápis **int**. |
| [`is_color_varied`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Určuje, že každý datový značkovač v řadě má jinou barvu.<br/>            Čtení/zápis **bool**. |
| [`has_series_lines`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | True pokud graf má čáry řad. Použito u sloupcových grafů se zásobníkem a grafů OfPie.<br/>            Čtení/zápis **bool**. |
| [`overlap`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/overlap/) | Určuje, jak moc se mají pruhy a sloupce překrývat v 2-D grafech, jako procento (od -100 % do 100 %).<br/>             - -100 %: Maximální rozestup (pruhy jsou zcela odděleny).<br/>             - 0 %: Průhledy jsou umístěny vedle sebe bez překrytí nebo mezery.<br/>             - 100 %: Maximální překrytí (pruhy se zcela překrývají).<br/>             Tato vlastnost je čtení/zápis **int**. |
| [`second_pie_size`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Určuje velikost druhé výseče nebo pruhu v grafu pie-of-pie nebo grafu bar-of-pie jako procento velikosti první výseče (může <br/>            být mezi 5 a 200 procent).<br/>            Čtení/zápis **int**. |
| [`pie_split_position`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Určuje hodnotu, která bude použita k určení, které datové body <br/>            jsou ve druhé výseči nebo pruhu v grafu pie-of-pie nebo bar-of-pie.<br/>            Používá se společně s vlastností PieSplitBy.<br/>            Čtení/zápis **float**. |
| [`pie_split_by`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Určuje, jak určit, které datové body jsou ve druhé výseči nebo pruhu <br/>            v grafu pie-of-pie nebo bar-of-pie.<br/>            Čtení/zápis [`PieSplitType`](/slides/python-net/cs/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením.<br/>            Obsahuje datové body, které mají být vykresleny ve druhé výseči nebo pruhu v grafu pie-of-pie nebo <br/>            bar-of-pie.<br/>            Pouze ke čtení [`IPieSplitCustomPointCollection`](/slides/python-net/cs/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Určuje velikost díry v prstencovém grafu (může být mezi 10 a 90 procenty <br/>            velikosti vykreslovací oblasti).<br/>            Čtení/zápis **int**. |
| [`bubble_size_scale`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Určuje škálovací faktor pro bublinový graf (může být <br/>            mezi 0 a 300 procenty výchozí velikosti).<br/>            Čtení/zápis **int**. |
| [`hi_low_lines_format`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Určuje formát HiLowLines. <br/>            HiLowLines se používá s typy grafů HiLowClose, OpenHiLowClose, VolumeHiLowClose a VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Určuje, jak jsou hodnoty velikosti bublin reprezentovány v bublinovém grafu.<br/>            Čtení/zápis [`BubbleSizeRepresentationType`](/slides/python-net/cs/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Získá prvek na zadaném indexu.

## Indexér

| Název | Popis |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### Poznámky

1) Viz souhrn a poznámky pro ChartSeriesGroupCollection třída a CombinableSeriesTypesGroup enum.  
2) Skupina řad obsahuje některé vlastnosti řad, které jsou společné pro každou řadu ve skupině („vlastnosti skupiny řad“).  
„Vlastnosti skupiny řad“ v ChartSeriesGroup třída jsou čtení/zápis.  
Každá z „vlastností skupiny řad“ může mít pouze ke čtení projekci v ChartSeries třída.

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)