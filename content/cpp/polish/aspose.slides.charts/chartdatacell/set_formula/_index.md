---
title: set_Formula()
second_title: Aspose.Slides dla C++ - referencja API
description: Ustawia formułę w stylu A1.
type: docs
weight: 66
url: /pl/aspose.slides.charts/chartdatacell/set_formula/
---
## ChartDataCell::set_Formula(System::String) metoda


Ustawia formułę w stylu A1.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Formula(System::String value) override
```

## Uwagi



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [ChartDataCell](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)