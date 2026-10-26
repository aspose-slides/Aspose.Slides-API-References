---
title: set_range method
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Установить диапазон данных диаграммы. Серии и категории будут обновлены на основе нового диапазона данных.
Если количество серий в диапазоне данных превышает количество серий в данных диаграммы, то дополнительные серии того же типа, что и последняя серия в текущей коллекции, будут добавлены в конец коллекции.


```python
def set_range(self, formula):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| formula | **str** | Формула диапазона данных ячеек. Например: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula имеет значение None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Неподдерживаемый тип диаграммы |
| **RuntimeError(Proxy error(ArgumentException))** | у formula неправильный формат. |



### См. также
* класс [`ChartData`](/slides/python-net/ru/aspose.slides.charts/chartdata)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)