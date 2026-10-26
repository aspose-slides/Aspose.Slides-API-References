---
title: IChartSeriesGroup class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup classe

Rappresenta un gruppo di serie.

Il tipo IChartSeriesGroup espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`type`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/type/) | Restituisce un tipo di questo gruppo di serie.<br/>            Solo lettura [`CombinableSeriesTypesGroup`](/slides/python-net/it/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Indica se le serie di questo gruppo vengono tracciate su un asse secondario.<br/>            Solo lettura **bool**. |
| [`series`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/series/) | Restituisce una collezione di sola lettura di serie di grafico.<br/>            Solo lettura [`IChartSeriesReadonlyCollection`](/slides/python-net/it/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Fornisce accesso alle barre su/giù di un grafico Line- o Stock-chart.<br/>            Solo lettura [`IUpDownBarsManager`](/slides/python-net/it/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/gap_width/) | Specifica lo spazio tra i raggruppamenti di barre o colonne, come percentuale della larghezza della barra o colonna.<br/>            Lettura/scrittura **int**. |
| [`gap_depth`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Restituisce o imposta la distanza, come percentuale della larghezza del marker, tra le serie di dati in un grafico 3D.<br/>            Lettura/scrittura **int**. |
| [`first_slice_angle`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Ottiene o imposta l'angolo della prima fetta di un grafico a torta o ciambella, <br/>            in gradi (orario dall'alto, da 0 a 360 gradi).<br/>            Lettura/scrittura **int**. |
| [`is_color_varied`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Specifica che ogni marcatore di dati nella serie ha un colore diverso.<br/>            Lettura/scrittura **bool**. |
| [`has_series_lines`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Vero se il grafico ha linee di serie. Applicato ai grafici a barre impilate e OfPie.<br/>            Lettura/scrittura **bool**. |
| [`overlap`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/overlap/) | Specifica quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%).<br/>             - -100%: Spaziatura massima (le barre sono completamente separate).<br/>             - 0%: Le barre sono posizionate una accanto all'altra senza sovrapposizione o spaziatura.<br/>             - 100%: Sovrapposizione massima (le barre si sovrappongono completamente).<br/>             Questa proprietà è lettura/scrittura **int**. |
| [`second_pie_size`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Specifica la dimensione della seconda torta o barra di un grafico pie-of-pie o bar-of-pie, come percentuale della dimensione della prima torta (può essere tra 5 e 200 percenti).<br/>            Lettura/scrittura **int**. |
| [`pie_split_position`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Specifica un valore da utilizzare per determinare quali punti dati si trovano nella seconda torta o barra su un grafico pie-of-pie o bar-of-pie.<br/>            È usato insieme alla proprietà PieSplitBy.<br/>            Lettura/scrittura **float**. |
| [`pie_split_by`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Specifica come determinare quali punti dati sono nella seconda torta o barra su un grafico pie-of-pie o bar-of-pie.<br/>            Lettura/scrittura [`PieSplitType`](/slides/python-net/it/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Le informazioni di divisione personalizzata per un grafico pie-of-pie o bar-of-pie con una divisione personalizzata.<br/>            Contiene i punti dati che devono essere disegnati nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie.<br/>            Solo lettura [`IPieSplitCustomPointCollection`](/slides/python-net/it/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Specifica la dimensione del foro in un grafico ciambella (può essere tra il 10% e il 90% della dimensione dell'area di disegno).<br/>            Lettura/scrittura **int**. |
| [`bubble_size_scale`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percenti della dimensione predefinita).<br/>            Lettura/scrittura **int**. |
| [`hi_low_lines_format`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Specifica il formato HiLowLines. HiLowLines è applicato con i tipi di grafico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Specifica come i valori di dimensione della bolla sono rappresentati nel grafico a bolle.<br/>            Lettura/scrittura [`BubbleSizeRepresentationType`](/slides/python-net/it/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Ottiene l'elemento all'indice specificato.

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### Osservazioni

1) Vedere il riepilogo e le osservazioni per la classe ChartSeriesGroupCollection e la enumerazione CombinableSeriesTypesGroup.  
2) Il gruppo di serie contiene alcune proprietà di serie che sono comuni a ogni serie nel gruppo ("proprietà del gruppo di serie").  
   Le "proprietà del gruppo di serie" nella classe ChartSeriesGroup sono lettura/scrittura.  
   Ciascuna delle "proprietà del gruppo di serie" può avere una proiezione solo lettura nella classe ChartSeries.

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)