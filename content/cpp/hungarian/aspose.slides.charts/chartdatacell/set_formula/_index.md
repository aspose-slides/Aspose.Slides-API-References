---
title: set_Formula()
second_title: Aspose.Slides C++-hoz API referencia
description: Beállítja a képletet A1-stílusban.
type: docs
weight: 66
url: /hu/aspose.slides.charts/chartdatacell/set_formula/
---
## ChartDataCell::set_Formula(System::String) metódus


Beállítja a képletet A1-stílusban.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Formula(System::String value) override
```

## Megjegyzések



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [ChartDataCell](../)
* Névtere [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)