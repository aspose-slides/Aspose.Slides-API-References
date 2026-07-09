---
title: ChartSeriesGroup
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta un gruppo di serie.
type: docs
weight: 1460
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
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Specifica come i valori delle dimensioni delle bolle sono rappresentati nel grafico a bolle. Lettura/scrittura [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Specifica il fattore di scala per il grafico a bolle (può essere compreso tra 0 e 300 percento della dimensione predefinita). Lettura/scrittura Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Restituisce il grafico principale. Sola lettura [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Specifica la dimensione del foro in un grafico a ciambella (può essere compresa tra 0 e 90 percento della dimensione dell'area del tracciato). Lettura/scrittura Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Ottiene o imposta l'angolo della prima fetta di un grafico a torta o a ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). Lettura/scrittura UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Restituisce o imposta la distanza, espressa in percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Lettura/scrittura UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Specifica lo spazio tra i raggruppamenti di barre o colonne, espresso in percentuale della larghezza della barra o colonna. Lettura/scrittura UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Vero se il grafico ha linee di serie. Applicato a grafici a barre impilate e OfPie. Lettura/scrittura Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Specifica il formato HiLowLines. HiLowLines applicato con i tipi di grafico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Specifica che ogni marcatore dati nella serie ha un colore diverso. Lettura/scrittura Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Ottiene l'elemento all'indice specificato. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Specifica di quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, in percentuale (da -100% a 100%). - -100%: Spaziatura massima (le barre sono completamente separate). - 0%: Le barre sono poste affiancate senza sovrapposizione o spaziatura. - 100%: Sovrapposizione massima (le barre si sovrappongono completamente). Questa proprietà è Lettura/scrittura SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Lettura/scrittura [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Le informazioni di divisione personalizzata per un grafico pie-of-pie o bar-of-pie con una divisione personalizzata. Contiene i punti dati che devono essere disegnati nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Sola lettura [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Specifica un valore da utilizzare per determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Viene usato insieme alla proprietà PieSplitBy. Lettura/scrittura Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Indica se le serie di questo gruppo sono tracciate su un asse secondario. Sola lettura Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Specifica la dimensione della seconda torta o barra di un grafico pie-of-pie o bar-of-pie, in percentuale della dimensione della prima torta (può essere compresa tra 5 e 200 percento). Lettura/scrittura UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Restituisce una raccolta di serie. Sola lettura [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Restituisce il tipo di questo gruppo di serie. Sola lettura [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Fornisce l'accesso alle barre su/giù di un grafico a linee o a barre di tipo Stock. Sola lettura [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Osservazioni

1) Vedere il riepilogo e le osservazioni per la classe ChartSeriesGroupCollection e l'enumerazione CombinableSeriesTypesGroup. 2) Un gruppo di serie contiene alcune proprietà di serie comuni a ciascuna serie nel gruppo ("proprietà del gruppo di serie"). Le "proprietà del gruppo di serie" nella classe ChartSeriesGroup sono lettura/scrittura. Ognuna delle "proprietà del gruppo di serie" può avere una proiezione sola lettura nella classe ChartSeries.

### Vedi anche

* interfaccia [IChartSeriesGroup](../ichartseriesgroup)
* spazio dei nomi [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->