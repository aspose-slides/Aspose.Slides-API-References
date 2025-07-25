---
title: GetOrCreateDataPointByIdx
second_title: Aspose.Slides для .NET API Справочник
description: Если коллекция уже содержит точку данных с индексом index, то возвращает эту точку данных. Если коллекция не содержит точку данных с индексом indexN, когда число точек данных в этой коллекции меньше или равно N, то добавляет недостающие точки данных и возвращает последнюю, которая имеет запрашиваемый индекс. Например, индексы коллекции - 0, 1, 2, а запрашиваемый индекс - 5. Затем метод добавляет недостающие точки данных 0, 1, 2, 3, 4, 5. И возвращает точку данных с индексом 5.
type: docs
weight: 300
url: /ru/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---

## ChartDataPointCollection.GetOrCreateDataPointByIdx метод

Если коллекция уже содержит точку данных с индексом *index*, то возвращает эту точку данных. Если коллекция не содержит точку данных с индексом *index*==N (когда число точек данных в этой коллекции меньше или равно N), то добавляет недостающие точки данных и возвращает последнюю (которая имеет запрашиваемый индекс). Например, индексы коллекции - {0, 1, 2}, а запрашиваемый индекс - 5. Затем метод добавляет недостающие точки данных: {0, 1, 2, 3, 4, 5}. И возвращает точку данных с индексом 5.

```csharp
public IChartDataPoint GetOrCreateDataPointByIdx(uint index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | UInt32 | Индекс. |

### Возвращаемое значение

Возвращает точку данных с запрашиваемым индексом.

### См. также

* интерфейс [IChartDataPoint](../../ichartdatapoint)
* класс [ChartDataPointCollection](../../chartdatapointcollection)
* пространство имен [Aspose.Slides.Charts](../../chartdatapointcollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->