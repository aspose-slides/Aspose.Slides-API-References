---
title: IDataLabelCollection class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection classe

Representa rótulos de série.

O tipo IDataLabelCollection expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Retorna o formato padrão de todos os rótulos de dados na coleção.<br/>            Somente leitura [`IDataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Representa o formato das linhas guias dos rótulos de dados.<br/>             Somente leitura [`IChartLinesFormat`](/slides/python-net/pt/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/is_visible/) | False indica que o rótulo de dados não está visível por padrão (e, portanto, todas as <br/>            Show*-flags (ShowValue, ...) da propriedade DefaultDataLabelFormat são falsas).<br/>            Somente leitura **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Obtém o número de rótulos de dados visíveis na coleção.<br/>            Somente leitura **int**. |
| [`count`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/count/) | Obtém o número de todos os rótulos de dados na coleção.<br/>            Somente leitura **int**. |
| [`parent_series`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/parent_series/) | Retorna a série de gráfico pai.<br/>            Somente leitura [`IChartSeries`](/slides/python-net/pt/aspose.slides.charts/ichartseries). |
| [`chart`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Obtém o rótulo de dados para o ponto de dados com o índice especificado.

## Indexador

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`hide(self)`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/hide/#) | Torna o rótulo de dados oculto por padrão, definindo todas as Show*-flags (ShowValue, ...) da propriedade <br/>            DefaultDataLabelFormat para o estado false.<br/>            IsVisible será false após isso. |
| [`index_of(self, value)`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Retorna um índice do DataLabel especificado na coleção. |

### Ver Também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)