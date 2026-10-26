---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет коллекцию легенд.
type: docs
url: /ru/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Представляет коллекцию легенд.

## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает свойства пункта легенды, соответствующего Chart.ChartData.Series[0].DataPoints[index] в случае типа диаграммы из следующего списка: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; или соответствующего Chart.ChartData.Series[index] для остальных типов диаграмм. |
| [getCount()](#getCount--) | Возвращает количество элементов, фактически содержащихся в коллекции. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

Получает свойства пункта легенды, соответствующего Chart.ChartData.Series[0].DataPoints[index] в случае типа диаграммы из следующего списка: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; или соответствующего Chart.ChartData.Series[index] для остальных типов диаграмм.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возврат:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getCount() {#getCount--}
```
public abstract int getCount()
```

Возвращает количество элементов, фактически содержащихся в коллекции. Только для чтения int.

**Возврат:**
int