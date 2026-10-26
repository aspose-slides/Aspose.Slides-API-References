---
title: get_Categories()
second_title: Referencia de API de Aspose.Slides para C++
description: "Obtiene las categorías primarias (o tanto las categorías primarias como secundarias si IChartData::set_UseSecondaryCategories está configurado a false). Solo lectura IChartCategoryCollection."
type: docs
weight: 40
url: /es/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() método

Obtiene las categorías primarias (o tanto las categorías primarias como secundarias si [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) está configurado a false). Solo lectura [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## Observaciones

Si [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) está configurado a false, entonces [IChartData::get_SecondaryCategories](../get_secondarycategories/) devuelve null y los datos en [IChartData::get_Categories](./) se utilizan tanto para series primarias como secundarias. Si [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) está configurado a true, entonces los datos en [IChartData::get_SecondaryCategories](../get_secondarycategories/) se utilizan para series secundarias y los datos en [IChartData::get_Categories](./) se utilizan para series primarias. 

Ejemplo. ¿Qué categorías están relacionadas con las series - ChartData.Categories o ChartData.SecondaryCategories? 
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

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IChartCategoryCollection](../../ichartcategorycollection/)
* Clase [IChartData](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)