---
title: ChartSeriesGroup
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta un gruppo di serie.
type: docs
weight: 1440
url: /it/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup classe

Rappresenta un gruppo di serie.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Specifica come i valori della dimensione delle bolle sono rappresentati nel grafico a bolle. Lettura/Scrittura [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Specifica il fattore di scala per il grafico a bolle (può essere compreso tra lo 0% e il 300% della dimensione predefinita). Lettura/Scrittura Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Restituisce il grafico genitore. Sola lettura [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Specifica la dimensione del foro in un grafico a ciambella (può essere compresa tra lo 0% e il 90% della dimensione dell'area del tracciato). Lettura/Scrittura Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Ottiene o imposta l'angolo della prima fetta di un grafico a torta o a ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). Lettura/Scrittura UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Restituisce o imposta la distanza, espressa in percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Lettura/Scrittura UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Specifica lo spazio tra i raggruppamenti di barre o colonne, espresso in percentuale della larghezza della barra o colonna. Lettura/Scrittura UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True se il grafico ha linee di serie. Applicato a barre impilate e grafici OfPie. Lettura/Scrittura Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Specifica il formato HiLowLines. HiLowLines è applicato con i tipi di grafico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Specifica che ogni marcatore di dati nella serie ha un colore diverso. Lettura/Scrittura Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Ottiene l'elemento all'indice specificato. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Specifica quanto le barre e le colonne devono sovrapporsi nei grafici 2D, in percentuale (da -100% a 100%). - -100%: Spaziatura massima (le barre sono completamente separate). - 0%: Le barre sono affiancate senza sovrapposizione né spaziatura. - 100%: Sovrapposizione massima (le barre si sovrappongono completamente). Questa proprietà è Lettura/Scrittura SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Specifica come determinare quali punti dati si trovano nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Lettura/Scrittura [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Le informazioni di suddivisione personalizzata per un grafico pie-of-pie o bar-of-pie con suddivisione personalizzata. Contiene i punti dati che devono essere disegnati nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Sola lettura [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Specifica un valore da utilizzare per determinare quali punti dati si trovano nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. È usato insieme alla proprietà PieSplitBy. Lettura/Scrittura Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Indica se le serie di questo gruppo sono tracciate su un asse secondario. Sola lettura Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Specifica la dimensione della seconda torta o barra di un grafico pie-of-pie o bar-of-pie, come percentuale della dimensione della prima torta (può essere compresa tra il 5% e il 200%). Lettura/Scrittura UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Restituisce una collezione di serie. Sola lettura [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Restituisce un tipo di questo gruppo di serie. Sola lettura [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Fornisce l'accesso alle barre up/down di un grafico a linee o a barre. Sola lettura [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Osservazioni

1) Vedi il riepilogo e le osservazioni per la classe ChartSeriesGroupCollection e l'enumerazione CombinableSeriesTypesGroup. 2) Il gruppo di serie contiene alcune proprietà di serie che sono comuni a ciascuna serie nel gruppo ("series group properties"). Le "series group properties" nella classe ChartSeriesGroup sono Lettura/Scrittura. Ognuna delle "series group properties" può avere una proiezione Sola lettura nella classe ChartSeries.

### Vedi anche

* interfaccia [IChartSeriesGroup](../ichartseriesgroup)
* spazio dei nomi [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->