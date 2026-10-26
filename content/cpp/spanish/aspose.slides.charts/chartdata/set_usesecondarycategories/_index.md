---
title: set_UseSecondaryCategories()
second_title: Referencia de API de Aspose.Slides para C++
description: "Si se establece en false, entonces ChartData::get_SecondaryCategories devuelve null y los datos en ChartData::get_Categories se utilizan tanto para series primarias como secundarias. Si se establece en true, los datos en ChartData::get_SecondaryCategories se utilizan para series secundarias y los datos en ChartData::get_Categories se utilizan para series primarias. Escriba bool."
type: docs
weight: 66
url: /es/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) método


Si se establece en false, entonces [ChartData::get_SecondaryCategories](../get_secondarycategories/) devuelve null y los datos en [ChartData::get_Categories](../get_categories/) se utilizan tanto para series primarias como secundarias. Si se establece en true, los datos en [ChartData::get_SecondaryCategories](../get_secondarycategories/) se utilizan para series secundarias y los datos en [ChartData::get_Categories](../get_categories/) se utilizan para series primarias. Escriba **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## Observaciones


Ejemplo. ¿Qué categorías están relacionadas con series - [ChartData::get_Categories](../get_categories/) o [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

## Véase también

* Clase [ChartData](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)