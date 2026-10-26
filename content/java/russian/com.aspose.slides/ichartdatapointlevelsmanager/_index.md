---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Container of data point levels.
type: docs
url: /ru/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Контейнер уровней точек данных. Применяется для серий Treeamp и Sunburst. Индексация уровней точек данных начинается с нуля.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returns IChartDataPointLevel object for defined level. |
| [getCount()](#getCount--) | Returns data point levels count. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```

Возвращает объект IChartDataPointLevel для указанного уровня.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| level | int |  |

**Возвращает:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Возвращает количество уровней точек данных.

**Возвращает:**
int