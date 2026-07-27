---
title: GetRange()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el rango de datos del gráfico.
type: docs
weight: 170
url: /es/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() método


Obtiene el rango de datos del gráfico.

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```


### Valor de retorno

Fórmula del rango de datos de celdas. Por ejemplo: \"Sheet1!$A$1:$C$4\"
## Observaciones




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [IChartData](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)