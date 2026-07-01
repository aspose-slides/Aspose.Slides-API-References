---
title: IChartSeriesGroup
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje skupinu sérií.
type: docs
weight: 1930
url: /cs/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup rozhraní

Reprezentuje skupinu sérií.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Umožňuje získat základní rozhraní IChartComponent. Pouze pro čtení [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Určuje, jak jsou hodnoty velikosti bublin zobrazovány v bublinovém grafu. Čtení/zápis [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Určuje měřítkový faktor pro bublinový graf (může být mezi 0 % a 300 % výchozí velikosti). Čtení/zápis Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Určuje velikost otvoru v prstencovém grafu (může být mezi 10 % a 90 % velikosti vykreslovací oblasti). Čtení/zápis Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Získá nebo nastaví úhel první výseče koláčového nebo prstencového grafu ve stupních (ve směru hodinových ručiček od shora, od 0 do 360 stupňů). Čtení/zápis UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Vrací nebo nastaví vzdálenost jako procento šířky značky mezi datovými sériemi ve 3D grafu. Čtení/zápis UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Určuje mezeru mezi shluky sloupců nebo sloupčíků jako procento jejich šířky. Čtení/zápis UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | True pokud graf má čáry sérií. Použito u sloupcových grafů s naskládanými řadami a OfPie grafů. Čtení/zápis Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Určuje formát HiLowLines. HiLowLines se používá s typy grafů HiLowClose, OpenHiLowClose, VolumeHiLowClose a VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Určuje, že každý datový značkovač v sérii má jinou barvu. Čtení/zápis Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Získá prvek na určeném indexu. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Určuje, jak moc se mají sloupce a pruhy překrývat v 2-D grafech, jako procento (od -100 % do 100 %). - -100 %: Maximální mezera (sloupce jsou zcela oddělené). - 0 %: Sloupce jsou umístěny vedle sebe bez překrytí či mezery. - 100 %: Maximální překrytí (sloupce se zcela překrývají). Tato vlastnost je čtení/zápis SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Určuje, jak určit, které datové body jsou ve druhém koláči nebo sloupci v grafu pie-of-pie nebo bar-of-pie. Čtení/zápis [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhém koláči nebo sloupci v grafu pie-of-pie nebo bar-of-pie. Pouze pro čtení [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém koláči nebo sloupci v grafu pie-of-pie nebo bar-of-pie. Používá se spolu s vlastností PieSplitBy. Čtení/zápis Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Určuje, zda jsou řady této skupiny vykresleny na sekundární ose. Pouze pro čtení Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Určuje velikost druhého koláče nebo sloupce v grafu pie-of-pie nebo bar-of-pie jako procento velikosti prvního koláče (může být mezi 5 % a 200 %). Čtení/zápis UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Vrací kolekci sérií grafu pouze pro čtení. Pouze pro čtení [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Vrací typ této skupiny sérií. Pouze pro čtení [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Zajišťuje přístup k horním/dolním pruhům v liniovém nebo akciovém grafu. Pouze pro čtení [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Poznámky

1) Viz souhrnu a poznámky ke třídě ChartSeriesGroupCollection a výčtu CombinableSeriesTypesGroup. 2) Skupina sérií obsahuje některé vlastnosti sérií, které jsou společné pro každou sérii ve skupině („vlastnosti skupiny sérií“). „Vlastnosti skupiny sérií“ ve třídě ChartSeriesGroup jsou čtení/zápis. Každá z „vlastností skupiny sérií“ může mít pouze pro čtení projekci ve třídě ChartSeries.

### Viz také

* rozhraní [IChartComponent](../ichartcomponent)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->