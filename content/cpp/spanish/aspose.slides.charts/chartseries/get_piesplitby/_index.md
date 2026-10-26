---
title: get_PieSplitBy()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-sobre-pastel o barra-sobre-pastel. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre, es la proyección de la propiedad del grupo correspondiente. Por lo tanto, esta propiedad es de solo lectura. Utilice la propiedad ParentSeriesGroup para acceder al grupo de series padre. Utilice get_ParentSeriesGroup()->get(set)_PieSplitBy() como propiedad de lectura/escritura para cambiar el valor. Solo lectura PieSplitType.
type: docs
weight: 755
url: /es/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() método

Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-sobre-pastel o barra-sobre-pastel. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre, es la proyección de la propiedad correspondiente del grupo. Por lo tanto, esta propiedad es de solo lectura. Utilice la propiedad ParentSeriesGroup para acceder al grupo de series padre. Utilice la propiedad [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() de lectura/escritura para cambiar el valor. Solo lectura [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## Observaciones

1) Esta es la proyección de la propiedad [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Si el valor de la propiedad es [PieSplitType::Custom](../../piesplittype/), entonces puede definir información de división personalizada con la propiedad [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Ver también

* Enumeración [PieSplitType](../../piesplittype/)
* Clase [ChartSeries](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)