---
title: IAxis
second_title: Aspose.Sildes voor .NET API-referentie
description: Omsluit het object dat de as van een diagram vertegenwoordigt.
type: docs
weight: 1710
url: /nl/aspose.slides.charts/iaxis/
---
## IAxis interface

Omsluit het object dat de as van een diagram vertegenwoordigt.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Specificeert de feitelijke hoofd eenheid van de as. Roep hiervoor vooraf de methode IChart.ValidateChartLayout() aan om de feitelijke waarde te verkrijgen. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Specificeert de feitelijke schaal van de hoofd eenheid van de as. Roep hiervoor vooraf de methode IChart.ValidateChartLayout() aan om de feitelijke waarde te verkrijgen. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Specificeert de feitelijke maximale waarde op de as. Roep hiervoor vooraf de methode IChart.ValidateChartLayout() aan om de feitelijke waarde te verkrijgen. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Specificeert de feitelijke secundaire eenheid van de as. Roep hiervoor vooraf de methode IChart.ValidateChartLayout() aan om de feitelijke waarde te verkrijgen. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Specificeert de feitelijke schaal van de secundaire eenheid van de as. Roep hiervoor vooraf de methode IChart.ValidateChartLayout() aan om de feitelijke waarde te verkrijgen. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Specificeert de feitelijke minimale waarde op de as. Roep hiervoor vooraf de methode IChart.ValidateChartLayout() aan om de feitelijke waarde te verkrijgen. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Stelt het aggregatietype van de categorieas (binnend) voor. Toegepast op categorie. Alleen te gebruiken met Histogram- of HistogramPareto-series. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Staat toe de basis IFormattedTextContainer interface op te halen. Alleen-lezen [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Geeft aan of de waardenas de categorieas tussen categorieën kruist. Deze eigenschap is alleen van toepassing op categorieassen en niet op 3D-diagrammen. Lees/schrijf Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Specificeert de kleinste tijdseenheid die op de datum-as wordt weergegeven. Lees/schrijf [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Specificeert de bin-breedte wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByBinWidth. Toegepast op categorieassen. Alleen te gebruiken met Histogram- of HistogramPareto-series. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Specificeert het type van de categorieas. Lees/schrijf [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Geeft het punt op de as aan waar de loodrechte as deze kruist. Lees/schrijf Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Geeft het CrossType op de opgegeven as aan waar de andere as kruist. Lees/schrijf [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. Lees/schrijf [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Geeft het formaat van de as weer. Alleen-lezen [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Bepaalt of een as een zichtbare titel heeft. Lees/schrijf Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Geeft aan of de hoofd eenheid van de as automatisch wordt toegewezen. Lees/schrijf Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Geeft aan of de maximale waarde automatisch wordt toegewezen. Lees/schrijf Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Geeft aan of de secundaire eenheid van de as automatisch wordt toegewezen. Lees/schrijf Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Geeft aan of de minimale waarde automatisch wordt toegewezen. Lees/schrijf Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Specificeert de automatische overflow-bin waarde. Indien onwaar: gebruik de OverflowBin-eigenschap. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Specificeert de automatische streepjes-labelafstand. Indien onwaar: gebruik de TickLabelSpacing-eigenschap. Lees/schrijf Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Specificeert de automatische streepjes-markeringafstand. Indien onwaar: gebruik de TickMarksSpacing-eigenschap. Lees/schrijf Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Specificeert de automatische underflow-bin waarde. Indien onwaar: gebruik de UnderflowBin-eigenschap. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Geeft aan of het schaaltype van de waardenas logaritmisch is of niet. Lees/schrijf Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Geeft aan of het formaat gekoppeld is aan brongegevens. Lees/schrijf Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Specificeert of een overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-bin waarde aan te passen. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Geeft aan of MS PowerPoint gegevenspunten van laatste naar eerste plot. Lees/schrijf Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Specificeert of een underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-bin waarde aan te passen. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Geeft aan of de as zichtbaar is. Lees/schrijf Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Specificeert de afstand van labels tot de as. Toegepast op categorie- of datum-as. Waarde moet tussen 0% en 1000% liggen. Lees/schrijf UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Geeft de logaritmische basis weer. Standaardwaarde is 10. Lees/schrijf Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Geeft het formaat van de hoofd rasterlijnen op een diagramas weer. Alleen-lezen [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Geeft het type van de hoofd-tickmarkering voor de opgegeven as weer. Lees/schrijf [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Geeft de hoofd eenheden voor de datum- of waardenas weer. Lees/schrijf Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Geeft de schaal van de hoofd eenheid voor de datum-as weer. Lees/schrijf [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Geeft de maximale waarde op de waardenas weer. Lees/schrijf Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Geeft het formaat van de secundaire rasterlijnen op een diagramas weer. Alleen-lezen [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Geeft het type van de secundaire tickmarkering voor de opgegeven as weer. Lees/schrijf [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Geeft de secundaire eenheden voor de datum- of waardenas weer. Lees/schrijf Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Geeft de schaal van de hoofd eenheid voor de datum-as weer. Lees/schrijf [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Geeft de minimale waarde op de waardenas weer. Lees/schrijf Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Geeft de opmaakreeks voor de As-labels weer. Lees/schrijf String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Specificeert het aantal bins wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByNumberOfBins. Toegepast op categorieassen. Alleen te gebruiken met Histogram- of HistogramPareto-series. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Specificeert een aangepaste overflow-bin waarde. Toegepast wanneer IsAutomaticOverflowBin onwaar is en IsOverflowBin waar is. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Geeft de positie van de as weer. Lees/schrijf [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Geeft aan of de hoofd rasterlijnen worden weergegeven. Alleen-lezen Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Geeft aan of de secundaire rasterlijnen worden weergegeven. Alleen-lezen Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Geeft de positie van tick-mark labels op de opgegeven as weer. Lees/schrijf [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Geeft de rotatiehoek van tick-labels weer. Lees/schrijf Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Specificeert hoeveel tick-labels overgeslagen moeten worden tussen getekende labels. Lees/schrijf UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Specificeert hoeveel tick-marks overgeslagen moeten worden voordat de volgende getekend wordt. Toegepast op categorie- of serie-as. Lees/schrijf UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Haalt de titel van de as op. Alleen-lezen [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Specificeert een aangepaste underflow-bin waarde. Toegepast wanneer IsAutomaticUnderflowBin onwaar is en IsUnderflowBin waar is. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Stelt de IAxis.CategoryAxisType-eigenschap in met een waarde die automatisch wordt bepaald op basis van asgegevens. |

### Zie ook

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->