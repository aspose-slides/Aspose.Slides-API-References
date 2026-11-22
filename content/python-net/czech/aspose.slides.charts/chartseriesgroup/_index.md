---
title: ChartSeriesGroup class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup třída

Representuje skupinu řad.

Typ ChartSeriesGroup exponuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/type/) | Vrací typ této skupiny řad.<br/>            Pouze pro čtení [`CombinableSeriesTypesGroup`](/slides/python-net/cs/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Udává, zda jsou řady této skupiny vykresleny na sekundární ose.<br/>            Pouze pro čtení **bool**. |
| [`series`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/series/) | Vrací kolekci řad.<br/>            Pouze pro čtení [`IChartSeriesReadonlyCollection`](/slides/python-net/cs/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Poskytuje přístup k up/down barům u čárového nebo akciového grafu.<br/>            Pouze pro čtení [`IUpDownBarsManager`](/slides/python-net/cs/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/gap_width/) | Získává nebo nastavuje vzdálenost mezi skupinami sloupců nebo pruhů jako procento šířky sloupce nebo pruhu.<br/>            Hodnota musí být mezi 0 a 500.<br/>            Čtení/zápis **int**. |
| [`gap_depth`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/gap_depth/) | Získává nebo nastavuje vzdálenost mezi datovými řadami ve 3D grafu jako procento šířky značky.<br/>            Hodnota musí být mezi 0 a 500.<br/>            Čtení/zápis **int**. |
| [`first_slice_angle`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Získává nebo nastavuje úhel prvního řezu koláčového nebo prstencového grafu, <br/>            ve stupních (po směru hodinových ručiček od horního, od 0 do 360 stupňů).<br/>            Čtení/zápis **int**. |
| [`doughnut_hole_size`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Určuje velikost díry v prstencovém grafu (může být mezi 0 a 90 % <br/>            velikosti vykreslovací plochy).<br/>            Čtení/zápis **int**. |
| [`overlap`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/overlap/) | Určuje, jak moc se mají sloupy a pruhy překrývat v 2-D grafech, jako procento (od -100 % do 100 %).<br/>             - -100 %: Maximální rozestup (sloupy jsou zcela oddělené).<br/>             - 0 %: Sloupy jsou umístěny vedle sebe bez překrytí či mezery.<br/>             - 100 %: Maximální překrytí (sloupy se zcela překrývají).<br/>             Tato vlastnost je čtení/zápis **int**. |
| [`second_pie_size`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Určuje velikost druhého výseku nebo pruhu v grafu koláč-v-koláči nebo pruh-v-koláči jako procento velikosti prvního výseku (může být mezi 5 a 200 %).<br/>            Čtení/zápis **int**. |
| [`bubble_size_representation`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Určuje, jak jsou hodnoty velikosti bublin zobrazeny v bublinovém grafu.<br/>            Čtení/zápis [`BubbleSizeRepresentationType`](/slides/python-net/cs/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém výseku nebo pruhu v grafu koláč-v-koláči nebo pruh-v-koláči. <br/>            Používá se spolu s vlastností PieSplitBy.<br/>            Čtení/zápis **float**. |
| [`pie_split_by`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Určuje, jak určit, které datové body jsou ve druhém výseku nebo pruhu v grafu koláč-v-koláči nebo pruh-v-koláči.<br/>            Čtení/zápis [`PieSplitType`](/slides/python-net/cs/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Určuje, že každý datový marker v řadě má jinou barvu.<br/>            Čtení/zápis **bool**. |
| [`has_series_lines`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Pravda, pokud graf má čáry řad. Používá se u sloupcových grafů se shlukem a grafů OfPie.<br/>            Čtení/zápis **bool**. |
| [`hi_low_lines_format`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Určuje formát HiLowLines.<br/>            HiLowLines se používá s typy grafů HiLowClose, OpenHiLowClose, VolumeHiLowClose a VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Určuje měřítkový faktor pro bublinový graf (může být <br/>            mezi 0 a 300 % výchozí velikosti).<br/>            Čtení/zápis **int**. |
| [`pie_split_custom_points`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Vlastní informace o rozdělení pro graf koláč-v-koláči nebo pruh-v-koláči s vlastním rozdělením.<br/>            Obsahuje datové body, které mají být vykresleny ve druhém výseku nebo pruhu v grafu koláč-v-koláči nebo <br/>            pruh-v-koláči.<br/>            Pouze pro čtení [`PieSplitCustomPointCollection`](/slides/python-net/cs/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/chart/) | Vrací nadřazený graf.<br/>            Pouze pro čtení [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Získá prvek na zadaném indexu.

## Indexér

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### Poznámky

1) Viz souhrn a poznámky pro třídu ChartSeriesGroupCollection a výčet CombinableSeriesTypesGroup enum.
2) Skupina řad obsahuje některé vlastnosti řad, které jsou společné pro 
   každou řadu ve skupině ("series group properties").
   "Series group properties" ve třídě ChartSeriesGroup jsou čtení/zápis.
   Každá z "series group properties" může mít pouze pro čtení projekci ve třídě ChartSeries.

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)