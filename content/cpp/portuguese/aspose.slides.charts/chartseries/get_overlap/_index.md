---
title: get_Overlap()
second_title: Aspose.Slides para C++ Referência da API
description: Especifica o quanto as barras e colunas se sobrepõem em gráficos 2-D, como uma porcentagem (de -100% a 100%). Esta é a propriedade não apenas desta série, mas de todas as séries do grupo de séries pai. É uma projeção da propriedade apropriada no grupo de séries pai e, portanto, esta propriedade é somente leitura. Para alterar o valor, use a propriedade read/write get_ParentSeriesGroup()->Overlap(). Somente leitura int8_t.
type: docs
weight: 690
url: /pt/aspose.slides.charts/chartseries/get_overlap/
---
## ChartSeries::get_Overlap() método


Especifica o quanto as barras e colunas se sobrepõem em gráficos 2-D, como uma porcentagem (de -100% a 100%). Esta é a propriedade não apenas desta série, mas de todas as séries do grupo de séries pai. É uma projeção da propriedade apropriada no grupo de séries pai e, portanto, esta propriedade é somente leitura. Para alterar o valor, use a propriedade [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) leitura/gravação. Somente leitura **int8_t**.

```cpp
int8_t Aspose::Slides::Charts::ChartSeries::get_Overlap() override
```

## Observações


A sobreposição especifica o grau de sobreposição ou espaçamento entre barras e colunas como uma porcentagem de sua largura:* -100%: Espaçamento máximo (as barras estão completamente separadas).
* 0%: As barras são colocadas lado a lado sem sobreposição ou espaçamento.
* 100%: Sobreposição máxima (as barras se sobrepõem completamente). Esta é uma projeção da propriedade [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/).

## Veja Também

* Classe [ChartSeries](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)