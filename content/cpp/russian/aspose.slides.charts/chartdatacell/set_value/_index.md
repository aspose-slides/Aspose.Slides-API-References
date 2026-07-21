---
title: set_Value()
second_title: Aspose.Slides для C++ справочник API
description: "Устанавливает значение ячейки. Запишите System::Object."
type: docs
weight: 40
url: /ru/aspose.slides.charts/chartdatacell/set_value/
---
## ChartDataCell::set_Value(System::SharedPtr\<System::Object\>) метод


Устанавливает значение ячейки. Запишите [System::Object](../../../system/object/).

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Value(System::SharedPtr<System::Object> value) override
```

## Примечания



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```


## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [ChartDataCell](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)