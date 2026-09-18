---
title: overlap property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## overlap propriedade
Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). 
            Esta é a propriedade não apenas desta série, mas de todas as séries do grupo de séries pai. 
            É uma projeção da propriedade apropriada no grupo de séries pai, e portanto esta propriedade é somente leitura.
            Para alterar o valor, use a propriedade de leitura/gravação **ParentSeriesGroup.Overlap**.
            Somente leitura **int**.

### Observações

Overlap especifica o grau de sobreposição ou espaçamento entre barras e colunas como uma porcentagem de sua largura:
            - -100%: Espaçamento máximo (as barras estão completamente separadas).
            - 0%: As barras são posicionadas lado a lado sem sobreposição ou espaçamento.
            - 100%: Sobreposição máxima (as barras se sobrepõem completamente).
            Esta é uma projeção da propriedade **ParentSeriesGroup.Overlap**.

### Definição:
```python
@property
def overlap(self):
    ...
```

### Veja Também
* classe [`ChartSeries`](/slides/python-net/pt/aspose.slides.charts/chartseries)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)