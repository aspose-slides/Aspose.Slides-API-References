---
title: set_R1C1Formula()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece la fórmula en estilo R1C1.
type: docs
weight: 92
url: /es/aspose.slides.charts/chartdatacell/set_r1c1formula/
---
## ChartDataCell::set_R1C1Formula(System::String) método

Establece la fórmula en estilo R1C1.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_R1C1Formula(System::String value) override
```

## Observaciones



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [ChartDataCell](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)