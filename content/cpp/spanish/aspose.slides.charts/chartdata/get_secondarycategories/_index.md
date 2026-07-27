---
title: get_SecondaryCategories()
second_title: Referencia de API de Aspose.Slides para C++
description: "Obtiene las categorías secundarias si ChartData::get_UseSecondaryCategories es verdadero. Solo lectura IChartCategoryCollection."
type: docs
weight: 79
url: /es/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() método

Obtiene las categorías secundarias si [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) es verdadero. Solo lectura [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## Observaciones

Si [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) se establece en false entonces [ChartData::get_SecondaryCategories](./) devuelve null y los datos en [ChartData::get_Categories](../get_categories/) se utilizan tanto para la serie primaria como para la secundaria. Si [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) se establece en true entonces los datos en [ChartData::get_SecondaryCategories](./) se utilizan para la serie secundaria y los datos en [ChartData::get_Categories](../get_categories/) se utilizan para la serie primaria. 

Ejemplo. ¿Qué categorías están relacionadas con la serie - [ChartData::get_Categories](../get_categories/) o [ChartData::get_SecondaryCategories](./)? 
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
* Clase [ChartData](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)