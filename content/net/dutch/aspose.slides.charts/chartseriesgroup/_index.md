---
title: ChartSeriesGroup
second_title: Aspose.Slides voor .NET API-referentie
description: Vertegenwoordigt een groep van series.
type: docs
weight: 1470
url: /nl/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup klasse

Represents group of series.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Specificeert hoe de bubbelgroottewaarden worden weergegeven in het bubbel-diagram. Lezen/Schrijven [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Specificeert de schaalfactor voor het bubbel-diagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). Lezen/Schrijven Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Geeft het bovenliggende diagram terug. Alleen-lezen [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Specificeert de grootte van het gat in een donut-diagram (kan tussen 0 en 90 procent van de grootte van het plotgebied liggen). Lezen/Schrijven Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Haalt de hoek op of stelt deze in van het eerste taart- of donut-diagramsegment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Lezen/Schrijven UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Haalt de afstand op of stelt deze in tussen gegevensreeksen in een 3D-diagram, als een percentage van de markerbreedte. De waarde moet tussen 0 en 500 liggen. Lezen/Schrijven UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Haalt de ruimte op of stelt deze in tussen balk- of kolom-clusters, als een percentage van de balk- of kolombreedte. De waarde moet tussen 0 en 500 liggen. Lezen/Schrijven UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Waar als diagram reekslijnen heeft. Toegepast op gestapelde balk- en OfPie-diagrammen. Lezen/Schrijven Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Specificeert het HiLowLines-formaat. HiLowLines toegepast met HiLowClose, OpenHiLowClose, VolumeHiLowClose en VolumeOpenHiLowClose diagramtypen. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Specificeert dat elke datamarker in de reeks een andere kleur heeft. Lezen/Schrijven Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Haalt het element op op de opgegeven index. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Specificeert hoeveel balken en kolommen overlappen in 2-D-diagrammen, als een percentage (van -100 % tot 100 %). - -100 %: Maximale spatiëring (balken zijn volledig gescheiden). - 0 %: Balken staan naast elkaar zonder overlapping of ruimte. - 100 %: Maximale overlapping (balken overlappen volledig elkaar). Deze eigenschap is Lezen/Schrijven SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Specificeert hoe bepaald wordt welke gegevenspunten zich in de tweede taart of balk bevinden in een taart-van-taart- of balk-van-taart-diagram. Lezen/Schrijven [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | De aangepaste splitsingsinformatie voor een taart-van-taart- of balk-van-taart-diagram met een aangepaste splitsing. Bevat gegevenspunten die in de tweede taart of balk moeten worden getekend in een taart-van-taart- of balk-van-taart-diagram. Alleen-lezen [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Specificeert een waarde die gebruikt wordt om te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden in een taart-van-taart- of balk-van-taart-diagram. Wordt samen met de eigenschap PieSplitBy gebruikt. Lezen/Schrijven Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Geeft aan of reeksen van deze groep worden weergegeven op een secundaire as. Alleen-lezen Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Specificeert de grootte van de tweede taart of balk van een taart-van-taart- of balk-van-taart-diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Lezen/Schrijven UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Geeft een verzameling van reeksen terug. Alleen-lezen [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Geeft een type van deze reeksgroep terug. Alleen-lezen [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Biedt toegang tot op/naar-beneden-balken van een Lijn- of Aandelen-diagram. Alleen-lezen [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Opmerkingen

1) Zie de samenvatting en opmerkingen voor de ChartSeriesGroupCollection klasse en de CombinableSeriesTypesGroup enum. 2) Een groep reeksen bevat enkele reeks-eigenschappen die gemeenschappelijk zijn voor elke reeks in de groep (“series group properties”). “Series group properties” in de ChartSeriesGroup klasse is Lezen/Schrijven. Elke “series group properties” kan een Alleen-lezen projectie hebben in de ChartSeries klasse.

### Zie ook

* interface [IChartSeriesGroup](../ichartseriesgroup)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->