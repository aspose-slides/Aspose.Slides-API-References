---
title: DataLabel class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/datalabel/
---
## DataLabel classe

Representa os rótulos de uma série.

O tipo DataLabel expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/pt/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Cria uma nova instância da classe DataLabel. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`chart`](/slides/python-net/pt/aspose.slides.charts/datalabel/chart/) | Retorna o gráfico pai.<br/>            Somente leitura [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/pt/aspose.slides.charts/datalabel/is_visible/) | False significa que o rótulo de dados não está visível (e portanto todas as flags Show* (ShowValue, ...) são falsas).<br/>            Somente leitura **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/pt/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Pode conter um texto formatado rico. Se esta propriedade não for None, então este <br/>            valor de texto formatado substitui o texto gerado automaticamente do rótulo de dados.<br/>            Texto gerado automaticamente do rótulo de dados significa o texto gerenciado por ShowSeriesName, <br/>            ShowValue, ... propriedades e formatado com a propriedade TextFormatManager.TextFormat.<br/>            Somente leitura [`ITextFrame`](/slides/python-net/pt/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/pt/aspose.slides.charts/datalabel/text_format/) | Retorna o formato de texto.<br/>            Somente leitura [`IChartTextFormat`](/slides/python-net/pt/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/pt/aspose.slides.charts/datalabel/x/) | Retorna ou define a coordenada x de um título como uma fração da largura do gráfico.<br/>            Leitura/gravação **float**. |
| [`y`](/slides/python-net/pt/aspose.slides.charts/datalabel/y/) | Retorna ou define a coordenada y de um título como uma fração da altura do gráfico.<br/>            Leitura/gravação **float**. |
| [`width`](/slides/python-net/pt/aspose.slides.charts/datalabel/width/) | Retorna ou define a largura de um título como uma fração da largura do gráfico.<br/>            Leitura/gravação **float**. |
| [`height`](/slides/python-net/pt/aspose.slides.charts/datalabel/height/) | Retorna ou define a altura de um título como uma fração da altura do gráfico.<br/>            Leitura/gravação **float**. |
| [`right`](/slides/python-net/pt/aspose.slides.charts/datalabel/right/) | Direita.<br/>            Somente leitura **float**. |
| [`bottom`](/slides/python-net/pt/aspose.slides.charts/datalabel/bottom/) | Inferior.<br/>            Somente leitura **float**. |
| [`data_label_format`](/slides/python-net/pt/aspose.slides.charts/datalabel/data_label_format/) | Retorna o formato do rótulo de dados.<br/>            Somente leitura [`IDataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/pt/aspose.slides.charts/datalabel/value_from_cell/) | Obtém ou define a célula de dados da pasta de trabalho. Aplicado se a propriedade IDataLabelFormat.ShowLabelValueFromCell for verdadeira. |
| [`actual_x`](/slides/python-net/pt/aspose.slides.charts/datalabel/actual_x/) | Especifica a localização x real (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico.<br/>            Chame o método IChart.ValidateChartLayout() antes para obter valores reais. <br/>            Leitura **float**. |
| [`actual_y`](/slides/python-net/pt/aspose.slides.charts/datalabel/actual_y/) | Especifica a parte superior real do elemento do gráfico em relação ao canto superior esquerdo do gráfico.<br/>            Chame o método IChart.ValidateChartLayout() antes para obter valores reais. <br/>            Leitura **float**. |
| [`actual_width`](/slides/python-net/pt/aspose.slides.charts/datalabel/actual_width/) | Especifica a largura real do elemento do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter valores reais. <br/>            Leitura **float**. |
| [`actual_height`](/slides/python-net/pt/aspose.slides.charts/datalabel/actual_height/) | Especifica a altura real do elemento do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter valores reais. <br/>            Leitura **float**. |
| [`slide`](/slides/python-net/pt/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides.charts/datalabel/presentation/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`hide(self)`](/slides/python-net/pt/aspose.slides.charts/datalabel/hide/#) | Torna o rótulo de dados oculto definindo todas as flags Show* (ShowValue, ...) para o estado false.<br/>            IsVisible será false após isso. |
| [`get_actual_label_text(self)`](/slides/python-net/pt/aspose.slides.charts/datalabel/get_actual_label_text/#) | Retorna o texto real do rótulo com base nas configurações DataLabelFormat ou no valor TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/pt/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Inicializa TextFrameForOverriding com o texto no parâmetro "text".<br/>            Se TextFrameForOverriding já estiver inicializado, simplesmente altera seu texto. |

### Ver também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)