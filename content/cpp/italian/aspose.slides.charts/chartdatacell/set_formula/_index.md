---
title: set_Formula()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta la formula nello stile A1.
type: docs
weight: 66
url: /it/aspose.slides.charts/chartdatacell/set_formula/
---
## ChartDataCell::set_Formula(System::String) metodo


Imposta la formula nello stile A1.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Formula(System::String value) override
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