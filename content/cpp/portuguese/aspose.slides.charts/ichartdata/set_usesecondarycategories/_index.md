---
title: set_UseSecondaryCategories()
second_title: Referência da API Aspose.Slides para C++
description: "Se definido como false, então IChartData::get_SecondaryCategories retorna null e os dados em IChartData::get_Categories são usados tanto para séries primárias quanto secundárias. Se definido como true, então os dados em IChartData::get_SecondaryCategories são usados para séries secundárias e os dados em IChartData::get_Categories são usados para séries primárias. Escreva bool."
type: docs
weight: 66
url: /pt/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) método

Se definido como false, então [IChartData::get_SecondaryCategories](../get_secondarycategories/) retorna null e os dados em [IChartData::get_Categories](../get_categories/) são usados tanto para séries primárias quanto secundárias. Se definido como true, então os dados em [IChartData::get_SecondaryCategories](../get_secondarycategories/) são usados para séries secundárias e os dados em [IChartData::get_Categories](../get_categories/) são usados para séries primárias. Escreva **bool**.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## Observações

Exemplo. Quais categorias estão relacionadas às séries - ChartData.Categories ou ChartData.SecondaryCategories?
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

* Classe [IChartData](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)