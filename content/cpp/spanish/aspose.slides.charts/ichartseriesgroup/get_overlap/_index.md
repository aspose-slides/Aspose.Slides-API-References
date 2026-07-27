---
title: get_Overlap()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica cuánto deben superponerse las barras y columnas en gráficos 2-D, como un porcentaje (de -100% a 100%).
type: docs
weight: 183
url: /es/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() método

Especifica cuánto deben superponerse las barras y columnas en gráficos 2-D, como un porcentaje (de -100% a 100%).

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## Observaciones

* -100%: Espaciado máximo (las barras están completamente separadas).
* 0%: Las barras se colocan una al lado de la otra sin superposición ni espaciado.
* 100%: Superposición máxima (las barras se superponen completamente entre sí). Esta propiedad es de lectura/escritura **int8_t**.

El siguiente ejemplo muestra cómo establecer la superposición para un grupo de series de gráfico y renderizar el gráfico resultante en un formulario: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Establecer superposición al 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## Ver también

* Clase [IChartSeriesGroup](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)