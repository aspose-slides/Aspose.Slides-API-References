---
title: IChartSeriesGroup
second_title: Aspose.Sildes pro .NET API Reference
description: Představuje skupinu řad.
type: docs
weight: 1970
url: /cs/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup rozhraní

Represents group of series.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Umožňuje získat základní rozhraní IChartComponent. Pouze ke čtení [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Určuje, jak jsou hodnoty velikosti bublin zobrazeny v bublinovém grafu. Čtení/zápis [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Určuje měřítko pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). Čtení/zápis Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Určuje velikost díry v prstencovém grafu (může být mezi 10 a 90 procenty velikosti vykreslovací oblasti). Čtení/zápis Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Získá nebo nastaví úhel první výsečky koláčového nebo prstencového grafu ve stupních (ve směru hodinových ručiček od horní pozice, od 0 do 360 stupňů). Čtení/zápis UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Získá nebo nastaví vzdálenost mezi datovými řadami ve 3D grafu jako procento šířky značky. Hodnota musí být mezi 0 a 500. Čtení/zápis UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Získá nebo nastaví prostor mezi shluky sloupců nebo pruhů jako procento šířky sloupce nebo pruhu. Hodnota musí být mezi 0 a 500. Čtení/zápis UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | True, pokud graf obsahuje řádky řad. Použito u sloupcových grafů s kumulací a grafů OfPie. Čtení/zápis Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Určuje formát HiLowLines. HiLowLines se používá s typy grafů HiLowClose, OpenHiLowClose, VolumeHiLowClose a VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Určuje, že každý datový značkovač v řadě má jinou barvu. Čtení/zápis Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Získá prvek na zadaném indexu. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Určuje, jak moc se mají sloupce a pruhy překrývat v 2-D grafech, jako procento (od -100 % do 100 %). - -100 %: Maximální mezera (sloupce jsou zcela oddělené). - 0 %: Sloupce jsou umístěny vedle sebe bez překrytí nebo mezery. - 100 %: Maximální překrytí (sloupce se zcela překrývají). Tato vlastnost je čtení/zápis SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Určuje, jak určit, které datové body jsou ve druhém výsečce nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Čtení/zápis [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhém výsečce nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Pouze ke čtení [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém výsečce nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Používá se spolu s vlastností PieSplitBy. Čtení/zápis Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Určuje, zda jsou řady této skupiny vykresleny na sekundární ose. Pouze ke čtení Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Určuje velikost druhého výsečku nebo pruhu v grafu pie-of-pie nebo bar-of-pie jako procento velikosti prvního výsečku (může být mezi 5 a 200 procenty). Čtení/zápis UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Vrací pouze pro čtení kolekci řad grafu. Pouze ke čtení [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Vrací typ této skupiny řad. Pouze ke čtení [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Poskytuje přístup k horním/dolním pruhům v grafu Line nebo Stock. Pouze ke čtení [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Poznámky

1) Viz souhrn a poznámky ke třídě ChartSeriesGroupCollection a výčtu CombinableSeriesTypesGroup. 2) Skupina řad obsahuje některé vlastnosti řad, které jsou společné pro každou řadu ve skupině („vlastnosti skupiny řad“). „Vlastnosti skupiny řad“ ve třídě ChartSeriesGroup jsou čtení/zápis. Každá z „vlastností skupiny řad“ může mít pouze-ke-čtení projekci ve třídě ChartSeries.

### Další informace

* rozhraní [IChartComponent](../ichartcomponent)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->