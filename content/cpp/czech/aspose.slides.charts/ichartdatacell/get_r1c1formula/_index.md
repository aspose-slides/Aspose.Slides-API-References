---
title: get_R1C1Formula()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Získá vzorec ve stylu R1C1.
type: docs
weight: 79
url: /cs/aspose.slides.charts/ichartdatacell/get_r1c1formula/
---
## IChartDataCell::get_R1C1Formula() metoda


Získá vzorec ve stylu R1C1.

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_R1C1Formula()=0
```

## Poznámky



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [IChartDataCell](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)