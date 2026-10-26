---
title: set_range method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Define o intervalo de dados do gráfico. Séries e categorias serão atualizadas com base no novo intervalo de dados.
Se a quantidade de séries no intervalo de dados for maior que a contagem de séries nos dados do gráfico, então séries adicionais do mesmo tipo da última série na coleção atual serão adicionadas ao final da coleção.

```python
def set_range(self, formula):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| formula | **str** | A fórmula de intervalo de dados das células. Ex.: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula é None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Tipo de gráfico não suportado |
| **RuntimeError(Proxy error(ArgumentException))** | formula tem formato incorreto. |

### Veja Também
* classe [`ChartData`](/slides/python-net/pt/aspose.slides.charts/chartdata)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)