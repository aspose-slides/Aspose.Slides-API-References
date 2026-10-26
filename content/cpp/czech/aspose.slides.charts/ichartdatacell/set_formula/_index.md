---
title: set_Formula()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastaví vzorec ve stylu A1.
type: docs
weight: 66
url: /cs/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) metoda


Nastaví vzorec ve stylu A1.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
```

## Poznámky



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [IChartDataCell](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)