---
title: get_Formula()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene la fórmula en estilo A1.
type: docs
weight: 53
url: /es/aspose.slides.charts/ichartdatacell/get_formula/
---
## IChartDataCell::get_Formula() método


Obtiene la fórmula en estilo A1.

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_Formula()=0
```

## Observaciones



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [IChartDataCell](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)