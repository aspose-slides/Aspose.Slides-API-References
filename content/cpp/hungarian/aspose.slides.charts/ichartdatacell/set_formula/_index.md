---
title: set_Formula()
second_title: Aspose.Slides for C++ API referencia
description: Beállítja a képletet A1-stílusban.
type: docs
weight: 66
url: /hu/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) metódus


Beállítja a képletet A1-stílusban.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
```

## Megjegyzések



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IChartDataCell](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)