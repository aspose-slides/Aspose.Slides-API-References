---
title: get_SecondaryCategories()
second_title: Referência da API Aspose.Slides para C++
description: "Obtém as categorias secundárias se IChartData::get_UseSecondaryCategories for true. Somente leitura IChartCategoryCollection."
type: docs
weight: 79
url: /pt/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() method


Obtém as categorias secundárias se [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) for true. Somente leitura [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## Observações


Se [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) for definido como false então [IChartData::get_SecondaryCategories](./) retorna null e os dados em [IChartData::get_Categories](../get_categories/) são usados tanto para a série primária quanto para a secundária. Se [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) for definido como true então os dados em [IChartData::get_SecondaryCategories](./) são usados para a série secundária e os dados em [IChartData::get_Categories](../get_categories/) são usados para a série primária. 

Exemplo. Quais categorias estão relacionadas à série - ChartData.Categories ou ChartData.SecondaryCategories? 
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategoryCollection](../../ichartcategorycollection/)
* Class [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)