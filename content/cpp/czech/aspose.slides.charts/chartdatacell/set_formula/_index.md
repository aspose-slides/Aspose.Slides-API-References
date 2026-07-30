---
title: set_Formula()
second_title: Aspose.Slides pro referenci API C++
description: Nastaví vzorec ve stylu A1.
type: docs
weight: 66
url: /cs/aspose.slides.charts/chartdatacell/set_formula/
---
## ChartDataCell::set_Formula(System::String) metoda


Nastaví vzorec ve stylu A1.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Formula(System::String value) override
```

## Poznámky



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [ChartDataCell](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)