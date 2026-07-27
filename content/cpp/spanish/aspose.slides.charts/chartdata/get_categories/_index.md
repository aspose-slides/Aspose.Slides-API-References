---
title: get_Categories()
second_title: Referencia de API de Aspose.Slides para C++
description: "Obtiene las categorías principales (o tanto las categorías principales como las secundarias si ChartData::set_UseSecondaryCategories se establece en false). Solo lectura IChartCategoryCollection."
type: docs
weight: 40
url: /es/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() method

Obtiene las categorías principales (o tanto las categorías principales como las secundarias si [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) se establece en false). Solo lectura [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## Observaciones

Si [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) se establece en false entonces [ChartData::get_SecondaryCategories](../get_secondarycategories/) devuelve null y los datos en [ChartData::get_Categories](./) se utilizan tanto para series primarias como secundarias. Si [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) se establece en true entonces los datos en [ChartData::get_SecondaryCategories](../get_secondarycategories/) se utilizan para series secundarias y los datos en [ChartData::get_Categories](./) se utilizan para series primarias.

Ejemplo. ¿Qué categorías están relacionadas con las series - [ChartData::get_Categories](./) o [ChartData::get_SecondaryCategories](../get_secondarycategories/)?
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