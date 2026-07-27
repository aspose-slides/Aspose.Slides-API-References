---
title: get_Categories()
second_title: Aspose.Slides para C++ Referência da API
description: "Obtém as categorias principais (ou tanto as categorias principais quanto as secundárias se IChartData::set_UseSecondaryCategories estiver definido como false). Somente leitura IChartCategoryCollection."
type: docs
weight: 40
url: /pt/aspose.slides.charts/ichartdata/get_categories/
---
## método IChartData::get_Categories() 

Obtém as categorias principais (ou tanto as categorias principais quanto as secundárias se [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) estiver definido como false). Somente leitura [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## Observações

Se [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) estiver definido como false, então [IChartData::get_SecondaryCategories](../get_secondarycategories/) retornará null e os dados em [IChartData::get_Categories](./) serão usados tanto para séries primárias quanto secundárias. Se [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) estiver definido como true, então os dados em [IChartData::get_SecondaryCategories](../get_secondarycategories/) serão usados para séries secundárias e os dados em [IChartData::get_Categories](./) serão usados para séries primárias. 

Exemplo. Quais categorias estão relacionadas às séries - ChartData.Categories ou ChartData.SecondaryCategories? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // related categories are series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // related categories are series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartCategoryCollection](../../ichartcategorycollection/)
* Classe [IChartData](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)