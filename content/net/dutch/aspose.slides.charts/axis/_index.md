---
title: Axis
second_title: Aspose.Sildes voor .NET API-referentie
description: Omvat het object dat een as van een diagram vertegenwoordigt.
type: docs
weight: 1180
url: /nl/aspose.slides.charts/axis/
---
## Axis klasse

Omvat het object dat een as van een diagram vertegenwoordigt.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Specificeert de werkelijke hoofdeenheid van de as. Roep de methode IChart.ValidateChartLayout() vooraf aan om de werkelijke waarde te verkrijgen. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Specificeert de werkelijke schaal van de hoofdeenheid van de as. Roep de methode IChart.ValidateChartLayout() vooraf aan om de werkelijke waarde te verkrijgen. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Specificeert de werkelijke maximale waarde op de as. Roep de methode IChart.ValidateChartLayout() vooraf aan om de werkelijke waarde te verkrijgen. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Specificeert de werkelijke ondereenheid van de as. Roep de methode IChart.ValidateChartLayout() vooraf aan om de werkelijke waarde te verkrijgen. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Specificeert de werkelijke schaal van de ondereenheid van de as. Roep de methode IChart.ValidateChartLayout() vooraf aan om de werkelijke waarde te verkrijgen. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Specificeert de werkelijke minimale waarde op de as. Roep de methode IChart.ValidateChartLayout() vooraf aan om de werkelijke waarde te verkrijgen. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Stelt het aggregatietype van de categorie-as (binning) voor. Toegepast op de categorie. Alleen gebruikt met Histogram- of HistogramPareto-series. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Geeft aan of de waardenas de categorie-as tussen categorieën kruist. Deze eigenschap is alleen van toepassing op categorie-assen en geldt niet voor 3-D-diagrammen. Lezen/Schrijven Booleaans. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Specificeert de kleinste tijdseenheid die op de datum-as wordt weergegeven. Lezen/Schrijven [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Specificeert de bin-breedte wanneer de eigenschap AggregationType is ingesteld op AxisAggregationType.ByBinWidth. Toegepast op categorie-assen. Alleen gebruikt met Histogram- of HistogramPareto-series. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Specificeert het type van de categorie-as. Lezen/Schrijven [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Retourneert het bovenliggende diagram. Alleen-lezen [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Stelt het punt op de as voor waar de loodrechte as deze kruist. Lezen/Schrijven Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Stelt het CrossType op de opgegeven as voor waar de andere as kruist. Lezen/Schrijven [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. Lezen/Schrijven [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Stelt het formaat van de as voor. Alleen-lezen [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Bepaalt of een as een zichtbare titel heeft. Lezen/Schrijven Booleaans. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Geeft aan of de hoofdeenheid van de as automatisch wordt toegewezen. Lezen/Schrijven Booleaans. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Geeft aan of de maximale waarde automatisch wordt toegewezen. Lezen/Schrijven Booleaans. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Geeft aan of de ondereenheid van de as automatisch wordt toegewezen. Lezen/Schrijven Booleaans. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Geeft aan of de minimale waarde automatisch wordt toegewezen. Lezen/Schrijven Booleaans. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Specificeert de automatische overflow-bin-waarde. Indien false: gebruik de eigenschap OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Specificeert de automatische tussenruimte voor tick-labels. Indien false: gebruik de eigenschap TickLabelSpacing. Lezen/Schrijven Booleaans. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Specificeert de automatische tussenruimte voor tick-markeringen. Indien false: gebruik de eigenschap TickMarksSpacing. Lezen/Schrijven Booleaans. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Specificeert de automatische underflow-bin-waarde. Indien false: gebruik de eigenschap UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Geeft aan of het schaaltype van de waardenas logaritmisch is of niet. Lezen/Schrijven Booleaans. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Geeft aan of het formaat gekoppeld is aan brongegevens. Lezen/Schrijven Booleaans. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Specificeert of overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-bin-waarde aan te passen. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Geeft aan of MS PowerPoint gegevenspunten plot van laatste naar eerste. Lezen/Schrijven Booleaans. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Specificeert of underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-bin-waarde aan te passen. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Geeft aan of de as zichtbaar is. Lezen/Schrijven Booleaans. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Specificeert de afstand van labels tot de as. Toegepast op categorie- of datum-as. Waarde moet tussen 0% en 1000% liggen. Lezen/Schrijven UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Stelt de logaritmische basis voor. Standaardwaarde is 10. Lezen/Schrijven Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Stelt het formaat van hoofdroosterlijnen op een diagram-as voor. Alleen-lezen [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Stelt het type van de hoofd-tickmarkering voor op de opgegeven as. Lezen/Schrijven [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Stelt de hoofd-eenheden voor de datum- of waardenas voor. Lezen/Schrijven Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Stelt de schaal van de hoofd-eenheid voor de datum-as voor. Lezen/Schrijven [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Stelt de maximale waarde op de waardenas voor. Lezen/Schrijven Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Stelt het formaat van de minorroosterlijnen op een diagram-as voor. Alleen-lezen [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Stelt het type van de minor-tickmarkering voor op de opgegeven as. Lezen/Schrijven [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Stelt de minor-eenheden voor de datum- of waardenas voor. Lezen/Schrijven Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Stelt de schaal van de hoofd-eenheid voor de datum-as voor. Lezen/Schrijven [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Stelt de minimale waarde op de waardenas voor. Lezen/Schrijven Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Stelt de opmaakstring voor de As-Labels voor. Lezen/Schrijven String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Specificeert het aantal bins wanneer de eigenschap AggregationType is ingesteld op AxisAggregationType.ByNumberOfBins. Toegepast op categorie-assen. Alleen gebruikt met Histogram- of HistogramPareto-series. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Specificeert een aangepaste overflow-bin-waarde. Toegepast wanneer de eigenschap IsAutomaticOverflowBin is ingesteld op false en de eigenschap IsOverflowBin true is. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Stelt de positie van de as voor. Lezen/Schrijven [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Om de hoofdroosterlijn te verbergen, stel MajorGridLinesFormat.Line.FillFormat.FillType in op FillType.NoFill. Alleen-lezen Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Om de minorroosterlijn te verbergen, stel MinorGridLinesFormat.Line.FillFormat.FillType in op FillType.NoFill. Alleen-lezen Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Stelt het formaat van tekst voor. Alleen-lezen [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Stelt de positie van tick-mark-labels op de opgegeven as voor. Lezen/Schrijven [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Stelt de rotatiehoek van tick-labels voor. Lezen/Schrijven Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Specificeert hoeveel tick-labels er worden overgeslagen tussen getekende labels. Toegepast op categorie- of series-as. Lezen/Schrijven UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Specificeert hoeveel tick-markeringen moeten worden overgeslagen voordat de volgende wordt getekend. Toegepast op categorie- of series-as. Lezen/Schrijven UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Haalt de titel van de as op. Alleen-lezen [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Specificeert een aangepaste underflow-bin-waarde. Toegepast wanneer de eigenschap IsAutomaticUnderflowBin is ingesteld op false en de eigenschap IsUnderflowBin true is. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Stelt de eigenschap IAxis.CategoryAxisType in met een waarde die automatisch wordt bepaald op basis van as-gegevens. |

### Zie ook

* klasse [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* klasse [AxesManager](../axesmanager)
* interface [IAxis](../iaxis)
* naamruimte [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->