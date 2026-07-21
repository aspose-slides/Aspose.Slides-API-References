---
title: get_R1C1Formula()
second_title: Aspose.Slides для C++ справочник API
description: Получает формулу в стиле R1C1.
type: docs
weight: 79
url: /ru/aspose.slides.charts/ichartdatacell/get_r1c1formula/
---
## IChartDataCell::get_R1C1Formula() метод

Получает формулу в стиле R1C1.

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_R1C1Formula()=0
```

## Примечания



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## См. также

* Класс [String](../../../system/string/)
* Класс [IChartDataCell](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)