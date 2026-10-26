---
title: IChartSeriesGroup
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta un gruppo di serie.
type: docs
weight: 1950
url: /it/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup interfaccia

Rappresenta un gruppo di serie.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Consente di ottenere l’interfaccia base IChartComponent. Sola lettura [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Specifica come i valori delle dimensioni delle bolle sono rappresentati nel grafico a bolle. Lettura/scrittura [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Specifica il fattore di scala per il grafico a bolle (può essere tra lo 0% e il 300% della dimensione predefinita). Lettura/scrittura Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Specifica la dimensione del foro in un grafico a ciambella (può essere tra il 10% e il 90% della dimensione dell’area del grafico). Lettura/scrittura Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Ottiene o imposta l’angolo della prima fetta di torta o ciambella, in gradi (orario dall’alto, da 0 a 360 gradi). Lettura/scrittura UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Restituisce o imposta la distanza, in percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Lettura/scrittura UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Specifica lo spazio tra i raggruppamenti di barre o colonne, in percentuale della larghezza della barra o della colonna. Lettura/scrittura UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Vero se il grafico ha linee di serie. Applicato a grafici a barre impilate e OfPie. Lettura/scrittura Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Specifica il formato HiLowLines. HiLowLines è applicato ai tipi di grafico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Specifica che ogni marcatore dati nella serie ha un colore diverso. Lettura/scrittura Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Ottiene l’elemento all’indice specificato. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Specifica quanto barre e colonne devono sovrapporsi nei grafici 2-D, in percentuale (da -100% a 100%). - -100%: Spaziatura massima (le barre sono completamente separate). - 0%: Le barre sono affiancate senza sovrapposizione né spaziatura. - 100%: Sovrapposizione massima (le barre si sovrappongono completamente). Questa proprietà è lettura/scrittura SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Lettura/scrittura [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Le informazioni di divisione personalizzata per un grafico pie-of-pie o bar-of-pie con divisione personalizzata. Contiene i punti dati che devono essere disegnati nella seconda torta o barra. Sola lettura [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Specifica un valore da usare per determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. È usato insieme alla proprietà PieSplitBy. Lettura/scrittura Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Indica se le serie di questo gruppo sono tracciate sull’asse secondario. Sola lettura Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Specifica la dimensione della seconda torta o barra di un grafico pie-of-pie o bar-of-pie, in percentuale della dimensione della prima torta (può essere tra il 5% e il 200%). Lettura/scrittura UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Restituisce una collezione solo lettura di serie di grafico. Sola lettura [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Restituisce il tipo di questo gruppo di serie. Sola lettura [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Fornisce l’accesso a barre up/down di un grafico a linee o a candela. Sola lettura [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Osservazioni

1) Vedere il riepilogo e le osservazioni per la classe **ChartSeriesGroupCollection** e l’enumerazione **CombinableSeriesTypesGroup**.  
2) Un gruppo di serie contiene alcune **proprietà del gruppo di serie** comuni a ciascuna serie nel gruppo. Le **proprietà del gruppo di serie** nella classe **ChartSeriesGroup** sono lettura/scrittura. Ognuna delle **proprietà del gruppo di serie** può avere una proiezione sola lettura nella classe **ChartSeries**.

### Vedi anche

* interfaccia [IChartComponent](../ichartcomponent)
* spazio dei nomi [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->