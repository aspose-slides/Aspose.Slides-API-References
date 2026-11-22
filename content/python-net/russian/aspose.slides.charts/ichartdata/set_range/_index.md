---
title: set_range method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/ichartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
Устанавливает диапазон данных диаграммы. Серии и категории будут обновлены на основе нового диапазона данных.
Если количество серий в диапазоне данных превышает количество серий в данных диаграммы, то дополнительные серии того же типа, что и последняя серия в текущей коллекции, будут добавлены в конец коллекции.

```python
def set_range(self, formula):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| formula | **str** | Формула диапазона данных ячеек. Например: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Исключения

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula равно None. |
| **RuntimeError(Proxy error(ArgumentException))** | formula имеет неверный формат. |

### См. также
* класс [`IChartData`](/slides/python-net/ru/aspose.slides.charts/ichartdata)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)