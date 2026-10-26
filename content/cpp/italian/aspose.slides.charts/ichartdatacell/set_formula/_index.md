---
title: set_Formula()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta la formula nello stile A1.
type: docs
weight: 66
url: /it/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) metodo


Imposta la formula in stile A1.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
```

## Osservazioni



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IChartDataCell](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)