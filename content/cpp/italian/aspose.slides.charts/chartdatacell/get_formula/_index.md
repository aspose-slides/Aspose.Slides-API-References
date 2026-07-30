---
title: get_Formula()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene la formula in stile A1.
type: docs
weight: 53
url: /it/aspose.slides.charts/chartdatacell/get_formula/
---
## ChartDataCell::get_Formula() metodo


Ottiene la formula in stile A1.

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_Formula() override
```

## Osservazioni



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [ChartDataCell](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)