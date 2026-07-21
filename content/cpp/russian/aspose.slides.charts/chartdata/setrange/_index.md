---
title: SetRange()
second_title: Aspose.Slides для C++ справочник API
description: Установите диапазон данных диаграммы. Series и categories будут обновлены на основе нового диапазона данных. Если количество series в диапазоне данных превышает количество series в данных диаграммы, то дополнительные series того же типа, что и последний series в текущей коллекции, будут добавлены в конец коллекции.
type: docs
weight: 170
url: /ru/aspose.slides.charts/chartdata/setrange/
---
## ChartData::SetRange(System::String) метод

Задаёт диапазон данных диаграммы. Series и категории будут обновлены на основе нового диапазона данных. Если количество series в диапазоне данных превышает количество series в данных диаграммы, то дополнительные series того же типа, что и последний series в текущей коллекции, будут добавлены в конец коллекции.

```cpp
void Aspose::Slides::Charts::ChartData::SetRange(System::String formula) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Формула диапазона данных ячеек. E.g: \"Sheet1!$A$1:$C$4\" , \"SomeSheetName!A1:B100\", \"Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5\". |

## См. также

* Класс [String](../../../system/string/)
* Класс [ChartData](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)