---
title: get_Overlap()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100% a 100%). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series principal. Es una proyección de la propiedad correspondiente en el grupo de series principal, por lo que esta propiedad es de solo lectura. Para cambiar el valor, use la get_ParentSeriesGroup()->get(set)_Overlap() propiedad de lectura/escritura. Solo lectura int8_t.
type: docs
weight: 690
url: /es/aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() método


Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100 % a 100 %). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series principal. Es una proyección de la propiedad correspondiente en el grupo de series principal, por lo que esta propiedad es de solo lectura. Para cambiar el valor, utilice la [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() propiedad de lectura/escritura. Solo lectura **int8_t**.

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## Observaciones


La superposición especifica el grado de solapamiento o espacio entre barras y columnas como un porcentaje de su ancho:
* -100 %: Espaciado máximo (las barras están completamente separadas).
* 0 %: Las barras se colocan una al lado de la otra sin solapamiento ni espacio.
* 100 %: Solapamiento máximo (las barras se superponen completamente entre sí). Esta es una proyección de la propiedad [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap().

## Ver también

* Clase [IChartSeries](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)