---
title: ChartSeriesGroup
second_title: Aspose.Sildes pro .NET API Referenci
description: Reprezentuje skupinu sérií.
type: docs
weight: 1440
url: /cs/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup třída

Reprezentuje skupinu sérií.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Určuje, jak jsou hodnoty velikosti bubliny zobrazeny v bublinovém grafu. Číst/zapisovat [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Určuje měřítkový faktor pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). Číst/zapisovat Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Vrací nadřazený graf. Pouze pro čtení [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Určuje velikost díry v prstencovém grafu (může být mezi 0 a 90 procenty velikosti oblasti výkresu). Číst/zapisovat Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Získává nebo nastavuje úhel prvního výseku koláčového nebo prstencového grafu ve stupních (ve směru hodinových ručiček od shora, od 0 do 360 stupňů). Číst/zapisovat UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Vrací nebo nastavuje vzdálenost jako procento šířky značky mezi datovými sériemi ve 3D grafu. Číst/zapisovat UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Určuje mezery mezi shluky sloupců nebo sloupcových klastrů jako procento šířky sloupce nebo kolony. Číst/zapisovat UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True, pokud graf obsahuje řádkové čáry. Používá se u sloupcových grafů s hromaděním a grafů OfPie. Číst/zapisovat Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Určuje formát HiLowLines. HiLowLines se používá s typy grafů HiLowClose, OpenHiLowClose, VolumeHiLowClose a VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Určuje, že každý datový marker v sérii má jinou barvu. Číst/zapisovat Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Získává prvek na zadaném indexu. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Určuje, jak moc se mají sloupce a kolonky překrývat v 2-D grafech, jako procento (od -100 % do 100 %). - -100 %: Maximální rozestup (sloupce jsou zcela odděleny). - 0 %: Sloupce jsou umístěny vedle sebe bez překrytí nebo mezery. - 100 %: Maximální překrytí (sloupce se zcela překrývají). Tato vlastnost je Číst/zapisovat SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Určuje, jak určit, které datové body jsou ve druhém koláči nebo sloupci v grafu pie-of-pie nebo bar-of-pie. Číst/zapisovat [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. Obsahuje datové body, které se mají vykreslit ve druhém koláči nebo sloupci v grafu pie-of-pie nebo bar-of-pie. Pouze pro čtení [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Určuje hodnotu, která se má použít k určení, které datové body jsou ve druhém koláči nebo sloupci v grafu pie-of-pie nebo bar-of-pie. Používá se spolu s vlastností PieSplitBy. Číst/zapisovat Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Udává, zda jsou řady této skupiny vykresleny na sekundární ose. Pouze pro čtení Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Určuje velikost druhého koláče nebo sloupce v grafu pie-of-pie nebo bar-of-pie jako procento velikosti prvního koláče (může být mezi 5 a 200 procenty). Číst/zapisovat UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Vrací kolekci řad. Pouze pro čtení [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Vrací typ této skupiny řad. Pouze pro čtení [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Provede přístup k horním/dolním pruhům v čárovém nebo akciovém grafu. Pouze pro čtení [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Poznámky

1) Viz souhrnu a poznámky pro třídu ChartSeriesGroupCollection a výčtový typ CombinableSeriesTypesGroup. 2) Skupina řad obsahuje některé vlastnosti řad, které jsou společné pro každou řadu ve skupině („vlastnosti skupiny řad“). „Vlastnosti skupiny řad“ v třídě ChartSeriesGroup jsou číst/zapisovat. Každá z „vlastností skupiny řad“ může mít v třídě ChartSeries projekt pouze pro čtení.

### Viz také

* rozhraní [IChartSeriesGroup](../ichartseriesgroup)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->