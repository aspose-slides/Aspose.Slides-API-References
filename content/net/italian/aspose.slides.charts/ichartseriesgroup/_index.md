---
title: IChartSeriesGroup
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta un gruppo di serie.
type: docs
weight: 1930
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
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Consente di ottenere l'interfaccia base IChartComponent. Sola lettura [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Specifica come i valori di dimensione delle bolle sono rappresentati nel grafico a bolle. Lettura/Scrittura [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percento della dimensione predefinita). Lettura/Scrittura Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Specifica la dimensione del foro in un grafico a ciambella (può essere tra 10 e 90 percento della dimensione dell'area del grafico). Lettura/Scrittura Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Ottiene o imposta l'angolo della prima fetta di un grafico a torta o a ciambella, in gradi (orario dal vertice, da 0 a 360 gradi). Lettura/Scrittura UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Lettura/Scrittura UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Specifica lo spazio tra i gruppi di barre o colonne, come percentuale della larghezza della barra o della colonna. Lettura/Scrittura UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | True se il grafico ha linee di serie. Applicato ai grafici a barre impilate e OfPie. Lettura/Scrittura Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Specifica il formato HiLowLines. HiLowLines applicato con i tipi di grafico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Specifica che ogni marcatore dati nella serie ha un colore diverso. Lettura/Scrittura Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Ottiene l'elemento all'indice specificato. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Specifica quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100 % a 100 %). -100 %: Spaziatura massima (le barre sono completamente separate). 0 %: Le barre sono affiancate senza sovrapposizione né spaziatura. 100 %: Sovrapposizione massima (le barre si sovrappongono completamente). Questa proprietà è Lettura/Scrittura SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico di tipo torta-di-torta o barra-di-torta. Lettura/Scrittura [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Le informazioni di divisione personalizzata per un grafico torta-di-torta o barra-di-torta con divisione personalizzata. Contiene i punti dati da disegnare nella seconda torta o barra. Sola lettura [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Specifica un valore da utilizzare per determinare quali punti dati sono nella seconda torta o barra in un grafico torta-di-torta o barra-di-torta. È usato insieme alla proprietà PieSplitBy. Lettura/Scrittura Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Indica se le serie di questo gruppo sono tracciate su un asse secondario. Sola lettura Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Specifica la dimensione della seconda torta o barra di un grafico torta-di-torta o barra-di-torta, come percentuale della dimensione della prima torta (può essere tra 5 e 200 percento). Lettura/Scrittura UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Restituisce una raccolta di sola lettura delle serie del grafico. Sola lettura [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Restituisce il tipo di questo gruppo di serie. Sola lettura [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Fornisce accesso a barre su/giù di un grafico a linee o a barre. Sola lettura [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Osservazioni

1) Vedere il riepilogo e le osservazioni per la classe ChartSeriesGroupCollection e per l'enumerazione CombinableSeriesTypesGroup. 2) Un gruppo di serie contiene alcune proprietà delle serie che sono comuni a ogni serie nel gruppo (“proprietà del gruppo di serie”). Le “proprietà del gruppo di serie” nella classe ChartSeriesGroup sono lettura/scrittura. Ognuna delle “proprietà del gruppo di serie” può avere una proiezione sola lettura nella classe ChartSeries.

### Vedi anche

* interfaccia [IChartComponent](../ichartcomponent)
* spazio dei nomi [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->