---
title: get_PieSplitBy()
second_title: Referência da API Aspose.Slides para C++
description: Especifica como determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico de pizza-sobre-pizza ou barra-sobre-pizza. Esta é a propriedade não apenas desta série, mas de todas as séries do grupo de séries pai - é a projeção da propriedade apropriada do grupo. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use get_ParentSeriesGroup()->get(set)_PieSplitBy() propriedade de leitura/gravação para alterar o valor. Somente leitura PieSplitType.
type: docs
weight: 755
url: /pt/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() método

Especifica como determinar quais pontos de dados estão no segundo pizza ou barra em um gráfico de pizza-sobre-pizza ou barra-sobre-pizza. Esta é a propriedade não apenas desta série, mas de todas as séries do grupo de séries pai – é a projeção da propriedade apropriada do grupo. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() propriedade de leitura/gravação para alterar o valor. Somente leitura [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## Observações

1) Esta é a projeção da propriedade [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Se o valor da propriedade for [PieSplitType::Custom](../../piesplittype/) então você pode definir informações de divisão personalizadas com a propriedade [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Veja Também

* Enum [PieSplitType](../../piesplittype/)
* Classe [ChartSeries](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)