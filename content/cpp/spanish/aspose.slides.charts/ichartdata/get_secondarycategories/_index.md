---
title: get_SecondaryCategories()
second_title: Aspose.Slides para C++ Referencia de API
description: "Obtiene las categorías secundarias si IChartData::get_UseSecondaryCategories es verdadero. Solo lectura IChartCategoryCollection."
type: docs
weight: 79
url: /es/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() método

Obtiene las categorías secundarias si [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) es verdadero. Solo lectura [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## Observaciones

Si [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) se establece en false entonces [IChartData::get_SecondaryCategories](./) devuelve null y los datos en [IChartData::get_Categories](../get_categories/) se usan tanto para la serie primaria como para la secundaria. Si [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) se establece en true entonces los datos en [IChartData::get_SecondaryCategories](./) se usan para la serie secundaria y los datos en [IChartData::get_Categories](../get_categories/) se usan para la serie primaria.

Ejemplo. ¿Qué categorías están relacionadas con la serie - ChartData.Categories o ChartData.SecondaryCategories?
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // las categorías relacionadas son series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // las categorías relacionadas son series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IChartCategoryCollection](../../ichartcategorycollection/)
* Clase [IChartData](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)