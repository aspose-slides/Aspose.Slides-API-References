---
title: SetRange
second_title: Aspose.Slides for .NET API 参考
description: 设置图表数据范围系列和类别将根据新的数据范围进行更新 如果数据范围内的系列数量大于图表数据中系列的数量则与当前集合中的最后一个系列具有相同类型 的其他系列将添加到集合结束
type: docs
weight: 120
url: /zh/net/aspose.slides.charts/ichartdata/setrange/
---
## IChartData.SetRange method

设置图表数据范围。系列和类别将根据新的数据范围进行更新。 如果数据范围内的系列数量大于图表数据中系列的数量，则与当前集合中的最后一个系列具有相同类型 的其他系列将添加到集合结束。

```csharp
public void SetRange(string formula)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formula | String | 单元格数据范围公式。例如:“Sheet1!$A$1:$C$4”、“SomeSheetName!A1:B100”、“Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5”。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 公式为空。 |
| ArgumentException | 公式格式不正确。 |

### 也可以看看

* interface [IChartData](../../ichartdata)
* 命名空间 [Aspose.Slides.Charts](../../ichartdata)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->