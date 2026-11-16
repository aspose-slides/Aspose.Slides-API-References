---
title: ChartSeries
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta una serie di grafico.
type: docs
weight: 1450
url: /it/aspose.slides.charts/chartseries/
---
## ChartSeries classe

Rappresenta una serie di grafico.

```csharp
public class ChartSeries : IChartSeries
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Specifica la forma di una serie di un grafico a barre 3-D. La modifica del valore di questa proprietà può causare la modifica automatica del Type della serie. Lettura/scrittura [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Specifica come i valori delle dimensioni delle bolle sono rappresentati nel grafico a bolle. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è la proiezione della proprietà di gruppo appropriata. Pertanto questa proprietà è a sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo di serie padre. Usa la proprietà ParentSeriesGroup.BubbleSizeRepresentation Lettura/scrittura per modificare il valore. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percento della dimensione predefinita). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è la proiezione della proprietà di gruppo appropriata. Pertanto questa proprietà è a sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo di serie padre. Usa la proprietà ParentSeriesGroup.BubbleSizeScale Lettura/scrittura per modificare il valore. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Restituisce il grafico padre. Sola lettura [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Restituisce la collezione di punti dati di questa serie. Sola lettura [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Specifica la dimensione del foro in un grafico a ciambella (può essere tra il 10 e il 90 percento della dimensione dell'area del grafico). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è la proiezione della proprietà di gruppo appropriata. Pertanto questa proprietà è a sola lettura. Byte a sola lettura. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Rappresenta le ErrorBars della serie con direzione X. Le ErrorBars con direzione X sono disponibili per le serie di tipo area, barra, scatter e bubble. Per altri tipi di grafico questa proprietà restituisce null (inclusi i grafici 3D). In caso di valori personalizzati usa la collezione DataPoints per specificare il valore (con la proprietà [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Sola lettura [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Rappresenta le ErrorBars della serie con direzione Y. Le ErrorBars con direzione Y sono disponibili per le serie di tipo area, barra, line, scatter e bubble. Per altri tipi di grafico questa proprietà restituisce null (inclusi i grafici 3D). In caso di valori personalizzati usa la collezione DataPoints per specificare il valore (con la proprietà [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Sola lettura [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | La distanza di una fetta di torta aperta dal centro del grafico a torta è espressa come percentuale del diametro della torta. Lettura/scrittura Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Specifica l'angolo della prima fetta di un grafico a torta o a ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è la proiezione della proprietà di gruppo appropriata. Pertanto questa proprietà è a sola lettura. Sola lettura UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Restituisce il formato di una serie. Sola lettura [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è la proiezione della proprietà di gruppo appropriata. Pertanto questa proprietà è a sola lettura. Sola lettura Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Specifica lo spazio tra i raggruppamenti di barre o colonne, come percentuale della larghezza della barra o colonna. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è la proiezione della proprietà di gruppo appropriata. Pertanto questa proprietà è a sola lettura. Sola lettura Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Determina se ci sono linee di serie per questa serie e serie correlate. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è la proiezione della proprietà di gruppo appropriata. Pertanto questa proprietà è a sola lettura. Sola lettura Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Determina se un grafico a linee o a barre ha barre su/giù. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è la proiezione della proprietà di gruppo appropriata. Pertanto questa proprietà è a sola lettura. Sola lettura Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Specifica il colore solido invertito per la serie. Per applicare l'impostazione colore imposta il FillType del formato della serie a FillType.Solid. Lettura/scrittura [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Specifica che la serie a barre, colonne o bolle inverta i colori se il valore è negativo. Lettura/scrittura Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Specifica che ogni marcatore dati nella serie ha un colore diverso. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è la proiezione della proprietà di gruppo appropriata. Pertanto questa proprietà è a sola lettura. Sola lettura Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Restituisce le Labels di una serie. Sola lettura [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Marker. Sola lettura [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Restituisce il nome della serie. Sola lettura [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Lettura/scrittura String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Lettura/scrittura String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Lettura/scrittura String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Lettura/scrittura String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Restituisce l'ordine di una serie. Lettura/scrittura Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Specifica di quanto le barre e le colonne si sovrappongono nei grafici 2-D, come percentuale (da -100% a 100%). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre. È una proiezione della proprietà appropriata nel gruppo di serie padre, quindi questa proprietà è a sola lettura. Per modificare il valore, usa la proprietà !:ParentSeriesGroup.Overlap Lettura/scrittura. Sola lettura SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Rappresenta il layout delle etichette di categoria padre. Si applica solo ai grafici Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Sola lettura [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è la proiezione della proprietà di gruppo appropriata. Sola lettura [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Le informazioni di divisione personalizzata per un grafico pie-of-pie o bar-of-pie con divisione personalizzata. Contiene punti dati che devono essere disegnati nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è la proiezione della proprietà di gruppo appropriata. Sola lettura [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Specifica un valore da utilizzare per determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. È usato insieme alla proprietà PieSplitBy. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è la proiezione della proprietà di gruppo appropriata. Pertanto questa proprietà è a sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo di serie padre. Usa la proprietà ParentSeriesGroup.PieSplitPosition Lettura/scrittura per modificare il valore. Sola lettura Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Indica se questa serie è tracciata sull'asse secondario. Lettura/scrittura Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Rappresenta il metodo quartile. Si applica solo ai grafici BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Rappresenta la voce della leggenda correlata a questa serie. Sola lettura [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Specifica la dimensione della seconda torta o barra di un grafico pie-of-pie o bar-of-pie, come percentuale della dimensione della prima torta (può essere tra 5 e 200 percento). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è la proiezione della proprietà di gruppo appropriata. Sola lettura UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Rappresenta le linee di collegamento. Si applica solo ai grafici Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Rappresenta i punti interni. Vero se i punti interni sono mostrati nel grafico BoxAndWhisker. Si applica solo ai grafici BoxAndWhisker. Lettura/scrittura Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Rappresenta la linea della media. Vero se la linea della media è mostrata nel grafico BoxAndWhisker. Si applica solo ai grafici BoxAndWhisker. Lettura/scrittura Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Rappresenta i marcatori della media. Vero se i marcatori della media sono mostrati nel grafico BoxAndWhisker. Si applica solo ai grafici BoxAndWhisker. Lettura/scrittura Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Rappresenta i punti anomali. Vero se i punti anomali sono mostrati nel grafico BoxAndWhisker. Si applica solo ai grafici BoxAndWhisker. Lettura/scrittura Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Rappresenta l'ammorbimento della curva. Vero se l'ammorbimento della curva è attivato per il grafico a linee o a dispersione. Si applica solo ai grafici a linee e a dispersione collegati da linee. Lettura/scrittura Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Collezione di linee di tendenza della serie. Sola lettura [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Restituisce il tipo di questa serie. Lettura/scrittura [`ChartType`](../charttype). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Restituisce un colore automatico della serie basato sull'indice della serie e sullo stile del grafico. Questo colore è usato per impostazione predefinita se FillType è uguale a NotDefined. |

### Vedi anche

* interfaccia [IChartSeries](../ichartseries)
* spazio dei nomi [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->