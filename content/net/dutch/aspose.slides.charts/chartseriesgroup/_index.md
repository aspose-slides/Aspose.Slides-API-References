---
title: ChartSeriesGroup
second_title: Aspose.Sildes voor .NET API-referentie
description: Vertegenwoordigt een groep series.
type: docs
weight: 1460
url: /nl/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup klasse

Vertegenwoordigt een groep van series.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Specificeert hoe de bubbelformaatwaarden worden weergegeven op de bubbelgrafiek. Lezen/schrijven [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Specificeert de schaalfactor voor de bubbelgrafiek (kan tussen 0 en 300 % van de standaardgrootte liggen). Lezen/schrijven Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Retourneert de bovenliggende grafiek. Alleen-lezen [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Specificeert de grootte van het gat in een donutgrafiek (kan tussen 0 en 90 % van de grootte van het tekengedeelte liggen). Lezen/schrijven Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Haalt de hoek van de eerste taart- of donutgrafieksegment op, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Lezen/schrijven UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Retourneert of stelt de afstand in, als percentage van de markerbreedte, tussen de gegevensseries in een 3D-grafiek. Lezen/schrijven UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Specificeert de ruimte tussen staaf- of kolomclusters, als percentage van de staaf- of kolombreedte. Lezen/schrijven UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Waar als de grafiek serielijnen heeft. Toegepast op gestapelde staaf- en OfPie-grafieken. Lezen/schrijven Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Specificeert HiLowLines-indeling. HiLowLines toegepast met HiLowClose, OpenHiLowClose, VolumeHiLowClose en VolumeOpenHiLowClose grafiektypen. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Specificeert dat elke datamarker in de serie een andere kleur heeft. Lezen/schrijven Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Haalt het element op op de opgegeven index. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Specificeert hoeveel staven en kolommen op 2-D-grafieken overlappen, als percentage (van -100 % tot 100 %). -100 %: maximale afstand (staven zijn volledig gescheiden). -0 %: staven staan naast elkaar zonder overlap of afstand. 100 %: maximale overlap (staven overlappen volledig). Deze eigenschap is lezen/schrijven SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Specificeert hoe bepaald wordt welke datapunten in de tweede taart of staaf van een pie-of-pie- of bar-of-pie-grafiek voorkomen. Lezen/schrijven [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | De aangepaste splitsingsinformatie voor een pie-of-pie- of bar-of-pie-grafiek met een aangepaste splitsing. Bevat datapunten die in de tweede taart of staaf van een pie-of-pie- of bar-of-pie-grafiek getekend moeten worden. Alleen-lezen [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Specificeert een waarde die gebruikt wordt om te bepalen welke datapunten in de tweede taart of staaf van een pie-of-pie- of bar-of-pie-grafiek voorkomen. Wordt samen met de eigenschap PieSplitBy gebruikt. Lezen/schrijven Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Geeft aan of series van deze groep op een secundaire as worden geplot. Alleen-lezen Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Specificeert de grootte van de tweede taart of staaf van een pie-of-pie-grafiek of een bar-of-pie-grafiek, als percentage van de grootte van de eerste taart (kan tussen 5 en 200 % liggen). Lezen/schrijven UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Retourneert een collectie van series. Alleen-lezen [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Retourneert een type van deze seriegroep. Alleen-lezen [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Biedt toegang tot op/ neer-balken van een lijn- of aandelen-grafiek. Alleen-lezen [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Opmerkingen

1) Zie samenvatting en opmerkingen voor ChartSeriesGroupCollection klasse en CombinableSeriesTypesGroup enum.  
2) Een groep van series bevat enkele series-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep (“series group properties”). “Series group properties” in de ChartSeriesGroup klasse is lezen/schrijven. Elke “series group properties” kan een alleen-lezen projectie hebben in de ChartSeries klasse.

### Zie ook

* interface [IChartSeriesGroup](../ichartseriesgroup)
* naamruimte [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->