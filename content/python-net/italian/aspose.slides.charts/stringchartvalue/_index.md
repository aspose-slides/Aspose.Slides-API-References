---
title: StringChartValue class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/stringchartvalue/
---
## StringChartValue classe

Rappresenta un valore stringa che può essere memorizzato in pptx presentation document in due modi:
            1) in cell/cells di workbook correlato a chart;
            2) come valore letterale.

**Ereditarietà:**[`StringChartValue`](/slides/python-net/it/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/it/aspose.slides.charts/basechartvalue)

Il tipo StringChartValue espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`data_source_type`](/slides/python-net/it/aspose.slides.charts/stringchartvalue/data_source_type/) | Specifica se la proprietà AsCell, AsCells, AsLiteralString o AsLiteralDouble <br/>            è effettiva nei discendenti. In altre parole specifica il tipo <br/>            di valore della proprietà Data.<br/>            Lettura/scrittura [`DataSourceType`](/slides/python-net/it/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/it/aspose.slides.charts/stringchartvalue/data/) | Restituisce o imposta l'oggetto Data.<br/>            Lettura/scrittura **qualsiasi**. |
| [`as_cells`](/slides/python-net/it/aspose.slides.charts/stringchartvalue/as_cells/) | L'assegnazione di valore null non è consentita.<br/>            Il valore restituito è sempre non nullo.<br/>            Lettura/scrittura [`IChartCellCollection`](/slides/python-net/it/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/it/aspose.slides.charts/stringchartvalue/as_literal_string/) | Restituisce o imposta il valore come stringa letterale.<br/>            Lettura/scrittura **str**. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/it/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | Imposta il valore dalla cella specificata. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/it/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | Se la proprietà DataSourceType è DataSourceType.Worksheet, allora questo metodo restituisce l'indirizzo<br/>            delle celle nel workbook che rappresentano i dati stringa. Altrimenti restituisce<br/>            una stringa vuota. |

### Vedi anche
* classe [`BaseChartValue`](/slides/python-net/it/aspose.slides.charts/basechartvalue)
* classe [`StringChartValue`](/slides/python-net/it/aspose.slides.charts/stringchartvalue)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)