---
title: IChartSeriesGroup
second_title: Aspose.Sildes .NET API hivatkozás
description: Sorozatcsoportot reprezentál.
type: docs
weight: 1970
url: /hu/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup interfész

Represents group of series.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Lehetővé teszi a bázis IChartComponent interfész lekérését. Csak olvasható [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Meghatározza, hogyan jelennek meg a buborékméret értékek a buborékdiagramon. Olvasás/írás [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Meghatározza a skalázási tényezőt a buborékdiagramhoz (0 és az alapértelmezett méret 300 százaléka között). Olvasás/írás Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Meghatározza a lyuk méretét a fánkdiagramon (10 és 90 százalék között a diagramterület méretéhez képest). Olvasás/írás Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Lekéri vagy beállítja az első kör vagy fánkdiagram szeletének szögét fokban (az óramutató járásával megegyező irányban fentről, 0-tól 360 fokig). Olvasás/írás UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Lekéri vagy beállítja az adatcsoportok közötti távolságot egy 3D diagramon, a jelölő szélességének százalékában. Az értéknek 0 és 500 között kell lennie. Olvasás/írás UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Lekéri vagy beállítja az oszlop vagy sávcsoportok közötti hézagot, az oszlop vagy sáv szélességének százalékában. Az értéknek 0 és 500 között kell lennie. Olvasás/írás UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Igaz, ha a diagramnak sorvonalai vannak. Alkalmazva a halmozott sáv és OfPie diagramokra. Olvasás/írás Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Meghatározza a HiLowLines formátumot. A HiLowLines a HiLowClose, OpenHiLowClose, VolumeHiLowClose és VolumeOpenHiLowClose diagramtípusokkal alkalmazható. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Meghatározza, hogy a sorozat minden adatjelölője más színű legyen. Olvasás/írás Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Lekéri a megadott indexű elemet. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Meghatározza, hogy a sávok és oszlopok mennyire fedjék át egymást 2-D diagramokon, százalékban (-100 % és 100 % között). - -100 %: maximális távolság (a sávok teljesen el vannak választva). - 0 %: a sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül. - 100 %: maximális átfedés (a sávok teljesen egymásra fedik). Ez a tulajdonság olvasás/írás SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Meghatározza, hogyan határozzuk meg, mely adatpontok vannak a második körben vagy sávban egy kör-kör vagy sáv-kör diagramon. Olvasás/írás [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Az egyéni felosztási információ egy kör-kör vagy sáv-kör diagramhoz egyedi felosztással. Az adatpontokat tartalmazza, amelyeket a második körben vagy sávban kell megjeleníteni egy kör-kör vagy sáv-kör diagramon. Csak olvasható [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Meghatározza azt az értéket, amelyet a második körben vagy sávban lévő adatpontok meghatározásához használnak egy kör-kör vagy sáv-kör diagramon. A PieSplitBy tulajdonsággal együtt használatos. Olvasás/írás Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Jelzi, hogy a csoport sorozatai másodlagos tengelyen vannak-e ábrázolva. Csak olvasható Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Meghatározza a második kör vagy sáv méretét egy kör-kör vagy sáv-kör diagramon, az első kör méretének százalékában (5 és 200 százalék között). Olvasás/írás UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Visszaad egy csak olvasható gyűjteményt a diagram sorozatairól. Csak olvasható [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Visszaad a sorozatcsoport típusát. Csak olvasható [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Biztosít hozzáférést a vonal- vagy részvény-diagram fel/le sávjaihoz. Csak olvasható [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Megjegyzések

1) Lásd a összefoglalót és a megjegyzéseket a ChartSeriesGroupCollection osztály és a CombinableSeriesTypesGroup enum esetén. 2) A sorozatcsoport tartalmaz néhány sorozat tulajdonságot, amely közös minden sorozatra a csoportban („sorozatcsoport tulajdonságok”). A „sorozatcsoport tulajdonságok” a ChartSeriesGroup osztályban olvasás/írás. Minden egyes „sorozatcsoport tulajdonság” rendelkezhet csak-olvasható vetítéssel a ChartSeries osztályban.

### Lásd még

* interfész [IChartComponent](../ichartcomponent)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->