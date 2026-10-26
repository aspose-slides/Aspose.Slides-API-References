---
title: IAxis
second_title: Riferimento API di Aspose.Sildes per .NET
description: Incapsula l'oggetto che rappresenta l'asse di un grafico.
type: docs
weight: 1710
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
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Specifica l'unità maggiore effettiva dell'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore reale. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Specifica la scala dell'unità maggiore effettiva dell'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore reale. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Specifica il valore massimo effettivo sull'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore reale. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Specifica l'unità minore effettiva dell'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore reale. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Specifica la scala dell'unità minore effettiva dell'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore reale. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Specifica il valore minimo effettivo sull'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore reale. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Rappresenta il tipo di aggregazione dell'asse di categoria (binning). Applicato alla categoria. Usato solo con le serie Histogram o HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Consente di ottenere l'interfaccia base IFormattedTextContainer. Solo lettura [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Indica se l'asse dei valori attraversa l'asse di categoria tra le categorie. Questa proprietà si applica solo agli assi di categoria e non ai grafici 3-D. Lettura/Scrittura Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Specifica l'unità di tempo più piccola rappresentata sull'asse delle date. Lettura/Scrittura [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Specifica la larghezza del bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByBinWidth. Applicato agli assi di categoria. Usato solo con le serie Histogram o HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Specifica il tipo di asse di categoria. Lettura/Scrittura [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa. Lettura/Scrittura Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Rappresenta il CrossType sull'asse specificato dove l'altro asse lo attraversa. Lettura/Scrittura [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Specifica il valore di scala delle unità di visualizzazione per l'asse dei valori. Lettura/Scrittura [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Rappresenta il formato dell'asse. Solo lettura [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Determina se un asse ha un titolo visibile. Lettura/Scrittura Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Indica se l'unità maggiore dell'asse è assegnata automaticamente. Lettura/Scrittura Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Indica se il valore massimo è assegnato automaticamente. Lettura/Scrittura Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Indica se l'unità minore dell'asse è assegnata automaticamente. Lettura/Scrittura Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Indica se il valore minimo è assegnato automaticamente. Lettura/Scrittura Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Specifica il valore automatico del bin di overflow. Se false: usa la proprietà OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Specifica il valore automatico della spaziatura delle etichette dei tick. Se false: usa la proprietà TickLabelSpacing. Lettura/Scrittura Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Specifica il valore automatico della spaziatura dei tick marks. Se false: usa la proprietà TickMarksSpacing. Lettura/Scrittura Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Specifica il valore automatico del bin di underflow. Se false: usa la proprietà UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Rappresenta se il tipo di scala dell'asse dei valori è logaritmico o no. Lettura/Scrittura Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Indica se il formato è collegato ai dati di origine. Lettura/Scrittura Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Specifica se è applicato il bin di overflow. Usa IsAutomaticOverflowBin e OverflowBin per regolare il valore del bin di overflow. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Rappresenta se MS PowerPoint traccia i punti dati dall'ultimo al primo. Lettura/Scrittura Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Specifica se è applicato il bin di underflow. Usa IsAutomaticUnderflowBin e UnderflowBin per regolare il valore del bin di underflow. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Rappresenta se l'asse è visibile. Lettura/Scrittura Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Specifica la distanza delle etichette dall'asse. Applicato all'asse di categoria o di data. Il valore deve essere compreso tra 0% e 1000%. Lettura/Scrittura UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Rappresenta la base logaritmica. Il valore predefinito è 10. Lettura/Scrittura Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Rappresenta il formato delle linee della griglia principale su un asse del grafico. Solo lettura [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Rappresenta il tipo di segno di tick principale per l'asse specificato. Lettura/Scrittura [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Rappresenta le unità principali per l'asse di data o valore. Lettura/Scrittura Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Rappresenta la scala dell'unità principale per l'asse di data. Lettura/Scrittura [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Rappresenta il valore massimo sull'asse dei valori. Lettura/Scrittura Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Rappresenta il formato delle linee della griglia minore su un asse del grafico. Solo lettura [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Rappresenta il tipo di segno di tick minore per l'asse specificato. Lettura/Scrittura [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Rappresenta le unità minori per l'asse di data o valore. Lettura/Scrittura Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Rappresenta la scala dell'unità principale per l'asse di data. Lettura/Scrittura [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Rappresenta il valore minimo sull'asse dei valori. Lettura/Scrittura Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Rappresenta la stringa di formato per le Etichette dell'Asse. Lettura/Scrittura String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Specifica il numero di bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByNumberOfBins. Applicato agli assi di categoria. Usato solo con le serie Histogram o HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Specifica il valore personalizzato del bin di overflow. Applicato quando la proprietà IsAutomaticOverflowBin è impostata su false e la proprietà IsOverflowBin è true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Rappresenta la posizione dell'asse. Lettura/Scrittura [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Rappresenta se le linee della griglia principale sono mostrate. Solo lettura Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Rappresenta se le linee della griglia minore sono mostrate. Solo lettura Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Rappresenta la posizione delle etichette dei segni di tick sull'asse specificato. Lettura/Scrittura [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Rappresenta l'angolo di rotazione delle etichette dei tick. Lettura/Scrittura Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Specifica quanti etichette dei tick saltare tra le etichette disegnate. Lettura/Scrittura UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Specifica quanti segni di tick devono essere saltati prima che il successivo venga disegnato. Applicato all'asse di categoria o di serie. Lettura/Scrittura UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Ottiene il titolo dell'asse. Solo lettura [`IChartTitle`](../icharttitle). |
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