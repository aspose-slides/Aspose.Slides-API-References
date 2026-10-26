---
title: set_Formula()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает формулу в стиле A1.
type: docs
weight: 66
url: /ru/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) метод


Устанавливает формулу в стиле A1.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
```

## Примечания



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## См. также

* Класс [String](../../../system/string/)
* Класс [IChartDataCell](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)