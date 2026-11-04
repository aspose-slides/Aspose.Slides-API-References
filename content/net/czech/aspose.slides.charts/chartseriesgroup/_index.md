---
title: ChartSeriesGroup
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje skupinu řad.
type: docs
weight: 1470
url: /cs/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup třída

Represents group of series.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Určuje, jak jsou hodnoty velikosti bublin reprezentovány v bublinovém grafu. Čtení/zápis [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Určuje měřítkový faktor pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). Čtení/zápis Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Vrací nadřazený graf. Pouze ke čtení [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Určuje velikost díry v prstencovém grafu (může být mezi 0 a 90 procenty velikosti výkresové oblasti). Čtení/zápis Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Získá nebo nastaví úhel první výsečky koláčového nebo prstencového grafu ve stupních (ve směru hodinových ručiček odshora, od 0 do 360 stupňů). Čtení/zápis UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Získá nebo nastaví vzdálenost mezi datovými řadami ve 3D grafu jako procento šířky značky. Hodnota musí být mezi 0 a 500. Čtení/zápis UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Získá nebo nastaví prostor mezi shluky sloupců nebo pruhů jako procento jejich šířky. Hodnota musí být mezi 0 a 500. Čtení/zápis UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True, pokud graf obsahuje čáry řad. Použito u sloupcových grafů s naskládáním a grafů OfPie. Čtení/zápis Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Určuje formát HiLowLines. HiLowLines se používá s typy grafů HiLowClose, OpenHiLowClose, VolumeHiLowClose a VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Určuje, že každý datový marker v řadě má jinou barvu. Čtení/zápis Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Získá prvek na zadaném indexu. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Určuje, jak moc se mají sloupce a pruhy překrývat v 2-D grafech, jako procento (od -100 % do 100 %). - -100 %: Maximální mezera (sloupce jsou zcela odděleny). - 0 %: Sloupce jsou umístěny vedle sebe bez překrytí nebo mezery. - 100 %: Maximální překrytí (sloupce se navzájem zcela překrývají). Tato vlastnost je čtení/zápis SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Určuje, jak určit, které datové body jsou ve druhém koláči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Čtení/zápis [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhém koláči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Pouze ke čtení [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém koláči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Používá se spolu s vlastností PieSplitBy. Čtení/zápis Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Indikuje, zda jsou řady této skupiny vykresleny na sekundární ose. Pouze ke čtení Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Určuje velikost druhého koláče nebo pruhu v grafu pie-of-pie nebo bar-of-pie jako procento velikosti prvního koláče (může být mezi 5 a 200 procenty). Čtení/zápis UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Vrací kolekci řad. Pouze ke čtení [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Vrací typ této skupiny řad. Pouze ke čtení [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Zajišťuje přístup k up/down pruhům v Line- nebo Stock-grafu. Pouze ke čtení [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Poznámky

1) Viz souhrn a poznámky ke třídě ChartSeriesGroupCollection a výčtu CombinableSeriesTypesGroup. 2) Skupina řad obsahuje některé vlastnosti řad, které jsou společné pro každou řadu ve skupině („vlastnosti skupiny řad“). „Vlastnosti skupiny řad“ v třídě ChartSeriesGroup jsou čtení/zápis. Každá z „vlastností skupiny řad“ může mít v třídě ChartSeries pouze-ke-čtení projekci.

### Viz také

* rozhraní [IChartSeriesGroup](../ichartseriesgroup)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestava [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->