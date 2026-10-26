---
title: ChartSeriesGroup
second_title: Aspose.Sildes .NET API hivatkozás
description: A sorozatok csoportját képviseli.
type: docs
weight: 1460
url: /hu/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup osztály

A sorozatok csoportját képviseli.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Megadja, hogy a buborékméret értékek hogyan jelennek meg a buborékdiagramon. Olvasás/írás [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Megadja a méretarányt a buborékdiagramhoz (0 és az alapméret 300 százaléka között lehet). Olvasás/írás Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Visszaadja a szülődiagramot. Csak olvasható [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Megadja a lyuk méretét egy fánkdiagramban (0 és a diagramterület méretének 90 százaléka között lehet). Olvasás/írás Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Lekéri vagy beállítja az első kör vagy fánkdiagram szeletének szögét fokban (az óramutató járásával megegyező irányban fentről, 0-tól 360 fokig). Olvasás/írás UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Visszaadja vagy beállítja a távolságot, a jelölő szélességének százalékában, az adat-sorozatok között egy 3D-diagramon. Olvasás/írás UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Megadja a sáv- vagy oszlopcsoportok közötti helyet, a sáv vagy oszlop szélességének százalékában. Olvasás/írás UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Igaz, ha a diagramnak sorozatsorai vannak. Alkalmazva a halmozott sáv- és OfPie diagramokra. Olvasás/írás Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Megadja a HiLowLines formátumot. A HiLowLines a HiLowClose, OpenHiLowClose, VolumeHiLowClose és VolumeOpenHiLowClose diagramtípusokkal együtt alkalmazható. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Megadja, hogy a sorozat minden adatjelölője különböző színű legyen. Olvasás/írás Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Lekéri a megadott indexű elemet. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Megadja, hogy a sávok és oszlopok milyen mértékben fedjék egymást 2-D diagramokon, százalékban (-100%-tól 100%-ig). -100%: Maximális távolság (a sávok teljesen el vannak választva). 0%: A sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül. 100%: Maximális átfedés (a sávok teljesen egymásra fedik). Ez a tulajdonság Olvasás/írás SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Megadja, hogyan határozzuk meg, mely adatpontok vannak a második körön vagy sávon egy pie-of-pie vagy bar-of-pie diagramon. Olvasás/írás [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Az egyéni felosztási információ egy egyéni felosztású pie-of-pie vagy bar-of-pie diagramhoz. Tartalmazza az adatpontokat, amelyeket a második körben vagy sávban kell megjeleníteni egy pie-of-pie vagy bar-of-pie diagramon. Csak olvasható [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Megad egy értéket, amelyet a második körön vagy sávon az adatpontok meghatározásához használnak egy pie-of-pie vagy bar-of-pie diagramon. A PieSplitBy tulajdonsággal együtt használatos. Olvasás/írás Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Jelzi, hogy a csoport sorozata másodlagos tengelyen van-e ábrázolva. Csak olvasható Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagramon, az első kör méretének százalékában (5-tól 200%-ig). Olvasás/írás UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Visszaad egy sorozatgyűjteményt. Csak olvasható [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Visszaadja ennek a sorozatcsoportnak a típusát. Csak olvasható [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Hozzáférést biztosít a vonal- vagy részvény-diagram fel- és le-sávjaihoz. Csak olvasható [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Megjegyzések

1) Lásd a ChartSeriesGroupCollection osztály és a CombinableSeriesTypesGroup enum összefoglalóját és megjegyzéseit. 2) A sorozatcsoport tartalmaz néhány sorozattulajdonságot, amely közös minden sorozatra a csoportban ("sorozatcsoport tulajdonságok"). A "sorozatcsoport tulajdonságok" a ChartSeriesGroup osztályban Olvasás/írás. Minden egyes "sorozatcsoport tulajdonság" rendelkezhet egy csak-olvasható vetítéssel a ChartSeries osztályban.

### Lásd még

* interfész [IChartSeriesGroup](../ichartseriesgroup)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->