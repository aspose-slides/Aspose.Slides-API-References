---
title: get_R1C1Formula()
second_title: Referencja API Aspose.Slides dla C++
description: Pobiera formułę w stylu R1C1.
type: docs
weight: 79
url: /pl/aspose.slides.charts/chartdatacell/get_r1c1formula/
---
## ChartDataCell::get_R1C1Formula() metoda


Pobiera formułę w stylu R1C1.

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_R1C1Formula() override
```

## Uwagi



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [ChartDataCell](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)