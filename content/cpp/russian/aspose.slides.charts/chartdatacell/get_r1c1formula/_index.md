---
title: get_R1C1Formula()
second_title: Aspose.Slides для справочного руководства API C++
description: Получает формулу в стиле R1C1.
type: docs
weight: 79
url: /ru/aspose.slides.charts/chartdatacell/get_r1c1formula/
---
## ChartDataCell::get_R1C1Formula() метод


Получает формулу в стиле R1C1.

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_R1C1Formula() override
```

## Примечания


```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C3Formula(u"MAX(R2C6:R5C8) / 3");
```

## См. также

* Класс [String](../../../system/string/)
* Класс [ChartDataCell](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)