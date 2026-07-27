---
title: get_ErrorBarsXFormat()
second_title: Referencia de API de Aspose.Slides para C++
description: Representa ErrorBars de series con dirección X.
type: docs
weight: 222
url: /es/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() método

Representa ErrorBars de la serie con dirección X.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## Observaciones

ErrorBars con dirección X están disponibles para series de tipo area, bar, scatter y bubble. Para cualquier otro tipo de gráfico esta propiedad devuelve null (incluidos los gráficos 3D). En caso de valores personalizados use la colección DataPoints para especificar el valor (con la propiedad [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Solo lectura [IErrorBarsFormat](../../ierrorbarsformat/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IErrorBarsFormat](../../ierrorbarsformat/)
* Clase [IChartSeries](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)