---
title: set_UseSecondaryCategories()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Si se establece en false, entonces IChartData::get_SecondaryCategories devuelve null y los datos en IChartData::get_Categories se utilizan tanto para la serie primaria como para la secundaria. Si se establece en true, entonces los datos en IChartData::get_SecondaryCategories se utilizan para la serie secundaria y los datos en IChartData::get_Categories se utilizan para la serie primaria. Escriba bool."
type: docs
weight: 66
url: /es/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) método

Si se establece en false entonces [IChartData::get_SecondaryCategories](../get_secondarycategories/) devuelve null y los datos en [IChartData::get_Categories](../get_categories/) se usan tanto para la serie primaria como para la secundaria. Si se establece en true entonces los datos en [IChartData::get_SecondaryCategories](../get_secondarycategories/) se usan para la serie secundaria y los datos en [IChartData::get_Categories](../get_categories/) se usan para la serie primaria. Escriba **bool**.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## Observaciones

Ejemplo. ¿Qué categorías están relacionadas con las series - ChartData.Categories o ChartData.SecondaryCategories?
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

* Clase [IChartData](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)