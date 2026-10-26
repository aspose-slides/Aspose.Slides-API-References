---
title: ChartSeriesGroup class
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup osztály

Representálja a sorozatok csoportját.

A ChartSeriesGroup típus a következő tagokat tartalmazza:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`type`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/type/) | Visszaadja ennek a sorozatcsoportnak a típusát.<br/>            Csak olvasható [`CombinableSeriesTypesGroup`](/slides/python-net/hu/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Jelzi, hogy a csoport sorozatai másodlagos tengelyen vannak-e ábrázolva.<br/>            Csak olvasható **bool**. |
| [`series`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/series/) | Visszaad egy sorozatok gyűjteményét.<br/>            Csak olvasható [`IChartSeriesReadonlyCollection`](/slides/python-net/hu/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Hozzáférést biztosít a vonal- vagy részvény-diagram fel-/alsó sávjaihoz.<br/>            Csak olvasható [`IUpDownBarsManager`](/slides/python-net/hu/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/gap_width/) | Megadja a sáv- vagy oszlopcsoportok közötti távolságot a sáv vagy oszlop szélességének százalékában.<br/>            Olvasás/írás **int**. |
| [`gap_depth`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/gap_depth/) | Visszaadja vagy beállítja a távolságot, a jelölő szélességének százalékában, az adat sorozatok között egy 3D diagramon.<br/>            Olvasás/írás **int**. |
| [`first_slice_angle`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Megkapja vagy beállítja az első kör vagy fánk diagram szeletének szögét,<br/>            fokban (az óramutató járásával megegyező irányban fentről, 0 és 360 fok között).<br/>            Olvasás/írás **int**. |
| [`doughnut_hole_size`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Megadja a lyuk méretét egy fánk diagramon (a diagramterület méretének 0 és 90 százaléka között).<br/>            Olvasás/írás **int**. |
| [`overlap`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/overlap/) | Megadja, hogy a sávok és oszlopok mennyire fedik egymást 2-D diagramokon, százalékban (-100% és 100% között).<br/>             - -100%: Maximális távolság (a sávok teljesen el vannak választva).<br/>             - 0%: A sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül.<br/>             - 100%: Maximális átfedés (a sávok teljesen egymásra fednek).<br/>             Ez a tulajdonság olvasás/írás **int**. |
| [`second_pie_size`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Megadja a második kör vagy sáv méretét egy kör-kör vagy sáv-kör diagramon, az első kör méretének százalékában (5 és 200 százalék között).<br/>            Olvasás/írás **int**. |
| [`bubble_size_representation`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Megadja, hogy a buborékméret értékek hogyan jelennek meg a buborékkördiagramon.<br/>            Olvasás/írás [`BubbleSizeRepresentationType`](/slides/python-net/hu/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Megad egy értéket, amely a második kör vagy sáv meghatározásához használható egy kör-kör vagy sáv-kör diagramon.<br/>            A PieSplitBy tulajdonsággal együtt használatos.<br/>            Olvasás/írás **float**. |
| [`pie_split_by`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Megadja, hogy hogyan határozzák meg, mely adatpontok kerülnek a második körbe vagy sávba egy kör-kör vagy sáv-kör diagramon.<br/>            Olvasás/írás [`PieSplitType`](/slides/python-net/hu/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Megadja, hogy a sorozat minden adatjelzője különböző színű legyen.<br/>            Olvasás/írás **bool**. |
| [`has_series_lines`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Igaz, ha a diagramnak sorozatsorai vannak. Alkalmazva halmozott oszlop és OfPie diagramokra.<br/>            Olvasás/írás **bool**. |
| [`hi_low_lines_format`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Megadja a HiLowLines formátumot.<br/>            A HiLowLines a HiLowClose, OpenHiLowClose, VolumeHiLowClose és VolumeOpenHiLowClose diagramtípusokkal alkalmazható. |
| [`bubble_size_scale`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Megadja a skálázási tényezőt a buborékkördiagramhoz (0 és az alapméret 300 százaléka között).<br/>            Olvasás/írás **int**. |
| [`pie_split_custom_points`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Az egyedi felosztási információk egy egyéni felosztással rendelkező kör-kör vagy sáv-kör diagramhoz.<br/>            Olyan adatpontokat tartalmaz, amelyeket a második körben vagy sávban kell megjeleníteni egy kör-kör vagy sáv-kör diagramon.<br/>            Csak olvasható [`PieSplitCustomPointCollection`](/slides/python-net/hu/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/chart/) | Visszaadja a szülő diagramot.<br/>            Csak olvasható [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Lekéri a megadott indexű elemet.

## Indexelő

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### Megjegyzések

1) Lásd a Summary és Remarks szakaszt a ChartSeriesGroupCollection osztály és a CombinableSeriesTypesGroup enum számára.  
2) A sorozatok csoportja tartalmaz néhány sorozati tulajdonságot, amely közös minden sorozatra a csoportban („series group properties”).  
„Series group properties” a ChartSeriesGroup osztályban olvasás/írás.  
Az „series group properties” egy olvasható (read-only) projekcióval is rendelkezhet a ChartSeries osztályban.

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)