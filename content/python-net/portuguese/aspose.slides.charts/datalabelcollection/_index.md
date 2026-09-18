---
title: DataLabelCollection class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection classe

Representa rótulos de série.

O tipo DataLabelCollection expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`chart`](/slides/python-net/pt/aspose.slides.charts/datalabelcollection/chart/) | Retorna o gráfico pai.<br/>            Somente leitura [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/pt/aspose.slides.charts/datalabelcollection/is_visible/) | False significa que o rótulo de dados não está visível por padrão (e, assim, todas as Show*-flags (ShowValue, ...) da propriedade DefaultDataLabelFormat são falsas).<br/>            Somente leitura **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/pt/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | Obtém o número de rótulos de dados visíveis na coleção.<br/>            Somente leitura **int**. |
| [`count`](/slides/python-net/pt/aspose.slides.charts/datalabelcollection/count/) | Obtém o número de todos os rótulos de dados na coleção.<br/>            Somente leitura **int**. |
| [`default_data_label_format`](/slides/python-net/pt/aspose.slides.charts/datalabelcollection/default_data_label_format/) | Obtém o formato padrão do rótulo de dados.<br/>            Somente leitura [`IDataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/pt/aspose.slides.charts/datalabelcollection/leader_lines_format/) | Representa o formato das linhas guia dos rótulos de dados.<br/>             Somente leitura [`IChartLinesFormat`](/slides/python-net/pt/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/pt/aspose.slides.charts/datalabelcollection/parent_series/) | Obtém a série pai.<br/>            Somente leitura [`IChartSeries`](/slides/python-net/pt/aspose.slides.charts/ichartseries). |
| [`slide`](/slides/python-net/pt/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides.charts/datalabelcollection/presentation/) |  |

Obtém o rótulo de dados para o ponto de dados com o índice especificado.

## Indexador

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`hide(self)`](/slides/python-net/pt/aspose.slides.charts/datalabelcollection/hide/#) | Torna o rótulo de dados oculto por padrão, definindo todas as Show*-flags (ShowValue, ...) da propriedade DefaultDataLabelFormat para o estado false.<br/>            IsVisible será false após isto. |
| [`index_of(self, value)`](/slides/python-net/pt/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | Retorna o índice do DataLabel especificado na coleção. |

### Ver também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)