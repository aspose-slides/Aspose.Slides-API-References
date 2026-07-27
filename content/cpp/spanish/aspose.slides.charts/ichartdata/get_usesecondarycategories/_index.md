---
title: get_UseSecondaryCategories()
second_title: Referencia de API de Aspose.Slides para C++
description: "Si se establece en false entonces IChartData::get_SecondaryCategories devuelve null y los datos en IChartData::get_Categories se utilizan tanto para la serie primaria como para la secundaria. Si se establece en true entonces los datos en IChartData::get_SecondaryCategories se utilizan para la serie secundaria y los datos en IChartData::get_Categories se utilizan para la serie primaria. Leer bool."
type: docs
weight: 53
url: /es/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() método

Si se establece en false entonces [IChartData::get_SecondaryCategories](../get_secondarycategories/) devuelve null y los datos en [IChartData::get_Categories](../get_categories/) se utilizan tanto para la serie primaria como para la secundaria. Si se establece en true entonces los datos en [IChartData::get_SecondaryCategories](../get_secondarycategories/) se utilizan para la serie secundaria y los datos en [IChartData::get_Categories](../get_categories/) se utilizan para la serie primaria. Leer **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
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