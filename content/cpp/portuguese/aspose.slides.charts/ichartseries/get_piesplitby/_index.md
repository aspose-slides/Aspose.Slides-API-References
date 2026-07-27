---
title: get_PieSplitBy()
second_title: Referência da API Aspose.Slides para C++
description: Especifica como determinar quais pontos de dados estão no segundo pedaço ou barra em um gráfico de pizza dentro de pizza ou barra dentro de pizza. Esta é a propriedade não apenas desta série, mas de todas as séries do grupo de séries pai – isso é a projeção da propriedade de grupo apropriada. Portanto, essa propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use get_ParentSeriesGroup()->get(set)_PieSplitBy() propriedade de leitura/gravação para alterar o valor. Somente leitura PieSplitType.
type: docs
weight: 729
url: /pt/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() método

Especifica como determinar quais pontos de dados estão no segundo pedaço ou barra em um gráfico de pizza dentro de pizza ou barra dentro de pizza. Esta é a propriedade não apenas desta série, mas de todas as séries do grupo de séries pai – isso é a projeção da propriedade de grupo apropriada. E, portanto, essa propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() propriedade de leitura/gravação para alterar o valor. Somente leitura [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## Observações

1) Esta é a projeção da propriedade [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy().
2) Se o valor da propriedade é [PieSplitType::Custom](../../piesplittype/) então você pode definir informações de divisão personalizadas com a propriedade [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Veja Também

* Enum [PieSplitType](../../piesplittype/)
* Classe [IChartSeries](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)