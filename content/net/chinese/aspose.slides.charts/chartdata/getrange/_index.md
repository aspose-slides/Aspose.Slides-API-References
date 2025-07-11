---
title: GetRange
second_title: Aspose.Sildes for .NET API Reference
description: 获取图表数据范围。
type: docs
weight: 90
url: /zh/aspose.slides.charts/chartdata/getrange/
---

## ChartData.GetRange 方法

获取图表数据范围。

```csharp
public string GetRange()
```

### 返回值

单元格数据范围公式。示例: "Sheet1!$A$1:$C$4"

### 异常

| exception | condition |
| --- | --- |
| InvalidOperationException | 图表未使用工作簿作为数据源 |

### 示例

示例 C#

```csharp
using (Presentation pres = new Presentation())
{
    IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
    string result = (chart.ChartData as ChartData).GetRange();
}
```

### 另见

* class [ChartData](../../chartdata)
* namespace [Aspose.Slides.Charts](../../chartdata)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->