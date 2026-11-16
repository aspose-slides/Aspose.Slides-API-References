---
title: ChartSeriesGroup
second_title: Aspose.Sildes .NET API Referenciája
description: Sorozatcsoportot képviseli.
type: docs
weight: 1470
url: /hu/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup osztály

A sorozatcsoportot képviseli.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Megadja, hogy a buborék méretértékek hogyan jelennek meg a buborékdiagramon. Olvasás/írás [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Megadja a skálafaktort a buborékdiagramhoz (0 és 300 százalék között az alapmérettől). Olvasás/írás Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Visszaadja a szülő diagramot. Csak olvasható [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Megadja a lyuk méretét egy fánk diagramban (0 és 90 százalék között a rajzterület méretéhez képest). Olvasás/írás Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Megkapja vagy beállítja az első torta vagy fánk szelet szögét fokban (óra járásával megegyezően fentről, 0-tól 360 fokig). Olvasás/írás UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Megkapja vagy beállítja a 3D diagram adatsorai közti távolságot a jelölő szélességének százalékában. Az értéknek 0 és 500 között kell lennie. Olvasás/írás UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Megkapja vagy beállítja az oszlop- vagy sávcsoportok közti távolságot az oszlop vagy sáv szélességének százalékában. Az értéknek 0 és 500 között kell lennie. Olvasás/írás UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Igaz, ha a diagramnak sorozatvonalai vannak. Alkalmazható halmozott sáv- és OfPie diagramokra. Olvasás/írás Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Megadja a HiLowLines formátumát. A HiLowLines a HiLowClose, OpenHiLowClose, VolumeHiLowClose és VolumeOpenHiLowClose diagramtípusokkal együtt használható. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Megadja, hogy a sorozat minden adatjelzője különböző színű legyen. Olvasás/írás Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Lekéri a megadott indexű elemet. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Megadja, hogy a 2-D diagramokon a sávok és oszlopok milyen mértékben fedjék át egymást, százalékban (-100 % és 100 % között). -100 %: maximális távolság (a sávok teljesen szétválasztva). 0 %: a sávok mellékesen helyezkednek el átfedés vagy távolság nélkül. 100 %: maximális átfedés (a sávok teljesen egymásra fedik). Ez a tulajdonság olvasás/írás SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Megadja, hogyan határozzuk meg, mely adatpontok vannak a második tortán vagy sávon egy pie-of-pie vagy bar-of-pie diagramon. Olvasás/írás [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | A saját felosztási információ egy pie-of-pie vagy bar-of-pie diagramhoz saját felosztással. Azokat az adatpontokat tartalmazza, amelyeket a második tortán vagy sávon kell megjeleníteni. Csak olvasható [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Megadja azt az értéket, amely a második torta vagy sáv adatpontjainak meghatározására szolgál egy pie-of-pie vagy bar-of-pie diagramon. A PieSplitBy tulajdonsággal együtt használatos. Olvasás/írás Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Jelzi, hogy a csoport sorozata a másodlagos tengelyen van-e ábrázolva. Csak olvasható Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Megadja a második torta vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagramon, az első torta méretének százalékában (5-200 % között). Olvasás/írás UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Visszaad egy sorozatgyűjteményt. Csak olvasható [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Visszaadja ennek a sorozatcsoportnak a típusát. Csak olvasható [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Biztosít hozzáférést a vonal- vagy részvény-diagram fel- és le-sávjaihoz. Csak olvasható [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Megjegyzések

1) Lásd a ChartSeriesGroupCollection osztály és a CombinableSeriesTypesGroup felsoroló típus összefoglalóját és megjegyzéseit.  
2) A sorozatcsoport tartalmaz néhány sorozat tulajdonságot, amely közös a csoport minden sorozatára („sorozatcsoport-tulajdonságok”). A „sorozatcsoport-tulajdonságok” a ChartSeriesGroup osztályban olvasás/írás. Minden „sorozatcsoport-tulajdonság” rendelkezhet csak olvasható leképezéssel a ChartSeries osztályban.

### Lásd még

* interfész [IChartSeriesGroup](../ichartseriesgroup)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->