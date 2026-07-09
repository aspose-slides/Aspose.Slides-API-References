---
title: ChartSeriesGroup
second_title: Aspose.Sildes pro .NET – referenční dokumentace API
description: Představuje skupinu řad.
type: docs
weight: 1460
url: /cs/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup třída

Představuje skupinu řad.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Určuje, jak jsou hodnoty velikosti bublin reprezentovány v bublinovém grafu. Read/write [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Určuje měřítko pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). Read/write Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Vrací nadřazený graf. Read-only [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Určuje velikost díry v prstencovém grafu (může být mezi 0 a 90 procenty velikosti vykreslovací oblasti). Read/write Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Získá nebo nastaví úhel první výsečky koláčového nebo prstencového grafu ve stupních (ve směru hodinových ručiček od shora, od 0 do 360 stupňů). Read/write UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Vrací nebo nastaví vzdálenost jako procento šířky značky mezi datovými řadami ve 3D grafu. Read/write UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Určuje mezeru mezi shluky sloupců nebo pruhů jako procento jejich šířky. Read/write UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True pokud graf obsahuje čáry řad. Používá se u skládaných sloupcových a OfPie grafů. Read/write Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Určuje formát HiLowLines. HiLowLines se používá u typů grafů HiLowClose, OpenHiLowClose, VolumeHiLowClose a VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Určuje, že každý datový značkovač v řadě má jinou barvu. Read/write Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Získá prvek na zadaném indexu. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Určuje, jak moc se mají pruhy a sloupce překrývat v 2-D grafech, jako procento (od -100 % do 100 %). -100 %: Maximální mezera (pruhy jsou zcela oddělené). 0 %: Pruhy jsou umístěny vedle sebe bez překrytí nebo mezery. 100 %: Maximální překrytí (pruhy se zcela překrývají). This property is read/write SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Určuje, jak určit, které datové body jsou ve druhém výseku nebo sloupci v grafu pie-of-pie nebo bar-of-pie. Read/write [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhém výseku nebo sloupci v grafu pie-of-pie nebo bar-of-pie. Read-only [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém výseku nebo sloupci v grafu pie-of-pie nebo bar-of-pie. Používá se společně s vlastností PieSplitBy. Read/write Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Indikuje, zda jsou řady této skupiny vykresleny na sekundární ose. Read-only Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Určuje velikost druhého výseku nebo sloupce v grafu pie-of-pie nebo bar-of-pie jako procento velikosti prvního výseku (může být mezi 5 a 200 procenty). Read/write UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Vrací kolekci řad. Read-only [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Vrací typ této skupiny řad. Read-only [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Poskytuje přístup k up/down pruhům v grafu Line nebo Stock. Read-only [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Poznámky

1) Viz souhrn a poznámky ke třídě ChartSeriesGroupCollection a výčtu CombinableSeriesTypesGroup. 2) Skupina řad obsahuje některé vlastnosti řad, které jsou společné pro každou řadu ve skupině („vlastnosti skupiny řad“). „Vlastnosti skupiny řad“ v třídě ChartSeriesGroup jsou read/write. Každá z „vlastností skupiny řad“ může mít read-only projekci ve třídě ChartSeries.

### Viz také

* rozhraní [IChartSeriesGroup](../ichartseriesgroup)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->