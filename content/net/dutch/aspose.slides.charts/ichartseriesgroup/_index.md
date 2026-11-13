---
title: IChartSeriesGroup
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een groep van series voor.
type: docs
weight: 1970
url: /nl/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup interface

Represents group of series.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Staat toe om de basis IChartComponent interface op te halen. Alleen-lezen [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Specificeert hoe de bubbelgrootte-waarden worden weergegeven op de bubbelgrafiek. Lezen/Schrijven [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Specificeert de schaalfactor voor de bubbelgrafiek (kan tussen 0 en 300 procent van de standaardgrootte liggen). Lezen/Schrijven Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Specificeert de grootte van het gat in een donutgrafiek (kan tussen 10 en 90 procent van de grootte van het tekengebied liggen). Lezen/Schrijven Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Haalt op of stelt de hoek van het eerste part van een taart- of donutgrafiek in graden in (met de klok mee vanaf boven, van 0 tot 360 graden). Lezen/Schrijven UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Haalt op of stelt de afstand tussen gegevensreeksen in een 3D-grafiek in, als een percentage van de markerbreedte. De waarde moet tussen 0 en 500 liggen. Lezen/Schrijven UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Haalt op of stelt de ruimte tussen balk- of kolomclusters in, als een percentage van de balk- of kolombreedte. De waarde moet tussen 0 en 500 liggen. Lezen/Schrijven UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Waar als de grafiek serieslíneas heeft. Toegepast op gestapelde balk- en OfPie-grafieken. Lezen/Schrijven Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Specificeert HiLowLines-indeling. HiLowLines toegepast bij HiLowClose, OpenHiLowClose, VolumeHiLowClose en VolumeOpenHiLowClose grafiektype-n. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Specificeert dat elke datamarker in de reeks een andere kleur heeft. Lezen/Schrijven Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Haalt het element op op de opgegeven index. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Specificeert hoeveel balken en kolommen elkaar overlappen in 2-D-grafieken, als een percentage (van -100 % tot 100 %). - -100 %: Maximale afstand (balken zijn volledig gescheiden). - 0 %: Balken staan naast elkaar zonder overlapping of afstand. - 100 %: Maximale overlapping (balken overlappen volledig elkaar). Deze eigenschap is Lezen/Schrijven SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Specificeert hoe te bepalen welke datapunten in de tweede taart of balk staan op een taart-van-taart of balk-van-taart grafiek. Lezen/Schrijven [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | De aangepaste splitsingsinformatie voor een taart-van-taart of balk-van-taart grafiek met een aangepaste splitsing. Bevat datapunten die getekend moeten worden in de tweede taart of balk in een taart-van-taart of balk-van-taart grafiek. Alleen-lezen [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Specificeert een waarde die gebruikt wordt om te bepalen welke datapunten in de tweede taart of balk staan op een taart-van-taart of balk-van-taart grafiek. Wordt samen met de PieSplitBy-eigenschap gebruikt. Lezen/Schrijven Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Geeft aan of de reeksen van deze groep op de secundaire as worden geplot. Alleen-lezen Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Specificeert de grootte van de tweede taart of balk van een taart-van-taart grafiek of een balk-van-taart grafiek, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Lezen/Schrijven UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Geeft een alleen-lezen collectie van grafiekreeksen terug. Alleen-lezen [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Geeft een type van deze reeksgroep terug. Alleen-lezen [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Biedt toegang tot omhoog/omlaag-balken van lijn- of aandelengrafiek. Alleen-lezen [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Opmerkingen

1) Zie samenvatting en opmerkingen voor de ChartSeriesGroupCollection klasse en de CombinableSeriesTypesGroup enum. 2) Een groep van series bevat enkele serieseigenschappen die gemeenschappelijk zijn voor elke serie in de groep ("series group properties"). "Series group properties" in de ChartSeriesGroup klasse is lezen/schrijven. Elk van de "series group properties" kan een alleen-lezen projectie hebben in de ChartSeries klasse.

### Zie ook

* interface [IChartComponent](../ichartcomponent)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->