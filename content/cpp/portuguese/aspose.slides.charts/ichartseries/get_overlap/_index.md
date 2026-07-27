---
title: get_Overlap()
second_title: Referência da API Aspose.Slides para C++
description: Especifica o quanto as barras e colunas se sobrepõem em gráficos 2-D, como uma porcentagem (de -100% a 100%). Esta é a propriedade não apenas desta série, mas de todas as séries do grupo de séries pai. É uma projeção da propriedade apropriada no grupo de séries pai, e por isso essa propriedade é somente leitura. Para alterar o valor, use a get_ParentSeriesGroup()->get(set)_Overlap() propriedade leitura/gravação. Somente leitura int8_t.
type: docs
weight: 690
url: /pt/aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() método


Overlap especifica o quanto as barras e colunas se sobrepõem em gráficos 2-D, como uma porcentagem (de -100% a 100%). Esta é a propriedade não apenas desta série, mas de todas as séries do grupo de séries pai. É uma projeção da propriedade apropriada no grupo de séries pai, e por isso essa propriedade é somente leitura. Para alterar o valor, use a [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() propriedade leitura/gravação. Somente leitura **int8_t**.

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## Observações


Overlap especifica o grau de sobreposição ou espaçamento entre barras e colunas como uma porcentagem de sua largura:* -100%: Espaçamento máximo (as barras estão completamente separadas).
* 0%: As barras são posicionadas lado a lado sem sobreposição ou espaçamento.
* 100%: Sobreposição máxima (as barras se sobrepõem completamente). Esta é uma projeção da propriedade [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap().


## Ver também

* Classe [IChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)