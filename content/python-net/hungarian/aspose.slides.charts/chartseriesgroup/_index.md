---
title: ChartSeriesGroup class
second_title: Aspose.Slides a Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup osztály

A sorozatok csoportját képviseli.

A ChartSeriesGroup típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`type`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/type/) | Visszaadja ennek a sorozatcsoportnak a típusát.<br/>            Csak olvasható [`CombinableSeriesTypesGroup`](/slides/python-net/hu/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Jelzi, hogy a csoport sorozatai másodlagos tengelyen vannak-e ábrázolva.<br/>            Csak olvasható **bool**. |
| [`series`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/series/) | Visszaad egy sorozatgyűjteményt.<br/>            Csak olvasható [`IChartSeriesReadonlyCollection`](/slides/python-net/hu/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Hozzáférést biztosít a vonal- vagy részvény-diagram fel-/le-oszlopaihoz.<br/>            Csak olvasható [`IUpDownBarsManager`](/slides/python-net/hu/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/gap_width/) | Beállítja vagy lekéri az oszlop- vagy sávcsoportok közti távolságot, a sáv vagy oszlop szélességének százalékában.<br/>            Az érték 0 és 500 között kell legyen.<br/>            Olvasás-írás **int**. |
| [`gap_depth`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/gap_depth/) | Beállítja vagy lekéri a 3D diagram adat-sorozatai közti távolságot, a jelölő szélességének százalékában.<br/>            Az érték 0 és 500 között kell legyen.<br/>            Olvasás-írás **int**. |
| [`first_slice_angle`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Beállítja vagy lekéri az első kör vagy fánk diagram szeletének szögét, fokban (az óramutató járásával megegyező irányban, 0-tól 360 fokig).<br/>            Olvasás-írás **int**. |
| [`doughnut_hole_size`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Meghatározza a fánk diagram lyukának méretét (a diagramterület méretének 0-tól 90 %-ig).<br/>            Olvasás-írás **int**. |
| [`overlap`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/overlap/) | Meghatározza, hogy a sávok és oszlopok 2-D diagramokon mekkora mértékben fedik egymást, százalékban (-100 %-tól 100 %-ig).<br/>             -100 %: Maximális távolság (a sávok teljesen elkülönülnek).<br/>             0 %: A sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül.<br/>             100 %: Maximális átfedés (a sávok teljesen egymásra fednek).<br/>             Ez a tulajdonság olvasás-írás **int**. |
| [`second_pie_size`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Meghatározza a második kör vagy sáv méretét egy kör-a-kör vagy sáv-a-kör diagramon, az első kör méretének százalékában (5-tól 200 %-ig).<br/>            Olvasás-írás **int**. |
| [`bubble_size_representation`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Meghatározza, hogyan jelennek meg a buborékméret-értékek a buborékdiagramon.<br/>            Olvasás-írás [`BubbleSizeRepresentationType`](/slides/python-net/hu/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Meghatároz egy értéket, amely alapján megállapítható, mely adatpontok vannak a második körben vagy sávban egy kör-a-kör vagy sáv-a-kör diagramon.<br/>            A PieSplitBy tulajdonsággal együtt használatos.<br/>            Olvasás-írás **float**. |
| [`pie_split_by`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Meghatározza, hogyan kell kiválasztani, mely adatpontok vannak a második körben vagy sávban egy kör-a-kör vagy sáv-a-kör diagramon.<br/>            Olvasás-írás [`PieSplitType`](/slides/python-net/hu/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Megadja, hogy a sorozat minden adatjelölője más színű legyen.<br/>            Olvasás-írás **bool**. |
| [`has_series_lines`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Igaz, ha a diagramnak sorozatvonalai vannak. Alkalmazható a halmozott sáv- és OfPie diagramokra.<br/>            Olvasás-írás **bool**. |
| [`hi_low_lines_format`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Meghatározza a HiLowLines formátumát.<br/>            A HiLowLines a HiLowClose, OpenHiLowClose, VolumeHiLowClose és VolumeOpenHiLowClose diagramtípusokkal együtt alkalmazható. |
| [`bubble_size_scale`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Meghatározza a buborékdiagram skálázási tényezőjét (0-tól 300 %-ig az alapértelmezett mérettől).<br/>            Olvasás-írás **int**. |
| [`pie_split_custom_points`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | A saját felosztási információ egy kör-a-kör vagy sáv-a-kör diagramhoz, amely saját felosztást használ.<br/>            Tartalmazza azokat az adatpontokat, amelyeket a második körben vagy sávban kell megjeleníteni.<br/>            Csak olvasható [`PieSplitCustomPointCollection`](/slides/python-net/hu/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/chart/) | Visszaadja a szülő diagramot.<br/>            Csak olvasható [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Lekéri az elemet a megadott indexnél.

## Indexer

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### Megjegyzés

1) Lásd a ChartSeriesGroupCollection osztály és a CombinableSeriesTypesGroup enumeráció összefoglalóját és megjegyzéseit.  
2) A sorozatcsoport néhány olyan sorozat-tulajdonságot tartalmaz, amely közös minden egyes sorozatra a csoportban („sorozatcsoport-tulajdonságok”).  
   A „sorozatcsoport-tulajdonságok” a ChartSeriesGroup osztályban olvasás-írás.  
   Minden „sorozatcsoport-tulajdonságnak” lehet egy csak olvasható vetülete a ChartSeries osztályban.

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)