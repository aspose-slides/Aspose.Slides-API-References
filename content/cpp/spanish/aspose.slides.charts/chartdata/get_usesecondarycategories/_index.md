---
title: get_UseSecondaryCategories()
second_title: Referencia de API de Aspose.Slides para C++
description: "Si se establece en false entonces ChartData::get_SecondaryCategories devuelve null y los datos en ChartData::get_Categories se utilizan tanto para series primarias como secundarias. Si se establece en true entonces los datos en ChartData::get_SecondaryCategories se utilizan para series secundarias y los datos en ChartData::get_Categories se utilizan para series primarias. Leer bool."
type: docs
weight: 53
url: /es/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() método

Si se establece en false entonces [ChartData::get_SecondaryCategories](../get_secondarycategories/) devuelve null y los datos en [ChartData::get_Categories](../get_categories/) se utilizan tanto para series primarias como secundarias. Si se establece en true entonces los datos en [ChartData::get_SecondaryCategories](../get_secondarycategories/) se utilizan para series secundarias y los datos en [ChartData::get_Categories](../get_categories/) se utilizan para series primarias. Leer **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## Observaciones

Ejemplo. ¿Qué categorías están relacionadas con la serie - [ChartData::get_Categories](../get_categories/) o [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

* Clase [ChartData](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)