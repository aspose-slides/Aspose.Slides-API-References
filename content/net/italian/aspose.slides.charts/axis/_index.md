---
title: Axis
second_title: Aspose.Sildes per .NET Riferimento API
description: Incapsula l'oggetto che rappresenta l'asse di un grafico.
type: docs
weight: 1160
url: /it/aspose.slides.charts/axis/
---
## Axis classe
Incapsula l'oggetto che rappresenta l'asse di un grafico.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Specifica l'unità principale effettiva dell'asse. Chiamare il metodo IChart.ValidateChartLayout() in precedenza per ottenere il valore effettivo. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Specifica la scala dell'unità principale effettiva dell'asse. Chiamare il metodo IChart.ValidateChartLayout() in precedenza per ottenere il valore effettivo. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Specifica il valore massimo effettivo sull'asse. Chiamare il metodo IChart.ValidateChartLayout() in precedenza per ottenere il valore effettivo. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Specifica l'unità secondaria effettiva dell'asse. Chiamare il metodo IChart.ValidateChartLayout() in precedenza per ottenere il valore effettivo. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Specifica la scala dell'unità secondaria effettiva dell'asse. Chiamare il metodo IChart.ValidateChartLayout() in precedenza per ottenere il valore effettivo. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Specifica il valore minimo effettivo sull'asse. Chiamare il metodo IChart.ValidateChartLayout() in precedenza per ottenere il valore effettivo. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Rappresenta il tipo di aggregazione dell'asse di categoria (binning). Applicato alla categoria. Usato solo con serie Histogram o HistogramPareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Indica se l'asse dei valori attraversa l'asse di categoria tra le categorie. Questa proprietà si applica solo agli assi di categoria e non si applica ai grafici 3-D. Lettura/scrittura Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Specifica la più piccola unità di tempo rappresentata sull'asse data. Lettura/scrittura [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Specifica la larghezza del bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByBinWidth. Applicato agli assi di categoria. Usato solo con serie Histogram o HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Specifica il tipo dell'asse di categoria. Lettura/scrittura [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Restituisce il grafico padre. Solo lettura [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa. Lettura/scrittura Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Rappresenta il CrossType sull'asse specificato dove l'altro asse lo attraversa. Lettura/scrittura [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Specifica il valore di scala delle unità di visualizzazione per l'asse dei valori. Lettura/scrittura [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Rappresenta il formato dell'asse. Solo lettura [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Determina se un asse ha un titolo visibile. Lettura/scrittura Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Indica se l'unità principale dell'asse è assegnata automaticamente. Lettura/scrittura Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Indica se il valore massimo è assegnato automaticamente. Lettura/scrittura Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Indica se l'unità secondaria dell'asse è assegnata automaticamente. Lettura/scrittura Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Indica se il valore minimo è assegnato automaticamente. Lettura/scrittura Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Specifica il valore del bin di overflow automatico. Se false: utilizzare la proprietà OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Specifica il valore di spaziatura automatico delle etichette dei tick. Se false: utilizzare la proprietà TickLabelSpacing. Lettura/scrittura Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Specifica il valore di spaziatura automatico dei segni di tick. Se false: utilizzare la proprietà TickMarksSpacing. Lettura/scrittura Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Specifica il valore del bin di underflow automatico. Se false: utilizzare la proprietà UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Indica se il tipo di scala dell'asse dei valori è logaritmico o meno. Lettura/scrittura Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Indica se il formato è collegato ai dati sorgente. Lettura/scrittura Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Specifica se il bin di overflow è applicato. Utilizzare IsAutomaticOverflowBin e OverflowBin per regolare il valore del bin di overflow. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Indica se MS PowerPoint traccia i punti dati dall'ultimo al primo. Lettura/scrittura Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Specifica se il bin di underflow è applicato. Utilizzare IsAutomaticUnderflowBin e UnderflowBin per regolare il valore del bin di underflow. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Indica se l'asse è visibile. Lettura/scrittura Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Specifica la distanza delle etichette dall'asse. Applicato all'asse di categoria o data. Il valore deve essere compreso tra 0% e 1000%. Lettura/scrittura UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Rappresenta la base logaritmica. Il valore predefinito è 10. Lettura/scrittura Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Rappresenta il formato delle linee di griglia principali su un asse del grafico. Solo lettura [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Rappresenta il tipo di segno di tick principale per l'asse specificato. Lettura/scrittura [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Rappresenta le unità principali per l'asse data o valore. Lettura/scrittura Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Rappresenta la scala dell'unità principale per l'asse data. Lettura/scrittura [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Rappresenta il valore massimo sull'asse dei valori. Lettura/scrittura Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Rappresenta il formato delle linee di griglia secondarie su un asse del grafico. Solo lettura [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Rappresenta il tipo di segno di tick secondario per l'asse specificato. Lettura/scrittura [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Rappresenta le unità secondarie per l'asse data o valore. Lettura/scrittura Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Rappresenta la scala dell'unità principale per l'asse data. Lettura/scrittura [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Rappresenta il valore minimo sull'asse dei valori. Lettura/scrittura Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Rappresenta la stringa di formato per le Etichette dell'Asse. Lettura/scrittura String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Specifica il numero di bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByNumberOfBins. Applicato agli assi di categoria. Usato solo con serie Histogram o HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Specifica il valore personalizzato del bin di overflow. Applicato quando la proprietà IsAutomaticOverflowBin è impostata su false e la proprietà IsOverflowBin è true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Rappresenta la posizione dell'asse. Lettura/scrittura [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Per nascondere la griglia principale impostare MajorGridLinesFormat.Line.FillFormat.FillType su FillType.NoFill. Solo lettura Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Per nascondere la griglia secondaria impostare MinorGridLinesFormat.Line.FillFormat.FillType su FillType.NoFill. Solo lettura Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Rappresenta il formato del testo. Solo lettura [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Rappresenta la posizione delle etichette dei segni di tick sull'asse specificato. Lettura/scrittura [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Rappresenta l'angolo di rotazione delle etichette dei tick. Lettura/scrittura Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Specifica quante etichette di tick saltare tra le etichette disegnate. Applicato all'asse di categoria o di serie. Lettura/scrittura UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Specifica quanti segni di tick devono essere saltati prima di disegnare il successivo. Applicato all'asse di categoria o di serie. Lettura/scrittura UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Restituisce il titolo dell'asse. Solo lettura [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Specifica il valore personalizzato del bin di underflow. Applicato quando la proprietà IsAutomaticUnderflowBin è impostata su false e la proprietà IsUnderflowBin è true. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Imposta la proprietà IAxis.CategoryAxisType con un valore determinato automaticamente in base ai dati dell'asse. |

### Vedi anche

* classe [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* classe [AxesManager](../axesmanager)
* interfaccia [IAxis](../iaxis)
* spazio dei nomi [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->