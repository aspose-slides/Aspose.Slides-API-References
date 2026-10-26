---
title: get_R1C1Formula()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Získá vzorec ve stylu R1C1.
type: docs
weight: 79
url: /cs/aspose.slides.charts/chartdatacell/get_r1c1formula/
---
## ChartDataCell::get_R1C1Formula() method


Získá vzorec ve stylu R1C1.

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_R1C1Formula() override
```

## Poznámky



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [ChartDataCell](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)