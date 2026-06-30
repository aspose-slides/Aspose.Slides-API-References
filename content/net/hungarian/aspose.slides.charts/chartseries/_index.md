---
title: ChartSeries
second_title: Aspose.Sildes .NET API-referencia
description: Egy diagram sorozatot képvisel.
type: docs
weight: 1420
url: /hu/aspose.slides.charts/chartseries/
---
## ChartSeries osztály

A chart sorozatot képviseli.

```csharp
public class ChartSeries : IChartSeries
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Meghatározza egy 3-D oszlopdiagram sorozat alakját. Ennek a tulajdonságnak az értékének módosítása automatikusan megváltoztathatja a sorozat Type-át. Olvasás/írás [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Meghatározza, hogy a buborékméret értékek hogyan jelennek meg a buborékdiagramon. Ez a tulajdonság nem csak erre a sorozatra, hanem az összes szülő sorozatcsoport sorozatra is vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Így ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. A ParentSeriesGroup.BubbleSizeRepresentation olvasás/írás tulajdonságot használja az érték módosításához. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Meghatározza a buborékdiagram skálázási tényezőjét (0 és 300 százalék között az alapmérettel szemben). Ez a tulajdonság nem csak erre a sorozatra, hanem az összes szülő sorozatcsoport sorozatra is vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Így ez a tulajdonság csak olvasható. A ParentSeriesGroup tulajdonságot használja a szülő sorozatcsoport eléréséhez. A ParentSeriesGroup.BubbleSizeScale olvasás/írás tulajdonságot használja az érték módosításához. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Visszaadja a szülő chart-et. Csak olvasható [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Visszaadja ennek a sorozatnak az adatpontok gyűjteményét. Csak olvasható [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Meghatározza a lyuk méretét a gyűrűdiagramon (10 és 90 százalék között a rajzterület méretéhez képest). Ez a tulajdonság nem csak erre a sorozatra, hanem az összes szülő sorozatcsoport sorozatra is vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Így ez a tulajdonság csak olvasható. A ParentSeriesGroup tulajdonságot használja a szülő sorozatcsoport eléréséhez. A ParentSeriesGroup.DoughnutHoleSize olvasás/írás tulajdonságot használja az érték módosításához. Csak olvasható Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Képviseli a sorozat X irányú ErrorBar-jait. X irányú ErrorBar-ok elérhetők area, bar, scatter és bubble típusú sorozatokhoz. Más diagramtípusoknál ez a tulajdonság null értéket ad vissza (beleértve a 3D diagramokat). Egyéni értékek esetén használja a DataPoints gyűjteményt az érték megadásához ([`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) tulajdonsággal). Csak olvasható [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Képviseli a sorozat Y irányú ErrorBar-jait. Y irányú ErrorBar-ok elérhetők area, bar, line, scatter és bubble típusú sorozatokhoz. Más diagramtípusoknál ez a tulajdonság null értéket ad vissza (beleértve a 3D diagramokat). Egyéni értékek esetén használja a DataPoints gyűjteményt az érték megadásához ([`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) tulajdonsággal). Csak olvasható [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | A nyitott szelet középponttól mért távolságot a szelet átmérőjének százalékában fejezi ki. Olvasás/írás Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Meghatározza az első pie vagy doughnut diagram szeletének szögét fokban (az órának megfelelően felfelé, 0-tól 360 fokig). Ez a tulajdonság nem csak erre a sorozatra, hanem az összes szülő sorozatcsoport sorozatra is vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Így ez a tulajdonság csak olvasható. A ParentSeriesGroup tulajdonságot használja a szülő sorozatcsoport eléréséhez. A ParentSeriesGroup.FirstSliceAngle olvasás/írás tulajdonságot használja az érték módosításához. Csak olvasható UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Visszaadja egy sorozat formátumát. Csak olvasható [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Visszaadja vagy beállítja a távolságot, a marker szélességének százalékában, a 3D diagram adat sorozatai között. Ez a tulajdonság nem csak erre a sorozatra, hanem az összes szülő sorozatcsoport sorozatra is vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Így ez a tulajdonság csak olvasható. A ParentSeriesGroup tulajdonságot használja a szülő sorozatcsoport eléréséhez. A ParentSeriesGroup.GapDepth olvasás/írás tulajdonságot használja az érték módosításához. Csak olvasható Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Meghatározza az oszlop vagy oszlopcsoport közti helyet, a bar vagy column szélességének százalékában. Ez a tulajdonság nem csak erre a sorozatra, hanem az összes szülő sorozatcsoport sorozatra is vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Így ez a tulajdonság csak olvasható. A ParentSeriesGroup tulajdonságot használja a szülő sorozatcsoport eléréséhez. A ParentSeriesGroup.GapWidth olvasás/írás tulajdonságot használja az érték módosításához. Csak olvasható Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Meghatározza, hogy vannak-e sorozati vonalak ehhez a sorozathoz és kapcsolódó sorozatokhoz. Ez a tulajdonság nem csak erre a sorozatra, hanem az összes szülő sorozatcsoport sorozatra is vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Így ez a tulajdonság csak olvasható. A ParentSeriesGroup tulajdonságot használja a szülő sorozatcsoport eléréséhez. A ParentSeriesGroup.HasSeriesLines olvasás/írás tulajdonságot használja az érték módosításához. A ParentSeriesGroup.SeriesLinesFormat tulajdonságot használja a sorozati vonalak formázásához. Csak olvasható Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Meghatározza, hogy a Line- vagy Stock-diagram rendelkezik-e fel/lef bárakkal. Ez a tulajdonság nem csak erre a sorozatra, hanem az összes szülő sorozatcsoport sorozatra is vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Így ez a tulajdonság csak olvasható. A ParentSeriesGroup tulajdonságot használja a szülő sorozatcsoport eléréséhez. A ParentSeriesGroup.UpDownBars.HasUpDownBars olvasás/írás tulajdonságot használja az érték módosításához. A ParentSeriesGroup.UpDownBars tulajdonságot használja a fel/lef bárak formázásához. Csak olvasható Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Meghatározza a sorozat invertált szilárd színét. A színbeállítás alkalmazásához állítsa a sorozat formátum FillType-át FillType.Solid-ra. Olvasás/írás [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Meghatározza, hogy a bar, column vagy bubble sorozat inverz színeket alkalmazzon, ha az érték negatív. Olvasás/írás Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Meghatározza, hogy a sorozat minden adatmarkere különböző színű legyen. Ez a tulajdonság nem csak erre a sorozatra, hanem az összes szülő sorozatcsoport sorozatra is vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Így ez a tulajdonság csak olvasható. A ParentSeriesGroup tulajdonságot használja a szülő sorozatcsoport eléréséhez. A ParentSeriesGroup.IsColorVaried olvasás/írás tulajdonságot használja az érték módosításához. Csak olvasható Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Visszaadja egy sorozat Címkéit. Csak olvasható [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Marker. Csak olvasható [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Visszaadja a sorozat nevét. Csak olvasható [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Olvasás/írás String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Olvasás/írás String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Olvasás/írás String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Olvasás/írás String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Visszaadja egy sorozat sorrendjét. Olvasás/írás Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Meghatározza, hogy a sávok és oszlopok mennyire átfedik egymást 2-D diagramokon, százalékban (%-ban) (-100%-tól 100%-ig). Ez a tulajdonság nem csak erre a sorozatra, hanem az összes szülő sorozatcsoport sorozatra is vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Így ez a tulajdonság csak olvasható. Az érték módosításához használja a !:ParentSeriesGroup.Overlap olvasás/írás tulajdonságot. Csak olvasható SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Képviseli a szülő kategória címkék elrendezését. Csak Treemap diagramokra alkalmazható. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Csak olvasható [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Meghatározza, hogy hogyan kell kiválasztani, mely adatpontok jelennek meg a második pie vagy bar részen egy pie-of-pie vagy bar-of-pie diagramon. Ez a tulajdonság nem csak erre a sorozatra, hanem az összes szülő sorozatcsoport sorozatra is vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Így ez a tulajdonság csak olvasható. A ParentSeriesGroup tulajdonságot használja a szülő sorozatcsoport eléréséhez. A ParentSeriesGroup.PieSplitBy olvasás/írás tulajdonságot használja az érték módosításához. Csak olvasható [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Az egyéni felosztási információ egy egyedi felosztással rendelkező pie-of-pie vagy bar-of-pie diagramhoz. Az adatpontokat tartalmazza, amelyeket a második pie vagy bar részben kell megjeleníteni egy pie-of-pie vagy bar-of-pie diagramon. Csak olvasható [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Meghatározza azt az értéket, amelyet a második pie vagy bar részben lévő adatpontok meghatározásához használnak egy pie-of-pie vagy bar-of-pie diagramon. A PieSplitBy tulajdonsággal együtt használatos. Csak olvasható Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Jelzi, hogy ez a sorozat a másodlagos tengelyen jelenik-e meg. Olvasás/írás Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Képviseli a kvartilis módszert. Csak BoxAndWhisker diagramokra alkalmazható. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Képviseli a legend bejegyzést, amely ehhez a sorozathoz kapcsolódik. Csak olvasható [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Meghatározza egy pie-of-pie vagy bar-of-pie diagram második pie vagy bar méretét, az első pie méretének százalékában (5 és 200 százalék között). Ez a tulajdonság nem csak erre a sorozatra, hanem az összes szülő sorozatcsoport sorozatra is vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Így ez a tulajdonság csak olvasható. A ParentSeriesGroup tulajdonságot használja a szülő sorozatcsoport eléréséhez. A ParentSeriesGroup.SecondPieSize olvasás/írás tulajdonságot használja az érték módosításához. Csak olvasható UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Képviseli a csatlakozó vonalakat. Csak Waterfall diagramokra alkalmazható. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Képviseli a belső pontokat. Igaz, ha a belső pontok megjelennek a BoxAndWhisker diagramon. Csak BoxAndWhisker diagramokra alkalmazható. Olvasás/írás Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Képviseli az átlagvonalat. Igaz, ha az átlagvonal megjelenik a BoxAndWhisker diagramon. Csak BoxAndWhisker diagramokra alkalmazható. Olvasás/írás Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Képviseli az átlagmarkereket. Igaz, ha az átlagmarkerek megjelennek a BoxAndWhisker diagramon. Csak BoxAndWhisker diagramokra alkalmazható. Olvasás/írás Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Képviseli a kiugró pontokat. Igaz, ha a kiugró pontok megjelennek a BoxAndWhisker diagramon. Csak BoxAndWhisker diagramokra alkalmazható. Olvasás/írás Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Képviseli a görbe simítást. Igaz, ha a görbe simítás be van kapcsolva vonallal összekötött vonaldiagram vagy szórásdiagram esetén. Csak vonal és szórás, vonallal összekötött diagramokra alkalmazható. Olvasás/írás Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | A sorozat trendvonalak gyűjteménye. Csak olvasható [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Visszaadja ennek a sorozatnak a típusát. Olvasás/írás [`ChartType`](../charttype). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Visszaad egy automatikus színt a sorozathoz a sorozat indexe és a diagram stílusa alapján. Ez a szín alapértelmezés szerint használatos, ha a FillType egyenlő NotDefined értékkel. |

### Lásd még

* interfész [IChartSeries](../ichartseries)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->