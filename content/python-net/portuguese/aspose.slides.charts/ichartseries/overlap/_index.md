---
title: overlap property
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## propriedade overlap
Especifica o quanto as barras e colunas se sobrepõem em gráficos 2-D, como uma porcentagem (de -100% a 100%).
            Esta é a propriedade não apenas desta série, mas de todas as séries do grupo de séries pai.
            É uma projeção da propriedade apropriada no grupo de séries pai, portanto esta propriedade é somente leitura.
            Para alterar o valor, use a propriedade de leitura/gravação ParentSeriesGroup.Overlap.
            Somente leitura **int**.

### Observações

Overlap especifica o grau de sobreposição ou espaçamento entre barras e colunas como uma porcentagem da largura delas:
            - -100%: Espaçamento máximo (as barras estão completamente separadas).
            - 0%: As barras são colocadas lado a lado sem sobreposição ou espaçamento.
            - 100%: Sobreposição máxima (as barras se sobrepõem completamente).
            Esta é uma projeção da propriedade ParentSeriesGroup.Overlap.

### Definição:
```python
@property
def overlap(self):
    ...
```

### Veja Também
* classe [`IChartSeries`](/slides/python-net/pt/aspose.slides.charts/ichartseries)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)