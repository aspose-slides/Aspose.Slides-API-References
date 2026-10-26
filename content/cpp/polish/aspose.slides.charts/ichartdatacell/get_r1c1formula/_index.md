---
title: get_R1C1Formula()
second_title: Aspose.Slides dla C++ – referencja API
description: Pobiera formułę w stylu R1C1.
type: docs
weight: 79
url: /pl/aspose.slides.charts/ichartdatacell/get_r1c1formula/
---
## IChartDataCell::get_R1C1Formula() metoda


Pobiera formułę w stylu R1C1.

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_R1C1Formula()=0
```

## Uwagi



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IChartDataCell](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)