---
title: LegendEntryCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию легенд.
type: docs
url: /ru/com.aspose.slides/legendentrycollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

Представляет коллекцию легенд.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает свойства элемента легенды, соответствующего Chart.ChartData.Series[0].DataPoints[index], если тип диаграммы из следующего списка: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; или соответствующего Chart.ChartData.Series[index] для остальных типов диаграмм. |
| [getCount()](#getCount--) | Получает количество элементов легенды. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

Получает свойства элемента легенды, соответствующего Chart.ChartData.Series[0].DataPoints[index], если тип диаграммы из следующего списка: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; или соответствующего Chart.ChartData.Series[index] для остальных типов диаграмм.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```

Получает количество элементов легенды. Только для чтения int.

**Возвращаемое значение:**
int