---
title: IChartDataCell class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartdatacell/
---
## IChartDataCell classe

Rappresenta una cella per i dati del grafico.

Il tipo IChartDataCell espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`row`](/slides/python-net/it/aspose.slides.charts/ichartdatacell/row/) | Restituisce l'indice della riga del foglio di lavoro in cui si trova la cella.<br/>            Solo lettura **int**. |
| [`column`](/slides/python-net/it/aspose.slides.charts/ichartdatacell/column/) | Restituisce l'indice della colonna del foglio di lavoro in cui si trova la cella.<br/>            Solo lettura **int**. |
| [`value`](/slides/python-net/it/aspose.slides.charts/ichartdatacell/value/) | Ottiene o imposta il valore di una cella.<br/>            Lettura/scrittura **any**. |
| [`formula`](/slides/python-net/it/aspose.slides.charts/ichartdatacell/formula/) | Ottiene o imposta la formula in stile A1. |
| [`r1c1_formula`](/slides/python-net/it/aspose.slides.charts/ichartdatacell/r1c1_formula/) | Ottiene o imposta la formula in stile R1C1. |
| [`chart_data_worksheet`](/slides/python-net/it/aspose.slides.charts/ichartdatacell/chart_data_worksheet/) | Ottiene il foglio di lavoro.<br/>            Solo lettura [`IChartDataWorksheet`](/slides/python-net/it/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/it/aspose.slides.charts/ichartdatacell/is_hidden/) | Determina se la cella è nascosta.<br/>            Solo lettura **bool**. |
| [`custom_number_format`](/slides/python-net/it/aspose.slides.charts/ichartdatacell/custom_number_format/) | Ottiene o imposta il formato di visualizzazione personalizzato di numeri e date. <br/>            Se il valore è vuoto verrà usato il valore PresetNumberFormat.<br/>            Lettura/scrittura **str**. |
| [`preset_number_format`](/slides/python-net/it/aspose.slides.charts/ichartdatacell/preset_number_format/) | Ottiene o imposta il formato di visualizzazione predefinito di numeri e date. Il numero predefinito deve essere in [0..22] o [37..49].<br/>             Lettura/scrittura **int**. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/it/aspose.slides.charts/ichartdatacell/calculate/#bool) | Se la cella contiene una formula, il valore sarà aggiornato in base a quella formula. |


### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)