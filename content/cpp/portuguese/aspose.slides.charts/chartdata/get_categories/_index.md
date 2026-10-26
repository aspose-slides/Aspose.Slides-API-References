---
title: get_Categories()
second_title: Aspose.Slides para C++ Referência da API
description: "Obtém as categorias primárias (ou tanto as categorias primárias quanto as secundárias se ChartData::set_UseSecondaryCategories for definido como false). Somente leitura IChartCategoryCollection."
type: docs
weight: 40
url: /pt/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() método

Obtém as categorias primárias (ou tanto as categorias primárias quanto as secundárias se [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) estiver definido como false). Somente leitura [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## Observações

Se [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) estiver definido como false então [ChartData::get_SecondaryCategories](../get_secondarycategories/) retornará null e os dados em [ChartData::get_Categories](./) serão usados tanto para séries primárias quanto para séries secundárias. Se [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) estiver definido como true então os dados em [ChartData::get_SecondaryCategories](../get_secondarycategories/) serão usados para séries secundárias e os dados em [ChartData::get_Categories](./) serão usados para séries primárias. 

Exemplo. Quais categorias estão relacionadas à série - [ChartData::get_Categories](./) ou [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartCategoryCollection](../../ichartcategorycollection/)
* Classe [ChartData](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)