---
title: IChartSeriesGroup
second_title: Aspose.Sildes .NET API Referenciája
description: A sorozatok csoportját képviseli.
type: docs
weight: 1930
url: /hu/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup interfész

A sorozatok csoportját képviseli.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Lehetővé teszi a alap IChartComponent interfész lekérdezését. Csak olvasható [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Megadja, hogy a buborék diagramon a buborékméret-értékek hogyan jelennek meg. Olvasás/írás [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Megadja a buborék diagram skálázási tényezőjét (0 és az alapméret 300 százaléka között lehet). Olvasás/írás Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Megadja a gyűrűdiagram lyukának méretét (a diagramterület méretének 10 és 90 százaléka között lehet). Olvasás/írás Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Lekérdezi vagy beállítja az első kör vagy gyűrű diagram szeletének szögét fokban (az óramutató járásával megegyező irányban, 0 és 360 fok között). Olvasás/írás UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Lekérdezi vagy beállítja a távolságot, a jelölő szélességének százalékában, az adat sorozatok között egy 3D diagramon. Olvasás/írás UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Megadja az oszlop- vagy sávcsoportok közötti távolságot, az oszlop vagy sáv szélességének százalékában. Olvasás/írás UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Igaz, ha a diagramnak sorozatsora van. Alkalmazva a halmozott sáv és OfPie diagramokra. Olvasás/írás Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Megadja a HiLowLines formátumát. A HiLowLines a HiLowClose, OpenHiLowClose, VolumeHiLowClose és VolumeOpenHiLowClose diagramtípusokkal együtt használható. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Megadja, hogy a sorozat minden adatjelölője különböző színnel rendelkezik. Olvasás/írás Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Lekérdezi a megadott indexű elemet. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Megadja, hogy a sávok és oszlopok mennyire fedhetnek egymást 2-D diagramokon, százalékban (-100%-tól 100%-ig). --100%: Maximális távolság (a sávok teljesen elkülönülnek). -0%: A sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül. -100%: Maximális átfedés (a sávok teljesen átfedik egymást). Ez a tulajdonság Olvasás/írás SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Megadja, hogyan határozható meg, mely adatpontok vannak a második kör vagy sáv egy pie-of-pie vagy bar-of-pie diagramon. Olvasás/írás [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Az egyéni felosztási információ egy egyedi felosztású pie-of-pie vagy bar-of-pie diagramhoz. Azokat az adatpontokat tartalmazza, amelyeket a második kör vagy sáv egy pie-of-pie vagy bar-of-pie diagramon kell megjeleníteni. Csak olvasható [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Megad egy értéket, amely a második kör vagy sáv adatpontjainak meghatározásához használatos egy pie-of-pie vagy bar-of-pie diagramon. A PieSplitBy tulajdonsággal együtt használatos. Olvasás/írás Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Jelzi, hogy a csoport sorozatai másodlagos tengelyen vannak-e ábrázolva. Csak olvasható Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagramon, az első kör méretének százalékában (5 és 200 százalék között lehet). Olvasás/írás UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Visszaad egy csak olvasható gyűjteményt a diagram sorozatairól. Csak olvasható [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Visszaadja ennek a sorozatcsoportnak a típusát. Csak olvasható [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Lehetővé teszi a vonal- vagy árfolyam-diagram fel/le sávjainak elérését. Csak olvasható [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Megjegyzések

1) Lásd a ChartSeriesGroupCollection osztály és a CombinableSeriesTypesGroup enum összefoglalóját és megjegyzéseit. 2) A sorozatok csoportja néhány sorozati tulajdonságot tartalmaz, amelyek minden sorozatra közösek a csoportban („sorozatcsoport tulajdonságok”). A „sorozatcsoport tulajdonságok” a ChartSeriesGroup osztályban olvasás/írás. Minden „sorozatcsoport tulajdonság” csak olvasható projekcióval rendelkezhet a ChartSeries osztályban.

### Lásd még

* interfész [IChartComponent](../ichartcomponent)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->