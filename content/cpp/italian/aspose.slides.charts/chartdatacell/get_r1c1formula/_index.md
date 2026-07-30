---
title: get_R1C1Formula()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene la formula nello stile R1C1.
type: docs
weight: 79
url: /it/aspose.slides.charts/chartdatacell/get_r1c1formula/
---
## ChartDataCell::get_R1C1Formula() metodo

Ottiene la formula nello stile R1C1.

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_R1C1Formula() override
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