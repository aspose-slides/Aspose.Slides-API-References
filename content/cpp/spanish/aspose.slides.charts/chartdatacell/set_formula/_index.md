---
title: set_Formula()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece la fórmula en estilo A1.
type: docs
weight: 66
url: /es/aspose.slides.charts/chartdatacell/set_formula/
---
## ChartDataCell::set_Formula(System::String) método


Establece la fórmula en estilo A1.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Formula(System::String value) override
```

## Observaciones


```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [ChartDataCell](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)