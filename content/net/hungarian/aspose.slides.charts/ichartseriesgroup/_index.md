---
title: IChartSeriesGroup
second_title: Aspose.Sildes .NET API referencia
description: A sorozatok csoportját képviseli.
type: docs
weight: 1950
url: /hu/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup interfész

Képviseli a sorozatok csoportját.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Lehetővé teszi az alap IChartComponent interfész lekérését. Csak olvasható [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Megadja, hogyan jelennek meg a buborékméret értékek a buborékdiagramon. Olvasás/írás [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Megadja a buborékdiagram méretezési tényezőjét (0 és az alapméret 300 százaléka között lehet). Olvasás/írás Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Megadja a fánkdiagram lyukának méretét (a diagramterület méretének 10 és 90 százaléka között lehet). Olvasás/írás Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Megkapja vagy beállítja az első torta vagy fánkdiagram szeletének szögét fokban (óra járásával felfelé, 0-tól 360 fokig). Olvasás/írás UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Megadja vagy beállítja a távolságot a jelölő szélességének százalékában, az adat sorozatok között egy 3D diagramon. Olvasás/írás UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Megadja az oszlopcsoportok közti távolságot az oszlop vagy oszlop szélességének százalékában. Olvasás/írás UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Igaz, ha a diagram rendelkezik sorozatvonalakkal. Alkalmazott halmozott oszlop és OfPie diagramoknál. Olvasás/írás Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Megadja a HiLowLines formátumot. A HiLowLines a HiLowClose, OpenHiLowClose, VolumeHiLowClose és VolumeOpenHiLowClose diagramtípusokkal együtt alkalmazható. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Megadja, hogy a sorozat minden adatjelzője különböző színű legyen. Olvasás/írás Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Megkapja a megadott indexű elemet. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Megadja, hogy a sávok és oszlopok mennyire fedjék egymást 2-D diagramokon, százalékban (-100-tól 100-ig). -100%: Legnagyobb távolság (a sávok teljesen el vannak választva). 0%: A sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül. 100%: Legnagyobb átfedés (a sávok teljesen átfedik egymást). Ez a tulajdonság Olvasás/írás SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Megadja, hogyan határozzuk meg, mely adatpontok vannak a második tortán vagy oszlopon egy pie-of-pie vagy bar-of-pie diagramon. Olvasás/írás [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Az egyéni felosztási információ egy egyéni felosztással rendelkező pie-of-pie vagy bar-of-pie diagramhoz. Azokat az adatpontokat tartalmazza, melyeket a második tortán vagy oszlopon kell megjeleníteni. Csak olvasható [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Megad egy értéket, amelyet a második tortán vagy oszlopon lévő adatpontok meghatározásához használnak egy pie-of-pie vagy bar-of-pie diagramon. A PieSplitBy tulajdonsággal együtt használatos. Olvasás/írás Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Jelzi, hogy a csoport sorozatai másodlagos tengelyen vannak-e ábrázolva. Csak olvasható Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Megadja a második torta vagy oszlop méretét egy pie-of-pie vagy bar-of-pie diagramon, az első torta méretének százalékában (5-tól 200-ig százalék). Olvasás/írás UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Visszaad egy csak olvasható diagram sorozatgyűjteményt. Csak olvasható [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Visszaad ennek a sorozatcsoportnak a típusát. Csak olvasható [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Elérést biztosít a vonal- vagy részvény-diagram fel/le oszlopaihoz. Csak olvasható [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Megjegyzések

1) Lásd a ChartSeriesGroupCollection osztály és a CombinableSeriesTypesGroup enum összefoglalóját és megjegyzéseit. 2) A sorozatok csoportja néhány sorozati tulajdonságot tartalmaz, amelyek közösek minden sorozatra a csoportban („sorozatcsoport tulajdonságok”). A „sorozatcsoport tulajdonságok” a ChartSeriesGroup osztályban olvasás/írás. Minden egyes „sorozatcsoport tulajdonság” rendelkezik egy csak olvasható vetítéssel a ChartSeries osztályban.

### Lásd még

* interfész [IChartComponent](../ichartcomponent)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->