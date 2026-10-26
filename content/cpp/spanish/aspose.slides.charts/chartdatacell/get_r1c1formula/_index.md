---
title: get_R1C1Formula()
second_title: Referencia API de Aspose.Slides para C++
description: Obtiene la fórmula en estilo R1C1.
type: docs
weight: 79
url: /es/aspose.slides.charts/chartdatacell/get_r1c1formula/
---
## ChartDataCell::get_R1C1Formula() método


Obtiene la fórmula en estilo R1C1.

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_R1C1Formula() override
```

## Observaciones



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## Véase también

* Clase [String](../../../system/string/)
* Clase [ChartDataCell](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)