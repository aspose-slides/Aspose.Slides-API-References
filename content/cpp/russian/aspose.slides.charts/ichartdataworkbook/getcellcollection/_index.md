---
title: GetCellCollection()
second_title: Aspose.Slides для C++ API Reference
description: Получает набор ячеек.
type: docs
weight: 27
url: /ru/aspose.slides.charts/ichartdataworkbook/getcellcollection/
---
## IChartDataWorkbook::GetCellCollection(System::String, bool) method

Получает набор ячеек.

```cpp
virtual System::SharedPtr<IChartCellCollection> Aspose::Slides::Charts::IChartDataWorkbook::GetCellCollection(System::String formula, bool skipHiddenCells)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) формула вида "Sheet1!$A$2:$A$5". |
| skipHiddenCells | **bool** | Если true, метод возвращает коллекцию без скрытых ячеек. |

### Возвращаемое значение

Набор ячеек [IChartCellCollection](../../ichartcellcollection/)

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IChartCellCollection](../../ichartcellcollection/)
* Класс [String](../../../system/string/)
* Класс [IChartDataWorkbook](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)