---
title: set_R1C1Formula()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta la formula in stile R1C1.
type: docs
weight: 92
url: /it/aspose.slides.charts/chartdatacell/set_r1c1formula/
---
## ChartDataCell::set_R1C1Formula(System::String) metodo


Imposta la formula nello stile R1C1.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_R1C1Formula(System::String value) override
```

## Osservazioni



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [ChartDataCell](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)