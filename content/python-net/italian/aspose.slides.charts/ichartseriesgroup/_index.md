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

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/type/) | Restituisce un tipo di questo gruppo di serie.<br/>            Sola lettura [`CombinableSeriesTypesGroup`](/slides/python-net/it/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Indica se le serie di questo gruppo sono tracciate su asse secondario.<br/>            Sola lettura **bool**. |
| [`series`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/series/) | Restituisce una raccolta di serie di grafico a sola lettura.<br/>            Sola lettura [`IChartSeriesReadonlyCollection`](/slides/python-net/it/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Fornisce l'accesso alle barre su/giù di grafico a linee o a barre.<br/>            Sola lettura [`IUpDownBarsManager`](/slides/python-net/it/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/gap_width/) | Ottiene o imposta lo spazio tra gruppi di barre o colonne, come percentuale della larghezza della barra o della colonna.<br/>            Il valore deve essere compreso tra 0 e 500.<br/>            Lettura/scrittura **int**. |
| [`gap_depth`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Ottiene o imposta la distanza tra le serie di dati in un grafico 3D, come percentuale della larghezza del marcatore.<br/>            Il valore deve essere compreso tra 0 e 500.<br/>            Lettura/scrittura **int**. |
| [`first_slice_angle`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Ottiene o imposta l'angolo della prima fetta di un grafico a torta o ciambella, <br/>            in gradi (in senso orario dall'alto, da 0 a 360 gradi).<br/>            Lettura/scrittura **int**. |
| [`is_color_varied`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Specifica che ogni marcatore dati nella serie ha un colore diverso.<br/>            Lettura/scrittura **bool**. |
| [`has_series_lines`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Vero se il grafico ha linee di serie. Applicato a grafici a barre impilate e OfPie.<br/>            Lettura/scrittura **bool**. |
| [`overlap`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/overlap/) | Specifica quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%).<br/>             - -100%: Spaziatura massima (le barre sono completamente separate).<br/>             - 0%: Le barre sono affiancate senza sovrapposizione o spaziatura.<br/>             - 100%: Sovrapposizione massima (le barre si sovrappongono completamente).<br/>             Questa proprietà è lettura/scrittura **int**. |
| [`second_pie_size`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Specifica la dimensione della seconda torta o barra di un grafico torta-sulla-torta o <br/>            un grafico barra-sulla-torta, come percentuale della dimensione della prima torta (può <br/>            essere tra 5 e 200 percento).<br/>            Lettura/scrittura **int**. |
| [`pie_split_position`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Specifica un valore da utilizzare per determinare quali punti dati <br/>            sono nella seconda torta o barra in un grafico torta-sulla-torta o barra-sulla-torta. <br/>            È usato insieme alla proprietà PieSplitBy.<br/>            Lettura/scrittura **float**. |
| [`pie_split_by`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Specifica come determinare quali punti dati sono nella seconda torta o barra <br/>            in un grafico torta-sulla-torta o barra-sulla-torta.<br/>            Lettura/scrittura [`PieSplitType`](/slides/python-net/it/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Le informazioni di divisione personalizzata per un grafico torta-sulla-torta o barra-sulla-torta con una divisione personalizzata.<br/>            Contiene i punti dati che devono essere disegnati nella seconda torta o barra in un grafico torta-sulla-torta o <br/>            barra-sulla-torta.<br/>            Sola lettura [`IPieSplitCustomPointCollection`](/slides/python-net/it/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Specifica la dimensione del buco in un grafico a ciambella (può essere tra 10 e 90 percento <br/>            della dimensione dell'area del grafico.).<br/>            Lettura/scrittura **int**. |
| [`bubble_size_scale`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Specifica il fattore di scala per il grafico a bolle (può essere <br/>            tra 0 e 300 percento della dimensione predefinita).<br/>            Lettura/scrittura **int**. |
| [`hi_low_lines_format`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Specifica il formato HiLowLines. <br/>            HiLowLines è applicato ai tipi di grafico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Specifica come i valori delle dimensioni delle bolle sono rappresentati nel grafico a bolle.<br/>            Lettura/scrittura [`BubbleSizeRepresentationType`](/slides/python-net/it/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Ottiene l'elemento all'indice specificato.

## Indicizzatore

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |


### Osservazioni

1) Vedi il riepilogo e le osservazioni per la classe ChartSeriesGroupCollection e l'enumerazione CombinableSeriesTypesGroup.
2) Il gruppo di serie contiene alcune proprietà delle serie che sono comuni a 
ogni serie nel gruppo ("proprietà del gruppo di serie").
Le "proprietà del gruppo di serie" nella classe ChartSeries sono lettura/scrittura.
Ciascuna delle "proprietà del gruppo di serie" può avere una proiezione a sola lettura nella classe ChartSeries.


### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)