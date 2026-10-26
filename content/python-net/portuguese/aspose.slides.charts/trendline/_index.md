---
title: Trendline class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/trendline/
---
## Trendline classe

A classe representa a linha de tendência da série do gráfico

O tipo Trendline expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`trendline_name`](/slides/python-net/pt/aspose.slides.charts/trendline/trendline_name/) | Obtém ou define  o nome da linha de tendência.<br/>            Leitura/gravação **str**. |
| [`trendline_type`](/slides/python-net/pt/aspose.slides.charts/trendline/trendline_type/) | Obtém ou define o tipo da linha de tendência.<br/>            Leitura/gravação [`TrendlineType`](/slides/python-net/pt/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/pt/aspose.slides.charts/trendline/format/) | Representa o formato da linha de tendência.<br/>            Leitura/gravação [`IFormat`](/slides/python-net/pt/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/pt/aspose.slides.charts/trendline/backward/) | Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende antes<br/>            dos dados da série que está sendo analisada. Em gráficos de dispersão e não dispersão, o valor deverá ser qualquer valor não negativo.<br/>            Leitura/gravação **float**. |
| [`forward`](/slides/python-net/pt/aspose.slides.charts/trendline/forward/) | Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende após os<br/>            dados da série que está sendo analisada. Em gráficos de dispersão e não dispersão, o valor deverá ser qualquer valor não negativo.<br/>            Leitura/gravação **float**. |
| [`intercept`](/slides/python-net/pt/aspose.slides.charts/trendline/intercept/) | Especifica o valor onde a linha de tendência cruza o eixo y. Esta propriedade será suportada somente<br/>            quando o tipo de linha de tendência for exp, linear ou poly.<br/>            Leitura/gravação **float**. |
| [`display_equation`](/slides/python-net/pt/aspose.slides.charts/trendline/display_equation/) | Especifica que a equação da linha de tendência é exibida no gráfico (no mesmo rótulo que o valor de Rsquared).<br/>            Leitura/gravação **bool**. |
| [`order`](/slides/python-net/pt/aspose.slides.charts/trendline/order/) | Especifica a ordem da linha de tendência polinomial. É ignorado para outros tipos de linha de tendência. O valor deve estar entre 2 e 6.<br/>            Leitura/gravação **int**. |
| [`period`](/slides/python-net/pt/aspose.slides.charts/trendline/period/) | Especifica o período da linha de tendência para uma linha de tendência de média móvel. É ignorado para outras<br/>            variantes de linha de tendência. O valor deve estar entre 2 e 255.<br/>            Leitura/gravação **int**. |
| [`display_r_squared_value`](/slides/python-net/pt/aspose.slides.charts/trendline/display_r_squared_value/) | Especifica que o valor R-quadrado da linha de tendência é exibido no gráfico (no mesmo rótulo que a equação).<br/>            Leitura/gravação **bool**. |
| [`related_legend_entry`](/slides/python-net/pt/aspose.slides.charts/trendline/related_legend_entry/) | Representa a entrada da legenda relacionada a esta linha de tendência<br/>            Somente leitura [`ILegendEntryProperties`](/slides/python-net/pt/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/pt/aspose.slides.charts/trendline/text_frame_for_overriding/) | Pode conter um texto formatado rico. Se esta propriedade não for None, então este <br/>            valor de texto formatado substitui o texto auto-gerado do rótulo de dados.<br/>            Texto auto-gerado do rótulo de dados significa o texto gerenciado por ShowSeriesName, <br/>            ShowValue, ... propriedades e formatado com a propriedade TextFormatManager.TextFormat.<br/>            Somente leitura [`ITextFrame`](/slides/python-net/pt/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/pt/aspose.slides.charts/trendline/text_format/) | Retorna o formato de texto.<br/>            Somente leitura [`IChartTextFormat`](/slides/python-net/pt/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/pt/aspose.slides.charts/trendline/chart/) | Retorna o gráfico pai.<br/>            Somente leitura [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/pt/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides.charts/trendline/presentation/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/pt/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | Inicializa TextFrameForOverriding com o texto no parâmetro "text".<br/>            Se TextFrameForOverriding já estiver inicializado, então simplesmente altera seu texto. |


### Ver também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)