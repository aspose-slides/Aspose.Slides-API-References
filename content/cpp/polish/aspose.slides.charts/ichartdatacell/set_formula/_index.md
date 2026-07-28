---
title: set_Formula()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Ustawia formułę w stylu A1.
type: docs
weight: 66
url: /pl/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) metoda


Ustawia formułę w stylu A1.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
```

## Uwagi



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IChartDataCell](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)