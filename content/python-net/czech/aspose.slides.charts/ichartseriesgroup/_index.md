---
title: IChartSeriesGroup class
second_title: Aspose.Slides pro Python přes .NET referenční příručku API
description: 
type: docs
url: /cs/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup třída

Představuje skupinu řad.

Typ IChartSeriesGroup poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`type`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/type/) | Vrací typ této skupiny řad.<br/>            Pouze pro čtení [`CombinableSeriesTypesGroup`](/slides/python-net/cs/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Indikuje, zda jsou řady této skupiny vykresleny na sekundární ose.<br/>            Pouze pro čtení **bool**. |
| [`series`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/series/) | Vrací kolekci řad grafu pouze pro čtení.<br/>            Pouze pro čtení [`IChartSeriesReadonlyCollection`](/slides/python-net/cs/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Poskytuje přístup k horním/dolním pruhům u čárového nebo akciového grafu.<br/>            Pouze pro čtení [`IUpDownBarsManager`](/slides/python-net/cs/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/gap_width/) | Určuje prostor mezi shluky sloupců nebo pruhů jako procento šířky sloupce nebo pruhu.<br/>            Čtení/zápis **int**. |
| [`gap_depth`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Vrací nebo nastavuje vzdálenost jako procento šířky značky mezi datovými řadami ve 3D grafu.<br/>            Čtení/zápis **int**. |
| [`first_slice_angle`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Získává nebo nastavuje úhel první řezu koláčového nebo prsteníkového grafu, <br/>            ve stupních (ve směru hodinových ručiček od shora, od 0 do 360 stupňů).<br/>            Čtení/zápis **int**. |
| [`is_color_varied`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Určuje, že každý datový marker v řadě má jinou barvu.<br/>            Čtení/zápis **bool**. |
| [`has_series_lines`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Pravda, pokud graf obsahuje čáry řad. Používá se u sloupcových grafů s hromaděním a grafů OfPie.<br/>            Čtení/zápis **bool**. |
| [`overlap`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/overlap/) | Určuje, jak moc se mají sloupce a pruhy překrývat v 2-D grafech, jako procento (od -100 % do 100 %).<br/>             - -100 %: Maximální mezera (sloupce jsou zcela odděleny).<br/>             - 0 %: Sloupce jsou umístěny vedle sebe bez překrytí nebo mezery.<br/>             - 100 %: Maximální překrytí (sloupce se zcela překrývají).<br/>             Tato vlastnost je čtení/zápis **int**. |
| [`second_pie_size`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Určuje velikost druhého koláče nebo pruhu v grafu pie-of-pie nebo bar-of-pie jako procento velikosti prvního koláče (může být mezi 5 a 200 %).<br/>            Čtení/zápis **int**. |
| [`pie_split_position`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém koláči nebo pruhu v grafu pie-of-pie nebo bar-of-pie.<br/>            Používá se spolu s vlastností PieSplitBy.<br/>            Čtení/zápis **float**. |
| [`pie_split_by`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Určuje, jak určit, které datové body jsou ve druhém koláči nebo pruhu v grafu pie-of-pie nebo bar-of-pie.<br/>            Čtení/zápis [`PieSplitType`](/slides/python-net/cs/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením.<br/>            Obsahuje datové body, které mají být vykresleny ve druhém koláči nebo pruhu v grafu pie-of-pie nebo <br/>            bar-of-pie.<br/>            Pouze pro čtení [`IPieSplitCustomPointCollection`](/slides/python-net/cs/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Určuje velikost otvoru v prsteníkovém grafu (může být mezi 10 a 90 % velikosti vykreslovací oblasti).<br/>            Čtení/zápis **int**. |
| [`bubble_size_scale`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Určuje měřítkový faktor pro bublinový graf (může být mezi 0 a 300 % výchozí velikosti).<br/>            Čtení/zápis **int**. |
| [`hi_low_lines_format`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Určuje formát HiLowLines.<br/>            HiLowLines se používá s typy grafů HiLowClose, OpenHiLowClose, VolumeHiLowClose a VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Určuje, jak jsou hodnoty velikosti bublin zobrazovány v bublinovém grafu.<br/>            Čtení/zápis [`BubbleSizeRepresentationType`](/slides/python-net/cs/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Získá prvek na zadaném indexu.

## Indexér

| Název | Popis |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### Poznámky

1) Viz souhrn a poznámky pro třídu ChartSeriesGroupCollection a enum CombinableSeriesTypesGroup.  
2) Skupina řad obsahuje některé vlastnosti řad, které jsou společné pro každou řadu ve skupině („vlastnosti skupiny řad“).  
„Vlastnosti skupiny řad“ v třídě ChartSeriesGroup jsou čtení/zápis.  
Každá z „vlastností skupiny řad“ může mít v třídě ChartSeries projekci pouze pro čtení.

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)