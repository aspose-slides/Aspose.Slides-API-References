---
title: IAxis class
second_title: Aspose.Slides per Python tramite API .NET
description: 
type: docs
url: /it/aspose.slides.charts/iaxis/
---
## IAxis classe

Incapsula l'oggetto che rappresenta l'asse di un grafico.

Il tipo IAxis espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/it/aspose.slides.charts/iaxis/axis_between_categories/) | Rappresenta se l'asse dei valori attraversa l'asse delle categorie tra le categorie.<br/>            Questa proprietà si applica solo agli assi delle categorie e non si applica ai grafici 3-D.<br/>            Lettura/scrittura **bool**. |
| [`cross_at`](/slides/python-net/it/aspose.slides.charts/iaxis/cross_at/) | Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa.<br/>            Lettura/scrittura **float**. |
| [`display_unit`](/slides/python-net/it/aspose.slides.charts/iaxis/display_unit/) | Specifica il valore di scala delle unità di visualizzazione per l'asse dei valori.<br/>            Lettura/scrittura [`DisplayUnitType`](/slides/python-net/it/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/it/aspose.slides.charts/iaxis/actual_max_value/) | Specifica il valore massimo effettivo sull'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore effettivo. |
| [`actual_min_value`](/slides/python-net/it/aspose.slides.charts/iaxis/actual_min_value/) | Specifica il valore minimo effettivo sull'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore effettivo. |
| [`actual_major_unit`](/slides/python-net/it/aspose.slides.charts/iaxis/actual_major_unit/) | Specifica l'unità principale effettiva dell'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore effettivo. |
| [`actual_minor_unit`](/slides/python-net/it/aspose.slides.charts/iaxis/actual_minor_unit/) | Specifica l'unità secondaria effettiva dell'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore effettivo. |
| [`actual_major_unit_scale`](/slides/python-net/it/aspose.slides.charts/iaxis/actual_major_unit_scale/) | Specifica la scala dell'unità principale effettiva dell'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore effettivo. |
| [`actual_minor_unit_scale`](/slides/python-net/it/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | Specifica la scala dell'unità secondaria effettiva dell'asse. Chiamare in precedenza il metodo IChart.ValidateChartLayout() per ottenere il valore effettivo. |
| [`is_automatic_max_value`](/slides/python-net/it/aspose.slides.charts/iaxis/is_automatic_max_value/) | Indica se il valore massimo è assegnato automaticamente.<br/>             Lettura/scrittura **bool**. |
| [`max_value`](/slides/python-net/it/aspose.slides.charts/iaxis/max_value/) | Rappresenta il valore massimo sull'asse dei valori.<br/>             Lettura/scrittura **float**. |
| [`minor_unit`](/slides/python-net/it/aspose.slides.charts/iaxis/minor_unit/) | Rappresenta le unità secondarie per l'asse della data o dei valori.<br/>             Lettura/scrittura **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/it/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | Indica se l'unità secondaria dell'asse è assegnata automaticamente.<br/>             Lettura/scrittura **bool**. |
| [`major_unit`](/slides/python-net/it/aspose.slides.charts/iaxis/major_unit/) | Rappresenta le unità principali per l'asse della data o dei valori.<br/>             Lettura/scrittura **float**. |
| [`is_automatic_major_unit`](/slides/python-net/it/aspose.slides.charts/iaxis/is_automatic_major_unit/) | Indica se l'unità principale dell'asse è assegnata automaticamente.<br/>            Lettura/scrittura **bool**. |
| [`is_automatic_min_value`](/slides/python-net/it/aspose.slides.charts/iaxis/is_automatic_min_value/) | Indica se il valore minimo è assegnato automaticamente.<br/>             Lettura/scrittura **bool**. |
| [`min_value`](/slides/python-net/it/aspose.slides.charts/iaxis/min_value/) | Rappresenta il valore minimo sull'asse dei valori.<br/>             Lettura/scrittura **float**. |
| [`is_logarithmic`](/slides/python-net/it/aspose.slides.charts/iaxis/is_logarithmic/) | Rappresenta se il tipo di scala dell'asse dei valori è logaritmico o meno.<br/>             Lettura/scrittura **bool**. |
| [`log_base`](/slides/python-net/it/aspose.slides.charts/iaxis/log_base/) | Rappresenta la base logaritmica. Il valore predefinito è 10.<br/>             Lettura/scrittura **float**. |
| [`is_plot_order_reversed`](/slides/python-net/it/aspose.slides.charts/iaxis/is_plot_order_reversed/) | Rappresenta se MS PowerPoint traccia i punti dati dall'ultimo al primo.<br/>             Lettura/scrittura **bool**. |
| [`is_visible`](/slides/python-net/it/aspose.slides.charts/iaxis/is_visible/) | Rappresenta se l'asse è visibile.<br/>             Lettura/scrittura **bool**. |
| [`major_tick_mark`](/slides/python-net/it/aspose.slides.charts/iaxis/major_tick_mark/) | Rappresenta il tipo di marcatura principale per l'asse specificato.<br/>             Lettura/scrittura [`TickMarkType`](/slides/python-net/it/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/it/aspose.slides.charts/iaxis/minor_tick_mark/) | Rappresenta il tipo di marcatura secondaria per l'asse specificato.<br/>             Lettura/scrittura [`TickMarkType`](/slides/python-net/it/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/it/aspose.slides.charts/iaxis/tick_label_position/) | Rappresenta la posizione delle etichette dei tick su l'asse specificato.<br/>             Lettura/scrittura [`TickLabelPositionType`](/slides/python-net/it/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/it/aspose.slides.charts/iaxis/major_unit_scale/) | Rappresenta la scala dell'unità principale per l'asse della data.<br/>             Lettura/scrittura [`TimeUnitType`](/slides/python-net/it/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/it/aspose.slides.charts/iaxis/minor_unit_scale/) | Rappresenta la scala dell'unità principale per l'asse della data.<br/>             Lettura/scrittura [`TimeUnitType`](/slides/python-net/it/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/it/aspose.slides.charts/iaxis/base_unit_scale/) | Specifica l'unità di tempo più piccola rappresentata sull'asse della data.<br/>            Lettura/scrittura [`TimeUnitType`](/slides/python-net/it/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/it/aspose.slides.charts/iaxis/minor_grid_lines_format/) | Rappresenta il formato delle linee di griglia secondarie su un asse del grafico.<br/>             Solo lettura [`IChartLinesFormat`](/slides/python-net/it/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/it/aspose.slides.charts/iaxis/major_grid_lines_format/) | Rappresenta il formato delle linee di griglia principali su un asse del grafico.<br/>             Solo lettura [`IChartLinesFormat`](/slides/python-net/it/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/it/aspose.slides.charts/iaxis/show_minor_grid_lines/) | Rappresenta se le linee di griglia secondarie sono visualizzate.<br/>             Solo lettura **bool**. |
| [`show_major_grid_lines`](/slides/python-net/it/aspose.slides.charts/iaxis/show_major_grid_lines/) | Rappresenta se le linee di griglia principali sono visualizzate.<br/>             Solo lettura **bool**. |
| [`format`](/slides/python-net/it/aspose.slides.charts/iaxis/format/) | Rappresenta il formato dell'asse.<br/>             Solo lettura [`IAxisFormat`](/slides/python-net/it/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/it/aspose.slides.charts/iaxis/title/) | Ottiene il titolo dell'asse.<br/>             Solo lettura [`IChartTitle`](/slides/python-net/it/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/it/aspose.slides.charts/iaxis/cross_type/) | Rappresenta il CrossType sull'asse specificato dove l'altro asse lo attraversa.<br/>             Lettura/scrittura [`CrossesType`](/slides/python-net/it/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/it/aspose.slides.charts/iaxis/position/) | Rappresenta la posizione dell'asse.<br/>             Lettura/scrittura [`AxisPositionType`](/slides/python-net/it/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/it/aspose.slides.charts/iaxis/has_title/) | Determina se un asse ha un titolo visibile.<br/>            Lettura/scrittura **bool**. |
| [`number_format`](/slides/python-net/it/aspose.slides.charts/iaxis/number_format/) | Rappresenta la stringa di formato per le etichette dell'asse.<br/>            Lettura/scrittura **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/it/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | Indica se il formato è collegato a dati di origine.<br/>            Lettura/scrittura **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/it/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | Rappresenta l'angolo di rotazione delle etichette dei tick<br/>            Lettura/scrittura **float**. |
| [`tick_label_spacing`](/slides/python-net/it/aspose.slides.charts/iaxis/tick_label_spacing/) | Specifica quante etichette dei tick saltare tra le etichette disegnate.<br/>            Lettura/scrittura **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/it/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | Specifica il valore di spaziatura automatica delle etichette dei tick. Se falso: usare la proprietà TickLabelSpacing.<br/>            Lettura/scrittura **bool**. |
| [`tick_marks_spacing`](/slides/python-net/it/aspose.slides.charts/iaxis/tick_marks_spacing/) | Specifica quanti segni di tick devono essere saltati prima che il successivo sia <br/>            disegnato. Applicato a un asse di categoria o di serie.<br/>            Lettura/scrittura **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/it/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | Specifica il valore di spaziatura automatica dei segni di tick. Se falso: usare la proprietà TickMarksSpacing.<br/>            Lettura/scrittura **bool**. |
| [`label_offset`](/slides/python-net/it/aspose.slides.charts/iaxis/label_offset/) | Specifica la distanza delle etichette dall'asse. Applicato a un asse di categoria o di data. Il valore deve essere compreso tra 0% e 1000%.<br/>            Lettura/scrittura **int**. |
| [`category_axis_type`](/slides/python-net/it/aspose.slides.charts/iaxis/category_axis_type/) | Specifica il tipo dell'asse di categoria.<br/>            Lettura/scrittura [`IAxis.category_axis_type`](/slides/python-net/it/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/it/aspose.slides.charts/iaxis/aggregation_type/) | Rappresenta il tipo di aggregazione dell'asse di categoria (binning). Applicato a categoria. Utilizzato solo con serie Histogram o HistogramPareto. |
| [`bin_width`](/slides/python-net/it/aspose.slides.charts/iaxis/bin_width/) | Specifica la larghezza del bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByBinWidth.<br/>            Applicato agli assi di categoria. Utilizzato solo con serie Histogram o HistogramPareto. |
| [`number_of_bins`](/slides/python-net/it/aspose.slides.charts/iaxis/number_of_bins/) | Specifica il numero di bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByNumberOfBins.<br/>            Applicato agli assi di categoria. Utilizzato solo con serie Histogram o HistogramPareto. |
| [`is_overflow_bin`](/slides/python-net/it/aspose.slides.charts/iaxis/is_overflow_bin/) | Specifica se il bin di overflow è applicato. Usa IsAutomaticOverflowBin e OverflowBin per regolare il valore del bin di overflow. |
| [`is_automatic_overflow_bin`](/slides/python-net/it/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | Specifica il valore automatico del bin di overflow. Se falso: usa la proprietà OverflowBin. |
| [`overflow_bin`](/slides/python-net/it/aspose.slides.charts/iaxis/overflow_bin/) | Specifica un valore personalizzato per il bin di overflow. Applicato quando la proprietà IsAutomaticOverflowBin è impostata su false e la proprietà IsOverflowBin è true. |
| [`is_underflow_bin`](/slides/python-net/it/aspose.slides.charts/iaxis/is_underflow_bin/) | Specifica se il bin di underflow è applicato. Usa IsAutomaticUnderflowBin e UnderflowBin per regolare il valore del bin di underflow. |
| [`is_automatic_underflow_bin`](/slides/python-net/it/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | Specifica il valore automatico del bin di underflow. Se falso: usa la proprietà UnderflowBin. |
| [`underflow_bin`](/slides/python-net/it/aspose.slides.charts/iaxis/underflow_bin/) | Specifica un valore personalizzato per il bin di underflow. Applicato quando la proprietà IsAutomaticUnderflowBin è impostata su false e la proprietà IsUnderflowBin è true. |
| [`text_format`](/slides/python-net/it/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/it/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/it/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/iaxis/presentation/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/it/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | Imposta la proprietà IAxis.CategoryAxisType con un valore determinato automaticamente in base ai dati dell'asse. |

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)