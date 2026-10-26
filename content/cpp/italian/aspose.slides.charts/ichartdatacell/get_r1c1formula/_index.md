---
title: get_R1C1Formula()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la formula in stile R1C1.
type: docs
weight: 79
url: /it/aspose.slides.charts/ichartdatacell/get_r1c1formula/
---
## IChartDataCell::get_R1C1Formula() metodo


Restituisce la formula in stile R1C1.

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_R1C1Formula()=0
```

## Note



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IChartDataCell](../)
* Namespace [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)