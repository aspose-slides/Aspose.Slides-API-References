---
title: IAxis
second_title: Aspose.Sildes voor .NET API-referentie
description: Omsluit het object dat een as van een diagram vertegenwoordigt.
type: docs
weight: 1720
url: /nl/aspose.slides.charts/iaxis/
---
## IAxis interface

Omsluit het object dat een as van een diagram vertegenwoordigt.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Specificeert de werkelijke hoofd-eenheid van de as. Roep hiervoor eerst de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Specificeert de werkelijke schaal van de hoofd-eenheid van de as. Roep hiervoor eerst de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Specificeert de werkelijke maximale waarde op de as. Roep hiervoor eerst de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Specificeert de werkelijke ondereenheid van de as. Roep hiervoor eerst de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Specificeert de werkelijke schaal van de ondereenheid van de as. Roep hiervoor eerst de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Specificeert de werkelijke minimale waarde op de as. Roep hiervoor eerst de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Stelt het aggregatietype van de categorias as (binning) voor. Toegepast op categorie. Alleen te gebruiken met Histogram of HistogramPareto series. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Stelt in staat om de basis IFormattedTextContainer interface op te halen. Alleen-lezen [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Geeft aan of de waardenas de categorias as tussen de categorieën kruist. Deze eigenschap geldt alleen voor categorias assen en is niet van toepassing op 3-D-diagrammen. Lezen/schrijven Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Specificeert de kleinste tijdseenheid die op de datum-as wordt weergegeven. Lezen/schrijven [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Specificeert de bin-breedte wanneer de AggregationType eigenschap is ingesteld op AxisAggregationType.ByBinWidth. Toegepast op categorias assen. Alleen te gebruiken met Histogram of HistogramPareto series. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Specificeert het type van de categorias as. Lezen/schrijven [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Stelt het punt op de as voor waar de loodrechte as deze kruist. Lezen/schrijven Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Stelt het CrossType op de opgegeven as voor waar de andere as kruist. Lezen/schrijven [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. Lezen/schrijven [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Stelt het formaat van de as voor. Alleen-lezen [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Bepaalt of een as een zichtbare titel heeft. Lezen/schrijven Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Geeft aan of de hoofd-eenheid van de as automatisch wordt toegewezen. Lezen/schrijven Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Geeft aan of de maximale waarde automatisch wordt toegewezen. Lezen/schrijven Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Geeft aan of de ondereenheid van de as automatisch wordt toegewezen. Lezen/schrijven Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Geeft aan of de minimale waarde automatisch wordt toegewezen. Lezen/schrijven Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Specificeert de automatische overflow-binknoopwaarde. Indien false: gebruik de OverflowBin eigenschap. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Specificeert de automatische afstand tussen tick-labels. Indien false: gebruik de TickLabelSpacing eigenschap. Lezen/schrijven Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Specificeert de automatische afstand tussen tick-markeringen. Indien false: gebruik de TickMarksSpacing eigenschap. Lezen/schrijven Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Specificeert de automatische underflow-binknoopwaarde. Indien false: gebruik de UnderflowBin eigenschap. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Geeft aan of het schaaltype van de waardenas logaritmisch is. Lezen/schrijven Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Geeft aan of het formaat is gekoppeld aan brongegevens. Lezen/schrijven Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Specificeert of overflow-binknoop wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-binknoopwaarde aan te passen. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Geeft aan of MS PowerPoint gegevenspunten van laatste naar eerste plot. Lezen/schrijven Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Specificeert of underflow-binknoop wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-binknoopwaarde aan te passen. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Geeft aan of de as zichtbaar is. Lezen/schrijven Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Specificeert de afstand van labels tot de as. Toegepast op categorie- of datum-as. Waarde moet tussen 0% en 1000% liggen. Lezen/schrijven UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Stelt de logaritmische basis voor. Standaardwaarde is 10. Lezen/schrijven Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Stelt het formaat van de hoofd-roosterrasterlijnen op een diagramas voor. Alleen-lezen [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Stelt het type van de hoofd-tick-markering voor de opgegeven as voor. Lezen/schrijven [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Stelt de hoofd-eenheden voor de datum- of waardenas voor. Lezen/schrijven Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Stelt de schaal van de hoofd-eenheid voor de datum-as voor. Lezen/schrijven [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Stelt de maximale waarde op de waardenas voor. Lezen/schrijven Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Stelt het formaat van de onder-roosterrasterlijnen op een diagramas voor. Alleen-lezen [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Stelt het type van de onder-tick-markering voor de opgegeven as voor. Lezen/schrijven [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Stelt de onder-eenheden voor de datum- of waardenas voor. Lezen/schrijven Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Stelt de schaal van de hoofd-eenheid voor de datum-as voor. Lezen/schrijven [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Stelt de minimale waarde op de waardenas voor. Lezen/schrijven Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Stelt de opmaak-string voor de as-labels voor. Lezen/schrijven String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Specificeert het aantal bins wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByNumberOfBins. Toegepast op categorias assen. Alleen te gebruiken met Histogram of HistogramPareto series. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Specificeert een aangepaste overflow-binknoopwaarde. Toegepast wanneer IsAutomaticOverflowBin-eigenschap op false staat en IsOverflowBin-eigenschap true is. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Stelt de positie van de as voor. Lezen/schrijven [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Geeft aan of de hoofd-roosterrasterlijnen worden getoond. Alleen-lezen Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Geeft aan of de onder-roosterrasterlijnen worden getoond. Alleen-lezen Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Stelt de positie van tick-labelmarkeringen op de opgegeven as voor. Lezen/schrijven [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Stelt de rotatiehoek van tick-labels voor. Lezen/schrijven Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Specificeert hoeveel tick-labels overgeslagen moeten worden tussen de getekende label. Lezen/schrijven UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Specificeert hoeveel tick-markeringen overgeslagen moeten worden voordat de volgende wordt getekend. Toegepast op categorie- of serie-as. Lezen/schrijven UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Haalt de titel van de as op. Alleen-lezen [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Specificeert een aangepaste underflow-binknoopwaarde. Toegepast wanneer IsAutomaticUnderflowBin-eigenschap op false staat en IsUnderflowBin-eigenschap true is. |

## Methodes

| Naam | Beschrijving |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Stelt de IAxis.CategoryAxisType eigenschap in met een waarde die automatisch wordt bepaald op basis van as-gegevens. |

### Zie ook

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->