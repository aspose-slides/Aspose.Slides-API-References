---
title: IAxis
second_title: Aspose.Sildes per il riferimento API .NET
description: Incapsula l'oggetto che rappresenta l'asse di un grafico.
type: docs
weight: 1690
url: /it/aspose.slides.charts/iaxis/
---
## IAxis interfaccia

Incapsula l'oggetto che rappresenta l'asse di un grafico.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Specifica l'unità principale reale dell'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore reale. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Specifica la scala dell'unità principale reale dell'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore reale. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Specifica il valore massimo reale sull'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore reale. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Specifica l'unità secondaria reale dell'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore reale. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Specifica la scala dell'unità secondaria reale dell'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore reale. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Specifica il valore minimo reale sull'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore reale. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Rappresenta il tipo di aggregazione dell'asse di categoria (raggruppamento). Applicato a categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Consente di ottenere l'interfaccia di base IFormattedTextContainer. Sola lettura [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Rappresenta se l'asse di valore attraversa l'asse di categoria tra le categorie. Questa proprietà si applica solo agli assi di categoria e non si applica ai grafici 3-D. Lettura/scrittura Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Specifica l'unità di tempo più piccola rappresentata sull'asse di data. Lettura/scrittura [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Specifica la larghezza del bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByBinWidth. Applicato agli assi di categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Specifica il tipo dell'asse di categoria. Lettura/scrittura [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa. Lettura/scrittura Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Rappresenta il CrossType sull'asse specificato dove l'altro asse lo attraversa. Lettura/scrittura [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Specifica il valore di scala delle unità visualizzate per l'asse di valore. Lettura/scrittura [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Rappresenta il formato dell'asse. Sola lettura [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Determina se un asse ha un titolo visibile. Lettura/scrittura Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Indica se l'unità principale dell'asse è assegnata automaticamente. Lettura/scrittura Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Indica se il valore massimo è assegnato automaticamente. Lettura/scrittura Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Indica se l'unità secondaria dell'asse è assegnata automaticamente. Lettura/scrittura Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Indica se il valore minimo è assegnato automaticamente. Lettura/scrittura Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Specifica il valore del bin di overflow automatico. Se false: utilizzare la proprietà OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Specifica il valore di spaziatura automatica delle etichette dei tick. Se false: utilizzare la proprietà TickLabelSpacing. Lettura/scrittura Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Specifica il valore di spaziatura automatica dei tick. Se false: utilizzare la proprietà TickMarksSpacing. Lettura/scrittura Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Specifica il valore del bin di underflow automatico. Se false: utilizzare la proprietà UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Rappresenta se il tipo di scala dell'asse di valore è logaritmico o no. Lettura/scrittura Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Indica se il formato è collegato ai dati di origine. Lettura/scrittura Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Specifica se il bin di overflow è applicato. Utilizzare IsAutomaticOverflowBin e OverflowBin per regolare il valore del bin di overflow. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Rappresenta se MS PowerPoint traccia i punti dati dall'ultimo al primo. Lettura/scrittura Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Specifica se il bin di underflow è applicato. Utilizzare IsAutomaticUnderflowBin e UnderflowBin per regolare il valore del bin di underflow. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Rappresenta se l'asse è visibile. Lettura/scrittura Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Specifica la distanza delle etichette dall'asse. Applicato all'asse di categoria o di data. Il valore deve essere compreso tra 0% e 1000%. Lettura/scrittura UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Rappresenta la base logaritmica. Il valore predefinito è 10. Lettura/scrittura Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Rappresenta il formato delle linee della griglia principale su un asse del grafico. Sola lettura [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Rappresenta il tipo di segno di tick principale per l'asse specificato. Lettura/scrittura [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Rappresenta le unità principali per l'asse di data o di valore. Lettura/scrittura Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Rappresenta la scala dell'unità principale per l'asse di data. Lettura/scrittura [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Rappresenta il valore massimo sull'asse di valore. Lettura/scrittura Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Rappresenta il formato delle linee della griglia secondaria su un asse del grafico. Sola lettura [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Rappresenta il tipo di segno di tick secondario per l'asse specificato. Lettura/scrittura [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Rappresenta le unità secondarie per l'asse di data o di valore. Lettura/scrittura Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Rappresenta la scala dell'unità principale per l'asse di data. Lettura/scrittura [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Rappresenta il valore minimo sull'asse di valore. Lettura/scrittura Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Rappresenta la stringa di formato per le Etichette dell'Asse. Lettura/scrittura String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Specifica il numero di bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByNumberOfBins. Applicato agli assi di categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Specifica il valore personalizzato del bin di overflow. Applicato quando la proprietà IsAutomaticOverflowBin è impostata su false e la proprietà IsOverflowBin è true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Rappresenta la posizione dell'asse. Lettura/scrittura [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Rappresenta se le linee della griglia principale sono visualizzate. Sola lettura Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Rappresenta se le linee della griglia secondaria sono visualizzate. Sola lettura Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Rappresenta la posizione delle etichette dei segni di tick sull'asse specificato. Lettura/scrittura [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Rappresenta l'angolo di rotazione delle etichette dei tick. Lettura/scrittura Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Specifica quante etichette dei tick saltare tra un'etichetta disegnata. Lettura/scrittura UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Specifica quanti segni di tick devono essere saltati prima di disegnare il successivo. Applicato all'asse di categoria o di serie. Lettura/scrittura UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Ottiene il titolo dell'asse. Sola lettura [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Specifica il valore personalizzato del bin di underflow. Applicato quando la proprietà IsAutomaticUnderflowBin è impostata su false e la proprietà IsUnderflowBin è true. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Imposta la proprietà IAxis.CategoryAxisType con un valore determinato automaticamente in base ai dati dell'asse. |

### Vedi anche

* interfaccia [IFormattedTextContainer](../iformattedtextcontainer)
* spazio dei nomi [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->