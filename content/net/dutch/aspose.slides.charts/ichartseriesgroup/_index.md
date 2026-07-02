---
title: IChartSeriesGroup
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een groep van series voor.
type: docs
weight: 1950
url: /nl/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup interface

Stelt een groep van series voor.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Eigenschappen

| Name | Description |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Staat toe om de basis IChartComponent interface op te halen. Alleen-lezen [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Specificeert hoe de waarden voor de bubbelgrootte worden weergegeven in de bubbelgrafiek. Lezen/Schrijven [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Specificeert de schaalfactor voor de bubbelgrafiek (kan tussen 0 en 300 procent van de standaardgrootte liggen). Lezen/Schrijven Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Specificeert de grootte van het gat in een doughnutgrafiek (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen). Lezen/Schrijven Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Haalt op of stelt de hoek in van het eerste taart- of doughnutgrafieksegment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Lezen/Schrijven UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Geeft de afstand terug of stelt deze in, als een percentage van de markerbreedte, tussen de dataseries in een 3D-grafiek. Lezen/Schrijven UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de balk- of kolombreedte. Lezen/Schrijven UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Waar als de grafiek serielijnen heeft. Toegepast op gestapelde balk- en OfPie-grafieken. Lezen/Schrijven Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Specificeert het HiLowLines-formaat. HiLowLines wordt toegepast met HiLowClose, OpenHiLowClose, VolumeHiLowClose en VolumeOpenHiLowClose grafiektype-n. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Specificeert dat elke datamarker in de serie een andere kleur heeft. Lezen/Schrijven Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Haalt het element op op de opgegeven index. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Specificeert hoeveel balken en kolommen moeten overlappen in 2-D-grafieken, als een percentage (van -100% tot 100%). - -100%: Maximale afstand (balken zijn volledig gescheiden). - 0%: Balken staan naast elkaar zonder overlap of afstand. - 100%: Maximale overlap (balken overlappen volledig). Deze eigenschap is Lezen/Schrijven SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Specificeert hoe bepaald wordt welke gegevenspunten zich in de tweede taart of balk bevinden in een pie-of-pie- of bar-of-pie-grafiek. Lezen/Schrijven [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | De aangepaste splitsinformatie voor een pie-of-pie- of bar-of-pie-grafiek met een aangepaste splitsing. Bevat gegevenspunten die getekend moeten worden in de tweede taart of balk in een pie-of-pie- of bar-of-pie-grafiek. Alleen-lezen [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Specificeert een waarde die gebruikt moet worden om te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden in een pie-of-pie- of bar-of-pie-grafiek. Wordt samen met de eigenschap PieSplitBy gebruikt. Lezen/Schrijven Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Geeft aan of de series van deze groep worden weergegeven op de secundaire as. Alleen-lezen Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Specificeert de grootte van de tweede taart of balk van een pie-of-pie-grafiek of een bar-of-pie-grafiek, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Lezen/Schrijven UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Geeft een alleen-lezen collectie van grafiekseries terug. Alleen-lezen [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Geeft het type van deze seriegroep terug. Alleen-lezen [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Biedt toegang tot op/af-balken van een Lijn- of Aandelen-grafiek. Alleen-lezen [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Opmerkingen

1) Zie samenvatting en opmerkingen voor de ChartSeriesGroupCollection klasse en de CombinableSeriesTypesGroup enum. 2) Een groep series bevat enkele series-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep (“eigenschappen van de seriegroep”). “Eigenschappen van de seriegroep” in de ChartSeriesGroup klasse zijn Lezen/Schrijven. Elke “eigenschap van de seriegroep” kan een alleen-lezen projectie hebben in de ChartSeries klasse.

### Zie ook

* interface [IChartComponent](../ichartcomponent)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->