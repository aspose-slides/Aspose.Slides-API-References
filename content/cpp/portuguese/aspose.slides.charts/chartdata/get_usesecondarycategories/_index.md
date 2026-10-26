---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides para C++ Referência da API
description: "Se definido como false então ChartData::get_SecondaryCategories retorna null e os dados em ChartData::get_Categories são usados tanto para séries primárias quanto secundárias. Se definido como true então os dados em ChartData::get_SecondaryCategories são usados para séries secundárias e os dados em ChartData::get_Categories são usados para séries primárias. Leia bool."
type: docs
weight: 53
url: /pt/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() método


Se definido como false então [ChartData::get_SecondaryCategories](../get_secondarycategories/) retorna null e os dados em [ChartData::get_Categories](../get_categories/) são usados tanto para séries primárias quanto secundárias. Se definido como true então os dados em [ChartData::get_SecondaryCategories](../get_secondarycategories/) são usados para séries secundárias e os dados em [ChartData::get_Categories](../get_categories/) são usados para séries primárias. Leia **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## Observações


Exemplo. Quais categorias estão relacionadas às séries - [ChartData::get_Categories](../get_categories/) ou [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // as categorias relacionadas são series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // as categorias relacionadas são series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Ver também

* Classe [ChartData](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)