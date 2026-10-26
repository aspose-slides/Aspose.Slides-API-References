---
title: set_R1C1Formula()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece la fórmula en estilo R1C1.
type: docs
weight: 92
url: /es/aspose.slides.charts/ichartdatacell/set_r1c1formula/
---
## IChartDataCell::set_R1C1Formula(System::String) método


Establece la fórmula en estilo R1C1.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_R1C1Formula(System::String value)=0
```

## Observaciones



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [IChartDataCell](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)