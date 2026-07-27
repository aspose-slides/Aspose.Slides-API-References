---
title: GetRange()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el rango de datos del gráfico.
type: docs
weight: 157
url: /es/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() método


Obtiene el rango de datos del gráfico.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### Valor devuelto

Fórmula del rango de datos de celdas. Por ejemplo: \"Sheet1!$A$1:$C$4\"
## Observaciones




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [ChartData](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)