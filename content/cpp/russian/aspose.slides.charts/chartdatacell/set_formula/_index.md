---
title: set_Formula()
second_title: Aspose.Slides для C++ API Reference
description: Устанавливает формулу в стиле A1.
type: docs
weight: 66
url: /ru/aspose.slides.charts/chartdatacell/set_formula/
---
## ChartDataCell::set_Formula(System::String) метод

Устанавливает формулу в стиле A1.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Formula(System::String value) override
```

## Примечания



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## См. также

* Класс [String](../../../system/string/)
* Класс [ChartDataCell](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)