---
title: set_R1C1Formula()
second_title: Aspose.Slides pro C++ API Reference
description: Nastaví vzorec ve stylu R1C1.
type: docs
weight: 92
url: /cs/aspose.slides.charts/chartdatacell/set_r1c1formula/
---
## ChartDataCell::set_R1C1Formula(System::String) metoda


Nastaví vzorec ve stylu R1C1.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_R1C1Formula(System::String value) override
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