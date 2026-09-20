---
title: ChartDataCell class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/chartdatacell/
---
## ChartDataCell classe

Rappresenta una cella per i dati del grafico.

Il tipo ChartDataCell espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`row`](/slides/python-net/it/aspose.slides.charts/chartdatacell/row/) | Restituisce l'indice della riga del foglio di lavoro in cui si trova la cella.<br/>            Read-only **int**. |
| [`column`](/slides/python-net/it/aspose.slides.charts/chartdatacell/column/) | Restituisce l'indice della colonna del foglio di lavoro in cui si trova la cella.<br/>            Read-only **int**. |
| [`value`](/slides/python-net/it/aspose.slides.charts/chartdatacell/value/) | Ottiene o imposta il valore di una cella.<br/>            Read/write **any**. |
| [`formula`](/slides/python-net/it/aspose.slides.charts/chartdatacell/formula/) | Ottiene o imposta la formula in stile A1. |
| [`r1c1_formula`](/slides/python-net/it/aspose.slides.charts/chartdatacell/r1c1_formula/) | Ottiene o imposta la formula in stile R1C1. |
| [`chart_data_worksheet`](/slides/python-net/it/aspose.slides.charts/chartdatacell/chart_data_worksheet/) | Ottiene il foglio di lavoro.<br/>            Read-only [`IChartDataWorksheet`](/slides/python-net/it/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/it/aspose.slides.charts/chartdatacell/is_hidden/) | Determina se la cella è nascosta.<br/>            Read-only **bool**. |
| [`custom_number_format`](/slides/python-net/it/aspose.slides.charts/chartdatacell/custom_number_format/) | Ottiene o imposta il formato di visualizzazione personalizzato di numeri e date. <br/>            Se il valore è vuoto verrà utilizzato il valore PresetNumberFormat.<br/>            Read/write **str**. |
| [`preset_number_format`](/slides/python-net/it/aspose.slides.charts/chartdatacell/preset_number_format/) | Ottiene o imposta il formato di visualizzazione predefinito di numeri e date. Il numero predefinito deve essere in [0..22] o [37..49].<br/>            Read/write **int**. |

## Metodi

| Method | Description |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/it/aspose.slides.charts/chartdatacell/calculate/#bool) | Se la cella contiene una formula, il valore sarà aggiornato in base a quella formula. |

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)