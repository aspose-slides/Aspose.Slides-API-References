---
title: GetRange
second_title: Справочник по API Aspose.Slides для .NET
description: Получает диапазон данных диаграммы.
type: docs
weight: 90
url: /ru/net/aspose.slides.charts/ichartdata/getrange/
---
## IChartData.GetRange method

Получает диапазон данных диаграммы.

```csharp
public string GetRange()
```

### Возвращаемое значение

Формула диапазона данных ячеек. Например:"Sheet1!$A$1:$C$4"

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Диаграмма не использует рабочую книгу в качестве источника данных |

### Примеры

Пример C#

```csharp
using (Presentation pres = new Presentation())
{
    IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
    string result = (chart.ChartData as ChartData).GetRange();
}
```

### Смотрите также

* interface [IChartData](../../ichartdata)
* пространство имен [Aspose.Slides.Charts](../../ichartdata)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->