---
title: IAxis
second_title: Riferimento API Aspose.Sildes per .NET
description: Incapsula l'oggetto che rappresenta l'asse di un grafico.
type: docs
weight: 1720
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
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Specifica l'unità principale effettiva dell'asse. Chiamare il metodo IChart.ValidateChartLayout() in precedenza per ottenere il valore effettivo. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Specifica la scala dell'unità principale effettiva dell'asse. Chiamare il metodo IChart.ValidateChartLayout() in precedenza per ottenere il valore effettivo. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Specifica il valore massimo effettivo sull'asse. Chiamare il metodo IChart.ValidateChartLayout() in precedenza per ottenere il valore effettivo. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Specifica l'unità secondaria effettiva dell'asse. Chiamare il metodo IChart.ValidateChartLayout() in precedenza per ottenere il valore effettivo. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Specifica la scala dell'unità secondaria effettiva dell'asse. Chiamare il metodo IChart.ValidateChartLayout() in precedenza per ottenere il valore effettivo. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Specifica il valore minimo effettivo sull'asse. Chiamare il metodo IChart.ValidateChartLayout() in precedenza per ottenere il valore effettivo. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Rappresenta il tipo di aggregazione dell'asse di categoria (raggruppamento). Applicato alla categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Permette di ottenere l'interfaccia base IFormattedTextContainer. Solo lettura [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Rappresenta se l'asse dei valori attraversa l'asse di categoria tra le categorie. Questa proprietà si applica solo agli assi di categoria e non si applica ai grafici 3-D. Lettura/scrittura Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Specifica l'unità di tempo più piccola che è rappresentata sull'asse delle date. Lettura/scrittura [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Specifica la larghezza del contenitore quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByBinWidth. Applicato agli assi di categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Specifica il tipo dell'asse di categoria. Lettura/scrittura [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa. Lettura/scrittura Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Rappresenta il CrossType sull'asse specificato dove l'altro asse lo attraversa. Lettura/scrittura [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Specifica il valore di scala delle unità di visualizzazione per l'asse dei valori. Lettura/scrittura [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Rappresenta il formato dell'asse. Solo lettura [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Determina se un asse ha un titolo visibile. Lettura/scrittura Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Indica se l'unità principale dell'asse è assegnata automaticamente. Lettura/scrittura Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Indica se il valore massimo è assegnato automaticamente. Lettura/scrittura Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Indica se l'unità secondaria dell'asse è assegnata automaticamente. Lettura/scrittura Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Indica se il valore minimo è assegnato automaticamente. Lettura/scrittura Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Specifica il valore automatico del contenitore di overflow. Se false: utilizzare la proprietà OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Specifica il valore automatico della spaziatura delle etichette di graduazione. Se false: utilizzare la proprietà TickLabelSpacing. Lettura/scrittura Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Specifica il valore automatico della spaziatura dei segni di graduazione. Se false: utilizzare la proprietà TickMarksSpacing. Lettura/scrittura Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Specifica il valore automatico del contenitore di underflow. Se false: utilizzare la proprietà UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Rappresenta se il tipo di scala dell'asse dei valori è logaritmico o meno. Lettura/scrittura Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Indica se il formato è collegato ai dati di origine. Lettura/scrittura Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Specifica se il contenitore di overflow è applicato. Utilizzare IsAutomaticOverflowBin e OverflowBin per regolare il valore del contenitore di overflow. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Rappresenta se MS PowerPoint traccia i punti dati dall'ultimo al primo. Lettura/scrittura Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Specifica se il contenitore di underflow è applicato. Utilizzare IsAutomaticUnderflowBin e UnderflowBin per regolare il valore del contenitore di underflow. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Rappresenta se l'asse è visibile. Lettura/scrittura Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Specifica la distanza delle etichette dall'asse. Applicato all'asse di categoria o data. Il valore deve essere compreso tra 0% e 1000%. Lettura/scrittura UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Rappresenta la base logaritmica. Il valore predefinito è 10. Lettura/scrittura Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Rappresenta il formato delle linee di griglia principali su un asse del grafico. Solo lettura [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Rappresenta il tipo di segno di graduazione principale per l'asse specificato. Lettura/scrittura [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Rappresenta le unità principali per l'asse data o valore. Lettura/scrittura Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Rappresenta la scala dell'unità principale per l'asse data. Lettura/scrittura [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Rappresenta il valore massimo sull'asse dei valori. Lettura/scrittura Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Rappresenta il formato delle linee di griglia secondarie su un asse del grafico. Solo lettura [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Rappresenta il tipo di segno di graduazione secondario per l'asse specificato. Lettura/scrittura [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Rappresenta le unità secondarie per l'asse data o valore. Lettura/scrittura Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Rappresenta la scala dell'unità principale per l'asse data. Lettura/scrittura [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Rappresenta il valore minimo sull'asse dei valori. Lettura/scrittura Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Rappresenta la stringa di formato per le etichette dell'asse. Lettura/scrittura String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Specifica il numero di contenitori quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByNumberOfBins. Applicato agli assi di categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Specifica il valore personalizzato del contenitore di overflow. Applicato quando la proprietà IsAutomaticOverflowBin è impostata su false e la proprietà IsOverflowBin è true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Rappresenta la posizione dell'asse. Lettura/scrittura [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Rappresenta se le linee di griglia principali sono visualizzate. Solo lettura Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Rappresenta se le linee di griglia secondarie sono visualizzate. Solo lettura Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Rappresenta la posizione delle etichette dei segni di graduazione sull'asse specificato. Lettura/scrittura [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Rappresenta l'angolo di rotazione delle etichette dei segni di graduazione. Lettura/scrittura Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Specifica quante etichette di segno saltare tra le etichette disegnate. Lettura/scrittura UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Specifica quanti segni di graduazione devono essere saltati prima che quello successivo venga disegnato. Applicato all'asse di categoria o serie. Lettura/scrittura UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Ottiene il titolo dell'asse. Solo lettura [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Specifica il valore personalizzato del contenitore di underflow. Applicato quando la proprietà IsAutomaticUnderflowBin è impostata su false e la proprietà IsUnderflowBin è true. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Imposta la proprietà IAxis.CategoryAxisType con un valore determinato automaticamente in base ai dati dell'asse. |

### Vedi anche

* interfaccia [IFormattedTextContainer](../iformattedtextcontainer)
* spazio dei nomi [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->