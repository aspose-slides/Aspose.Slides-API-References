---
title: ChartDataPointLevelsManager
second_title: Aspose.Slides для Android через Java API Reference
description: Контейнер уровней точек данных.
type: docs
url: /ru/com.aspose.slides/chartdatapointlevelsmanager/
---
**Наследование:**  
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**  
[com.aspose.slides.IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)  
```
public class ChartDataPointLevelsManager extends DomObject<ChartDataPoint> implements IChartDataPointLevelsManager
```

Контейнер уровней точек данных. Применяется для серий Treeamp и Sunburst. Индексация уровней точек данных начинается с нуля.

## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Возвращает объект IChartDataPointLevel для указанного уровня. |
| [getCount()](#getCount--) | Возвращает количество уровней точек данных. |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataPointLevel get_Item(int level)
```

Возвращает объект IChartDataPointLevel для указанного уровня.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| level | int |  |

**Возвращаемое значение:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public final int getCount()
```

Возвращает количество уровней точек данных.

**Возвращаемое значение:**
int