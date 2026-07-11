---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Контейнер уровней точек данных.
type: docs
url: /ru/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Контейнер уровней точек данных. Применяется для серий Treeamp и Sunburst. Индексация уровней точек данных начинается с нуля.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Возвращает объект IChartDataPointLevel для указанного уровня. |
| [getCount()](#getCount--) | Возвращает количество уровней точек данных. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
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
public abstract int getCount()
```


Возвращает количество уровней точек данных.

**Возвращаемое значение:**
int