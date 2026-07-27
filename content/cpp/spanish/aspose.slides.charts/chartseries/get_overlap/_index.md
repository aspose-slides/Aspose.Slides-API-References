---
title: get_Overlap()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100% a 100%). Esta es una propiedad no solo de esta serie sino de todas las series del grupo de series padre. Es una proyección de la propiedad correspondiente en el grupo de series padre, por lo que esta propiedad es de solo lectura. Para cambiar el valor, use la propiedad de lectura/escritura get_ParentSeriesGroup()->Overlap(). Solo de lectura int8_t.
type: docs
weight: 690
url: /es/aspose.slides.charts/chartseries/get_overlap/
---
## ChartSeries::get_Overlap() método

Especifica cuánto se solapan las barras y columnas en gráficos 2-D, como un porcentaje (de -100% a 100%). Esta es una propiedad no solo de esta serie sino de todas las series del grupo de series padre. Es una proyección de la propiedad correspondiente en el grupo de series padre, por lo que esta propiedad es de solo lectura. Para cambiar el valor, use el [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) propiedad de lectura/escritura. Solo de lectura **int8_t**.

```cpp
int8_t Aspose::Slides::Charts::ChartSeries::get_Overlap() override
```

## Observaciones

La superposición especifica el grado de superposición o espaciado entre barras y columnas como un porcentaje de su ancho:
* -100%: Espaciado máximo (las barras están completamente separadas).
* 0%: Las barras se colocan una al lado de la otra sin superposición ni espaciado.
* 100%: Superposición máxima (las barras se superponen completamente entre sí). Esta es una proyección de la propiedad [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/).

## Ver también

* Clase [ChartSeries](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)