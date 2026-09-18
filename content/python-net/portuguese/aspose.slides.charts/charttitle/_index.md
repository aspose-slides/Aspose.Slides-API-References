---
title: ChartTitle class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.charts/charttitle/
---
## ChartTitle classe

Representa as propriedades do título do gráfico.

O tipo ChartTitle expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`x`](/slides/python-net/pt/aspose.slides.charts/charttitle/x/) | Retorna ou define a coordenada x de um título como uma fração da largura do gráfico.<br/>            Leitura/gravação **float**. |
| [`y`](/slides/python-net/pt/aspose.slides.charts/charttitle/y/) | Retorna ou define a coordenada y de um título como uma fração da altura do gráfico.<br/>            Leitura/gravação **float**. |
| [`width`](/slides/python-net/pt/aspose.slides.charts/charttitle/width/) | Retorna ou define a largura de um título como uma fração da largura do gráfico.<br/>            Leitura/gravação **float**. |
| [`height`](/slides/python-net/pt/aspose.slides.charts/charttitle/height/) | Retorna ou define a altura de um título como uma fração da altura do gráfico.<br/>            Leitura/gravação **float**. |
| [`right`](/slides/python-net/pt/aspose.slides.charts/charttitle/right/) | Direita.<br/>            Somente leitura **float**. |
| [`bottom`](/slides/python-net/pt/aspose.slides.charts/charttitle/bottom/) | Inferior.<br/>            Somente leitura **float**. |
| [`overlay`](/slides/python-net/pt/aspose.slides.charts/charttitle/overlay/) | Determina se outros elementos do gráfico podem se sobrepor ao título.<br/>            Leitura/gravação **bool**. |
| [`format`](/slides/python-net/pt/aspose.slides.charts/charttitle/format/) | Retorna os estilos de preenchimento, linha e efeito de um título.<br/>            Somente leitura [`IFormat`](/slides/python-net/pt/aspose.slides.charts/iformat). |
| [`text_frame_for_overriding`](/slides/python-net/pt/aspose.slides.charts/charttitle/text_frame_for_overriding/) | Pode conter um texto rico formatado. Se esta propriedade não for None, então este <br/>            valor de texto formatado substitui o texto gerado automaticamente.<br/>            Texto gerado automaticamente é uma propriedade implícita do rótulo de dados, do rótulo de unidade de exibição do eixo de valores, do título do eixo, do título do gráfico, do rótulo da linha de tendência.<br/>            Texto gerado automaticamente é formatado com a propriedade IFormattedTextContainer.TextFormat.<br/>            Somente leitura [`ITextFrame`](/slides/python-net/pt/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/pt/aspose.slides.charts/charttitle/text_format/) | Retorna o formato de texto.<br/>            Somente leitura [`IChartTextFormat`](/slides/python-net/pt/aspose.slides.charts/icharttextformat). |
| [`actual_x`](/slides/python-net/pt/aspose.slides.charts/charttitle/actual_x/) | Especifica a posição x real (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico.<br/>            Chame o método IChart.ValidateChartLayout() antes para obter valores reais. <br/>            Leitura **float**. |
| [`actual_y`](/slides/python-net/pt/aspose.slides.charts/charttitle/actual_y/) | Especifica a parte superior real do elemento do gráfico em relação ao canto superior esquerdo do gráfico.<br/>            Chame o método IChart.ValidateChartLayout() antes para obter valores reais. <br/>            Leitura **float**. |
| [`actual_width`](/slides/python-net/pt/aspose.slides.charts/charttitle/actual_width/) | Especifica a largura real do elemento do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter valores reais. <br/>            Leitura **float**. |
| [`actual_height`](/slides/python-net/pt/aspose.slides.charts/charttitle/actual_height/) | Especifica a altura real do elemento do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter valores reais. <br/>            Leitura **float**. |
| [`chart`](/slides/python-net/pt/aspose.slides.charts/charttitle/chart/) | Retorna o gráfico pai.<br/>            Somente leitura [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/pt/aspose.slides.charts/charttitle/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides.charts/charttitle/presentation/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/pt/aspose.slides.charts/charttitle/add_text_frame_for_overriding/#str) | Inicializa TextFrameForOverriding com o texto no parâmetro "text".<br/>            Se TextFrameForOverriding já estiver inicializado, então simplesmente altera seu texto. |

### Veja Também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)