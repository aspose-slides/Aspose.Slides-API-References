---
title: ChartSeriesGroup
second_title: Aspose.Sildes .NET API hivatkozás
description: A sorozatok csoportját reprezentálja.
type: docs
weight: 1440
url: /hu/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup osztály

A sorozatok csoportját reprezentálja.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Meghatározza, hogyan jelennek meg a buborékméret értékek a buborékdiagramon. Olvasás/írás [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Meghatározza a skálázási tényezőt a buborékdiagramhoz (0 és az alapméret 300 százaléka között lehet). Olvasás/írás Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Visszaadja a szülő diagramot. Csak olvasható [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Meghatározza a lyuk méretét a fánk diagramon (0 és a rajzterület méretének 90 százaléka között lehet). Olvasás/írás Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Lekérdezi vagy beállítja az első kör vagy fánk diagram szeletének szögét fokban (az órától jobbra, 0-tól 360 fokig). Olvasás/írás UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Visszaadja vagy beállítja a távolságot a jelölő szélességének százalékában a 3D diagram adatcsorozatai között. Olvasás/írás UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Meghatározza az oszlop- vagy sávcsoportok közti távolságot a sáv vagy oszlop szélességének százalékában. Olvasás/írás UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Igaz, ha a diagram rendelkezik sorozatsorokkal. Alkalmazva a rétegezett sáv- és OfPie diagramokra. Olvasás/írás Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Meghatározza a HiLowLines formátumot. A HiLowLines a HiLowClose, OpenHiLowClose, VolumeHiLowClose és a VolumeOpenHiLowClose diagramtípusokkal alkalmazható. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Meghatározza, hogy a sorozat minden adatjelölője más színű legyen. Olvasás/írás Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Lekérdezi a megadott indexű elemet. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Meghatározza, hogy a sávok és oszlopok mekkora mértékben fedjék egymást 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). --100 %: Maximális távolság (a sávok teljesen elválasztva vannak). - 0 %: A sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül. - 100 %: Maximális átfedés (a sávok teljesen egymást fedik). Ez a tulajdonság olvasás/írás SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Meghatározza, hogyan határozzák meg, mely adatpontok szerepelnek a második kör vagy sáv a pie-of-pie vagy bar-of-pie diagramon. Olvasás/írás [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Az egyéni felosztási információ egy egyéni felosztású pie-of-pie vagy bar-of-pie diagramhoz. Az adatpontokat tartalmazza, amelyek a második körben vagy sávban jelennek meg a pie-of-pie vagy bar-of-pie diagramon. Csak olvasható [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Megad egy értéket, amely a második körben vagy sávban lévő adatpontok meghatározásához használatos a pie-of-pie vagy bar-of-pie diagramon. A PieSplitBy tulajdonsággal együtt használatos. Olvasás/írás Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Jelzi, hogy a csoport sorozatai másodlagos tengelyen vannak-e ábrázolva. Csak olvasható Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Meghatározza a pie-of-pie vagy bar-of-pie diagram második körének vagy sávjának méretét az első kör méretének százalékában (5-tól 200 %-ig). Olvasás/írás UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Visszaad egy sorozatgyűjteményt. Csak olvasható [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Visszaadja ennek a sorozatcsoportnak a típusát. Csak olvasható [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Hozzáférést biztosít a vonal- vagy részvény-diagram fel/lef sávjaihoz. Csak olvasható [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Megjegyzések

1) Lásd a ChartSeriesGroupCollection osztály és a CombinableSeriesTypesGroup enumeráció összefoglalóját és megjegyzéseit.  
2) A sorozatok csoportja néhány, a csoport minden sorozatára közös sorozat-tulajdonságot tartalmaz („series group properties”). A „Series group properties” a ChartSeriesGroup osztályban olvasás/írás. Minden egyes „series group properties” csak olvasható projekcióval rendelkezhet a ChartSeries osztályban.

### Lásd még

* interfész [IChartSeriesGroup](../ichartseriesgroup)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->