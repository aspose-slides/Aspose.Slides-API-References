---
title: get_PieSplitBy()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pie-of-pie o bar-of-pie. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre, es una proyección de la propiedad de grupo correspondiente. Por lo tanto, esta propiedad es de solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use get_ParentSeriesGroup()->get(set)_PieSplitBy() como propiedad de lectura/escritura para cambiar el valor. Solo lectura PieSplitType.
type: docs
weight: 729
url: /es/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() método

Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pie-of-pie o bar-of-pie. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre, es una proyección de la propiedad de grupo correspondiente. Por lo tanto, esta propiedad es de solo lectura. Utilice la propiedad ParentSeriesGroup para acceder al grupo de series padre. Utilice la propiedad [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() de lectura/escritura para cambiar el valor. Solo lectura [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## Comentarios

1) Esta es la proyección de la propiedad [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Si el valor de la propiedad es [PieSplitType::Custom](../../piesplittype/) entonces puede definir información de división personalizada con la propiedad [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Ver también

* Enumeración [PieSplitType](../../piesplittype/)
* Clase [IChartSeries](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)