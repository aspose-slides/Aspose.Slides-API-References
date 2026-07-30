---
title: set_R1C1Formula()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta la formula in stile R1C1.
type: docs
weight: 92
url: /it/aspose.slides.charts/ichartdatacell/set_r1c1formula/
---
## IChartDataCell::set_R1C1Formula(System::String) method

Imposta la formula in stile R1C1.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_R1C1Formula(System::String value)=0
```

## Osservazioni

```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IChartDataCell](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)