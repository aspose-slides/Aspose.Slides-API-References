---
title: ChartSeriesGroup class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup classe

Rappresenta un gruppo di serie.

Il tipo ChartSeriesGroup espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`type`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/type/) | Restituisce un tipo di questo gruppo di serie.<br/>            Sola lettura [`CombinableSeriesTypesGroup`](/slides/python-net/it/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Indica se le serie di questo gruppo sono tracciate su asse secondario.<br/>            Sola lettura **bool**. |
| [`series`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/series/) | Restituisce una collezione di serie.<br/>            Sola lettura [`IChartSeriesReadonlyCollection`](/slides/python-net/it/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Fornisce accesso a barre su/giù di grafici a linee o a barre.<br/>            Sola lettura [`IUpDownBarsManager`](/slides/python-net/it/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/gap_width/) | Ottiene o imposta lo spazio tra i raggruppamenti di barre o colonne, come percentuale della larghezza della barra o della colonna.<br/>            Il valore deve essere compreso tra 0 e 500.<br/>            Lettura/scrittura **int**. |
| [`gap_depth`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/gap_depth/) | Ottiene o imposta la distanza tra le serie di dati in un grafico 3D, come percentuale della larghezza del marcatore.<br/>            Il valore deve essere compreso tra 0 e 500.<br/>            Lettura/scrittura **int**. |
| [`first_slice_angle`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Ottiene o imposta l'angolo della prima fetta di un grafico a torta o ciambella, <br/>            in gradi (in senso orario dall'alto, da 0 a 360 gradi).<br/>            Lettura/scrittura **int**. |
| [`doughnut_hole_size`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Specifica la dimensione del foro in un grafico a ciambella (può essere tra 0 e 90 percento <br/>            della dimensione dell'area del grafico).<br/>            Lettura/scrittura **int**. |
| [`overlap`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/overlap/) | Specifica quanto barre e colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%).<br/>             - -100%: Spaziatura massima (le barre sono completamente separate).<br/>             - 0%: Le barre sono affiancate senza sovrapposizione né spaziatura.<br/>             - 100%: Sovrapposizione massima (le barre si sovrappongono completamente).<br/>             Questa proprietà è lettura/scrittura **int**. |
| [`second_pie_size`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Specifica la dimensione della seconda fetta o barra di un grafico torta-sulla-torta o <br/>            di un grafico barra-sulla-torta, come percentuale della dimensione della prima fetta (può <br/>            essere tra 5 e 200 percento).<br/>            Lettura/scrittura **int**. |
| [`bubble_size_representation`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Specifica come i valori di dimensione delle bolle sono rappresentati nel grafico a bolle.<br/>            Lettura/scrittura [`BubbleSizeRepresentationType`](/slides/python-net/it/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Specifica un valore da usare per determinare quali punti dati <br/>            sono nella seconda fetta o barra di un grafico torta-sulla-torta o barra-sulla-torta. <br/>            È usato insieme alla proprietà PieSplitBy.<br/>            Lettura/scrittura **float**. |
| [`pie_split_by`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Specifica come determinare quali punti dati sono nella seconda fetta o barra <br/>            di un grafico torta-sulla-torta o barra-sulla-torta.<br/>            Lettura/scrittura [`PieSplitType`](/slides/python-net/it/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Specifica che ogni marcatore dati nella serie ha un colore diverso.<br/>            Lettura/scrittura **bool**. |
| [`has_series_lines`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Vero se il grafico ha linee di serie. Applicato a grafici a barre impilate e OfPie.<br/>            Lettura/scrittura **bool**. |
| [`hi_low_lines_format`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Specifica il formato HiLowLines. <br/>            HiLowLines applicato con i tipi di grafico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Specifica il fattore di scala per il grafico a bolle (può essere <br/>            tra 0 e 300 percento della dimensione predefinita).<br/>            Lettura/scrittura **int**. |
| [`pie_split_custom_points`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Le informazioni di divisione personalizzate per un grafico torta-sulla-torta o barra-sulla-torta con divisione personalizzata.<br/>            Contiene i punti dati che devono essere disegnati nella seconda fetta o barra in un grafico torta-sulla-torta o <br/>            barra-sulla-torta.<br/>            Sola lettura [`PieSplitCustomPointCollection`](/slides/python-net/it/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/chart/) | Restituisce il grafico genitore.<br/>            Sola lettura [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Ottiene l'elemento all'indice specificato.

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### Osservazioni

1) Vedi il riepilogo e le osservazioni per la classe ChartSeriesGroupCollection e l'enumerazione CombinableSeriesTypesGroup.  
2) Il gruppo di serie contiene alcune proprietà delle serie che sono comuni a ogni serie nel gruppo ("proprietà del gruppo di serie").  
   Le "proprietà del gruppo di serie" nella classe ChartSeriesGroup sono lettura/scrittura.  
   Ciascuna delle "proprietà del gruppo di serie" può avere una proiezione sola lettura nella classe ChartSeries.


### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)