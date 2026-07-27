---
title: set_Formula()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece la fórmula en formato A1.
type: docs
weight: 66
url: /es/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) método


Establece la fórmula en formato A1.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
```

## Observaciones



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Véase también

* Clase [String](../../../system/string/)
* Clase [IChartDataCell](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)