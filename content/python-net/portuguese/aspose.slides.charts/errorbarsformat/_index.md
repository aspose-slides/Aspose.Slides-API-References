---
title: ErrorBarsFormat class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat classe

Representa as barras de erro da série de gráfico. Os valores personalizados de ErrorBars estão em IChartDataPointCollection (na propriedade [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).

O tipo ErrorBarsFormat expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/pt/aspose.slides.charts/errorbarsformat/type/) | Obtém ou define o tipo das barras de erro. <br/>            Leitura/ gravação [`ErrorBarType`](/slides/python-net/pt/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/pt/aspose.slides.charts/errorbarsformat/value_type/) | Representa as possíveis maneiras de determinar o comprimento das barras de erro. <br/>            No caso de tipo de valor personalizado para especificar o valor, use a propriedade [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) do ponto de dados específico na coleção DataPoints da série.<br/>            No caso de tipos de valor Fixed, Percentage ou StandardDeviation, use a propriedade Value para especificar o valor.  <br/>            Leitura/ gravação [`ErrorBarValueType`](/slides/python-net/pt/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/pt/aspose.slides.charts/errorbarsformat/has_end_cap/) | Especifica que uma tampa final não é desenhada nas barras de erro.<br/>            Leitura/ gravação **bool**. |
| [`value`](/slides/python-net/pt/aspose.slides.charts/errorbarsformat/value/) | Obtém ou define o valor que é usado com os tipos de valor Fixed, Percentage e StandardDeviation para determinar o comprimento das barras de erro. <br/>            Em qualquer outro caso retornará NaN.<br/>            Leitura/ gravação **float**. |
| [`format`](/slides/python-net/pt/aspose.slides.charts/errorbarsformat/format/) | Representa o formato das barras de erro.<br/>            Leitura/ gravação [`IFormat`](/slides/python-net/pt/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/pt/aspose.slides.charts/errorbarsformat/chart/) | Retorna o gráfico pai.<br/>            Somente leitura [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/pt/aspose.slides.charts/errorbarsformat/is_visible/) | Obtém ou define a visibilidade das barras de erro.<br/>            Leitura/ gravação **bool**. |
| [`slide`](/slides/python-net/pt/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides.charts/errorbarsformat/presentation/) |  |

### Veja Também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)