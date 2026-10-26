---
title: ChartSeriesGroup class
second_title: Riferimento API di Aspose.Slides per Python tramite .NET
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
| [`plot_on_second_axis`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Indica se le serie di questo gruppo sono tracciate su un asse secondario.<br/>            Sola lettura **bool**. |
| [`series`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/series/) | Restituisce una raccolta di serie.<br/>            Sola lettura [`IChartSeriesReadonlyCollection`](/slides/python-net/it/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Fornisce l'accesso alle barre su/giù di un grafico a linee o a candela.<br/>            Sola lettura [`IUpDownBarsManager`](/slides/python-net/it/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/gap_width/) | Specifica lo spazio tra i gruppi di barre o colonne, come percentuale della larghezza della barra o colonna.<br/>            Lettura/Scrittura **int**. |
| [`gap_depth`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/gap_depth/) | Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D.<br/>            Lettura/Scrittura **int**. |
| [`first_slice_angle`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Restituisce o imposta l'angolo della prima fetta di torta o ciambella, <br/>            in gradi (orario dall'alto, da 0 a 360 gradi).<br/>            Lettura/Scrittura **int**. |
| [`doughnut_hole_size`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Specifica la dimensione del foro in un grafico a ciambella (può essere tra 0 e 90 percento <br/>            della dimensione dell'area del grafico).<br/>            Lettura/Scrittura **int**. |
| [`overlap`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/overlap/) | Specifica di quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%).<br/>             - -100%: Spaziatura massima (le barre sono completamente separate).<br/>             - 0%: Le barre sono affiancate senza sovrapposizione o spaziatura.<br/>             - 100%: Sovrapposizione massima (le barre si sovrappongono completamente).<br/>             Questa proprietà è Lettura/Scrittura **int**. |
| [`second_pie_size`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Specifica la dimensione della seconda fetta o barra di un grafico torta-sotto-torta o <br/>            un grafico barra-sotto-torta, come percentuale della dimensione della prima fetta (può <br/>            essere tra 5 e 200 percento).<br/>            Lettura/Scrittura **int**. |
| [`bubble_size_representation`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Specifica come i valori di dimensione delle bolle sono rappresentati nel grafico a bolle.<br/>            Lettura/Scrittura [`BubbleSizeRepresentationType`](/slides/python-net/it/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Specifica un valore da utilizzare per determinare quali punti dati <br/>            sono nella seconda fetta o barra in un grafico torta-sotto-torta o barra-sotto-torta. <br/>            È usato insieme alla proprietà PieSplitBy.<br/>            Lettura/Scrittura **float**. |
| [`pie_split_by`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Specifica come determinare quali punti dati sono nella seconda fetta o barra <br/>            in un grafico torta-sotto-torta o barra-sotto-torta.<br/>            Lettura/Scrittura [`PieSplitType`](/slides/python-net/it/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Specifica che ogni marcatore dati nella serie ha un colore diverso.<br/>            Lettura/Scrittura **bool**. |
| [`has_series_lines`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Vero se il grafico ha linee di serie. Applicato ai grafici a barre impilate e OfPie.<br/>            Lettura/Scrittura **bool**. |
| [`hi_low_lines_format`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Specifica il formato HiLowLines. <br/>            HiLowLines è applicato con i tipi di grafico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Specifica il fattore di scala per il grafico a bolle (può essere <br/>            tra 0 e 300 percento della dimensione predefinita).<br/>            Lettura/Scrittura **int**. |
| [`pie_split_custom_points`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Le informazioni di divisione personalizzata per un grafico torta-sotto-torta o barra-sotto-torta con divisione personalizzata.<br/>            Contiene i punti dati che devono essere disegnati nella seconda fetta o barra in un grafico torta-sotto-torta o <br/>            barra-sotto-torta.<br/>            Sola lettura [`PieSplitCustomPointCollection`](/slides/python-net/it/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/chart/) | Restituisce il grafico genitore.<br/>            Sola lettura [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Restituisce l'elemento all'indice specificato.

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### Osservazioni

1) Vedere il riepilogo e le osservazioni per la classe ChartSeriesGroupCollection e l'enumerazione CombinableSeriesTypesGroup.
            2) Un gruppo di serie contiene alcune proprietà delle serie che sono comuni a 
            ogni serie nel gruppo ("proprietà del gruppo di serie").
            Le "proprietà del gruppo di serie" nella classe ChartSeriesGroup sono Lettura/Scrittura.
            Ognuna delle "proprietà del gruppo di serie" può avere una proiezione Sola lettura nella classe ChartSeries.


### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)