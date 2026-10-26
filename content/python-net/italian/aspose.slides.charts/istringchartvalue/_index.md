---
title: IStringChartValue class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue classe

Rappresenta un valore stringa che può essere memorizzato in un documento di presentazione pptx in due modi:
1) nella/e cella/e della cartella di lavoro collegata al grafico;
2) come valore letterale.

Il tipo IStringChartValue espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`as_literal_string`](/slides/python-net/it/aspose.slides.charts/istringchartvalue/as_literal_string/) | Restituisce o imposta la stringa letterale se la proprietà DataSourceType è DataSourceType.StringLiterals.<br/>            Lettura/scrittura **str**. |
| [`as_cells`](/slides/python-net/it/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [`data_source_type`](/slides/python-net/it/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [`data`](/slides/python-net/it/aspose.slides.charts/istringchartvalue/data/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`to_string(self)`](/slides/python-net/it/aspose.slides.charts/istringchartvalue/to_string/#) | Restituisce la rappresentazione della stringa. |
| [`set_from_one_cell(self, cell)`](/slides/python-net/it/aspose.slides.charts/istringchartvalue/set_from_one_cell/#ichartdatacell) | Imposta il valore dalla cella specificata. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/it/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | Se la proprietà DataSourceType è DataSourceType.Worksheet, questo metodo restituisce l'indirizzo<br/>            delle celle nella cartella di lavoro che rappresentano i dati stringa. Altrimenti restituisce<br/>            una stringa vuota. |

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)