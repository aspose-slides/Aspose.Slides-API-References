---
title: ChartSeriesGroup
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een groep series voor.
type: docs
weight: 1460
url: /nl/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup klasse

Stelt een groep series voor.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Specificeert hoe de waarden voor de bubbelformaat worden weergegeven op het bubbeldiagram. Lezen/schrijven [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Specificeert de schaalfactor voor het bubbeldiagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). Lezen/schrijven Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Geeft het bovenliggende diagram terug. Alleen-lezen [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Specificeert de grootte van de opening in een donutdiagram (kan tussen 0 en 90 procent van de grootte van het plotgebied liggen). Lezen/schrijven Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Haalt op of stelt de hoek van het eerste taart- of donutdiagramsegment in, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Lezen/schrijven UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Geeft de afstand terug of stelt deze in, als een percentage van de markerbreedte, tussen de gegevensreeksen in een 3D-diagram. Lezen/schrijven UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de breedte van de balk of kolom. Lezen/schrijven UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Waar als het diagram serieslijnen heeft. Toegepast op gestapelde balk- en OfPie-diagrammen. Lezen/schrijven Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Specificeert het HiLowLines-formaat. HiLowLines wordt toegepast met HiLowClose, OpenHiLowClose, VolumeHiLowClose en VolumeOpenHiLowClose diagramtypen. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Specificeert dat elke datamarker in de reeks een andere kleur heeft. Lezen/schrijven Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Haalt het element op op de opgegeven index. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Specificeert hoeveel balken en kolommen moeten overlappen op 2D-diagrammen, als een percentage (van -100% tot 100%). - -100%: Maximale afstand (balken zijn volledig gescheiden). - 0%: Balken staan naast elkaar zonder overlap of ruimte. - 100%: Maximale overlap (balken overlappen volledig). Deze eigenschap is lezen/schrijven SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden op een taart-bij-taart of balk-bij-taart diagram. Lezen/schrijven [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | De aangepaste splitsingsinformatie voor een taart-bij-taart of balk-bij-taart diagram met een aangepaste splitsing. Bevat gegevenspunten die in de tweede taart of balk moeten worden getekend in een taart-bij-taart of balk-bij-taart diagram. Alleen-lezen [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Specificeert een waarde die gebruikt moet worden om te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden op een taart-bij-taart of balk-bij-taart diagram. Wordt gebruikt samen met de eigenschap PieSplitBy. Lezen/schrijven Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Geeft aan of de reeksen van deze groep op een secundaire as worden geplot. Alleen-lezen Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Specificeert de grootte van de tweede taart of balk van een taart-bij-taart of balk-bij-taart diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Lezen/schrijven UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Geeft een verzameling van reeksen terug. Alleen-lezen [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Geeft een type van deze seriesgroep terug. Alleen-lezen [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Biedt toegang tot op/naar beneden balken van Lijn- of Aandelen-diagrammen. Alleen-lezen [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Opmerkingen

1) Zie de samenvatting en opmerkingen voor ChartSeriesGroupCollection klasse en CombinableSeriesTypesGroup enum. 2) Groep van series bevat enkele series-eigenschappen die algemeen zijn voor elke serie in de groep (“series group properties”). “Series group properties” in ChartSeriesGroup klasse is lezen/schrijven. Elke “series group properties” kan een alleen-lezen projectie hebben in ChartSeries klasse.

### Zie ook

* interface [IChartSeriesGroup](../ichartseriesgroup)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->