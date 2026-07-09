---
title: Axis
second_title: Aspose.Sildes voor .NET API-referentie
description: Omvat het object dat een as van een grafiek vertegenwoordigt.
type: docs
weight: 1180
url: /nl/aspose.slides.charts/axis/
---
## Axis klasse

Encapsulates the object that represents a chart's axis.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Eigenschappen

| Name | Description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Specificeert de werkelijke major-eenheid van de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Specificeert de werkelijke schaal van de major-eenheid van de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Specificeert de werkelijke maximumwaarde op de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Specificeert de werkelijke minor-eenheid van de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Specificeert de werkelijke schaal van de minor-eenheid van de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Specificeert de werkelijke minimumwaarde op de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Geeft het aggregatietype van de categoriasas (binning) weer. Toegepast op categorie. Alleen gebruikt met Histogram- of HistogramPareto-reeksen. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Geeft aan of de waarde-as de categoriasas tussen categorieën kruist. Deze eigenschap geldt alleen voor categoriasen en niet voor 3D-grafieken. Lezen/schrijven Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Specificeert de kleinste tijdseenheid die op de datum-as wordt weergegeven. Lezen/schrijven [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Specificeert de breedte van de bin wanneer de eigenschap AggregationType is ingesteld op AxisAggregationType.ByBinWidth. Toegepast op categoriasen. Alleen gebruikt met Histogram- of HistogramPareto-reeksen. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Specificeert het type van de categoriasas. Lezen/schrijven [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Retourneert de bovenliggende grafiek. Alleen-lezen [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Geeft het punt op de as weer waar de loodrechte as deze kruist. Lezen/schrijven Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Geeft het CrossType op de opgegeven as weer waar de andere as deze kruist. Lezen/schrijven [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Specificeert de schaalwaarde van de weergave-eenheden voor de waarde-as. Lezen/schrijven [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Geeft het formaat van de as weer. Alleen-lezen [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Bepaalt of een as een zichtbare titel heeft. Lezen/schrijven Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Geeft aan of de major-eenheid van de as automatisch wordt toegewezen. Lezen/schrijven Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Geeft aan of de maximumwaarde automatisch wordt toegewezen. Lezen/schrijven Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Geeft aan of de minor-eenheid van de as automatisch wordt toegewezen. Lezen/schrijven Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Geeft aan of de minimumwaarde automatisch wordt toegewezen. Lezen/schrijven Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Specificeert de automatische overflow-binwaarde. Indien false: gebruik OverflowBin eigenschap. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Specificeert de automatische afstand tussen tick-labels. Indien false: gebruik TickLabelSpacing eigenschap. Lezen/schrijven Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Specificeert de automatische afstand tussen tick-markeringen. Indien false: gebruik TickMarksSpacing eigenschap. Lezen/schrijven Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Specificeert de automatische underflow-binwaarde. Indien false: gebruik UnderflowBin eigenschap. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Geeft aan of het schaaltype van de waarde-as logaritmisch is of niet. Lezen/schrijven Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Geeft aan of het formaat gekoppeld is aan brongegevens. Lezen/schrijven Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Specificeert of overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-binwaarde aan te passen. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Geeft aan of MS PowerPoint gegevenspunten van laatste naar eerste plot. Lezen/schrijven Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Specificeert of underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-binwaarde aan te passen. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Geeft aan of de as zichtbaar is. Lezen/schrijven Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Specificeert de afstand van labels tot de as. Toegepast op categorias- of datum-as. Waarde moet tussen 0% en 1000% liggen. Lezen/schrijven UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Geeft de logaritmische basis weer. Standaardwaarde is 10. Lezen/schrijven Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Geeft het formaat van de hoofdroosterlijnen op een grafiek-as weer. Alleen-lezen [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Geeft het type van de hoofd-tick-markering voor de opgegeven as weer. Lezen/schrijven [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Geeft de hoofd-eenheden voor de datum- of waarde-as weer. Lezen/schrijven Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Geeft de schaal van de hoofd-eenheid voor de datum-as weer. Lezen/schrijven [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Geeft de maximumwaarde op de waarde-as weer. Lezen/schrijven Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Geeft het formaat van de kleinere rasterlijnen op een grafiek-as weer. Alleen-lezen [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Geeft het type van de kleine tick-markering voor de opgegeven as weer. Lezen/schrijven [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Geeft de kleine eenheden voor de datum- of waarde-as weer. Lezen/schrijven Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Geeft de schaal van de hoofd-eenheid voor de datum-as weer. Lezen/schrijven [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Geeft de minimumwaarde op de waarde-as weer. Lezen/schrijven Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Geeft de opmaaktekenreeks voor de as-labels weer. Lezen/schrijven String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Specificeert het aantal bins wanneer de eigenschap AggregationType is ingesteld op AxisAggregationType.ByNumberOfBins. Toegepast op categoriasen. Alleen gebruikt met Histogram- of HistogramPareto-reeksen. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Specificeert de aangepaste waarde voor overflow-bin. Toegepast wanneer de eigenschap IsAutomaticOverflowBin is ingesteld op false en de eigenschap IsOverflowBin gelijk is aan true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Geeft de positie van de as weer. Lezen/schrijven [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Om de hoofdroosterlijn te verbergen, stel MajorGridLinesFormat.Line.FillFormat.FillType in op FillType.NoFill. Alleen-lezen Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Om de kleinere roosterlijn te verbergen, stel MinorGridLinesFormat.Line.FillFormat.FillType in op FillType.NoFill. Alleen-lezen Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Geeft het formaat van tekst weer. Alleen-lezen [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Geeft de positie van tick-mark-labels op de opgegeven as weer. Lezen/schrijven [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Geeft de rotatiehoek van tick-labels weer. Lezen/schrijven Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Specificeert hoeveel tick-labels overgeslagen moeten worden tussen getekende labels. Toegepast op categorias- of serie-as. Lezen/schrijven UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Specificeert hoeveel tick-markeringen overgeslagen moeten worden voordat de volgende wordt getekend. Toegepast op categorias- of serie-as. Lezen/schrijven UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Haalt de titel van de as op. Alleen-lezen [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Specificeert de aangepaste waarde voor underflow-bin. Toegepast wanneer de eigenschap IsAutomaticUnderflowBin is ingesteld op false en de eigenschap IsUnderflowBin gelijk is aan true. |

## Methodes

| Name | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Stelt de eigenschap IAxis.CategoryAxisType in met een waarde die automatisch wordt bepaald op basis van as-gegevens. |

### Zie ook

* klasse [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* klasse [AxesManager](../axesmanager)
* interface [IAxis](../iaxis)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->