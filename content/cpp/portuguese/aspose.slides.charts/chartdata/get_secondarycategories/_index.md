---
title: get_SecondaryCategories()
second_title: Referência da API Aspose.Slides para C++
description: "Obtém as categorias secundárias se ChartData::get_UseSecondaryCategories for verdadeiro. Somente leitura IChartCategoryCollection."
type: docs
weight: 79
url: /pt/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() método


Obtém as categorias secundárias se [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) é verdadeiro. Somente leitura [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## Observações


Se [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) for definido como falso então [ChartData::get_SecondaryCategories](./) retorna nulo e os dados em [ChartData::get_Categories](../get_categories/) são usados tanto para a série primária quanto para a secundária. Se [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) for definido como verdadeiro, então os dados em [ChartData::get_SecondaryCategories](./) são usados para a série secundária e os dados em [ChartData::get_Categories](../get_categories/) são usados para a série primária. 

Exemplo. Quais categorias estão relacionadas à série - [ChartData::get_Categories](../get_categories/) ou [ChartData::get_SecondaryCategories](./)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // categorias relacionadas são series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // categorias relacionadas são series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartCategoryCollection](../../ichartcategorycollection/)
* Classe [ChartData](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)