---
title: IChartDataCell
second_title: Aspose.Slides for .NET API Reference
description: 表示图表数据的单元格。
type: docs
weight: 1730
url: /zh/aspose.slides.charts/ichartdatacell/
---

## IChartDataCell 接口

表示图表数据的单元格。

```csharp
public interface IChartDataCell
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ChartDataWorksheet](../../aspose.slides.charts/ichartdatacell/chartdataworksheet) { get; } | 获取工作表。只读 [`IChartDataWorksheet`](../ichartdataworksheet)。 |
| [Column](../../aspose.slides.charts/ichartdatacell/column) { get; } | 返回单元格所在工作表的列索引。只读 Int32。 |
| [CustomNumberFormat](../../aspose.slides.charts/ichartdatacell/customnumberformat) { get; set; } | 获取或设置数字和日期的自定义显示格式。如果值为空，将使用 PresetNumberFormat 值。可读写 String。 |
| [Formula](../../aspose.slides.charts/ichartdatacell/formula) { get; set; } | 获取或设置 A1 样式的公式。 |
| [IsHidden](../../aspose.slides.charts/ichartdatacell/ishidden) { get; } | 判断单元格是否隐藏。只读 Boolean。 |
| [PresetNumberFormat](../../aspose.slides.charts/ichartdatacell/presetnumberformat) { get; set; } | 获取或设置数字和日期的内置显示格式。预设数字必须在 [0..22] 或 [37..49] 之间。可读写 Byte。 |
| [R1C1Formula](../../aspose.slides.charts/ichartdatacell/r1c1formula) { get; set; } | 获取或设置 R1C1 样式的公式。 |
| [Row](../../aspose.slides.charts/ichartdatacell/row) { get; } | 返回单元格所在工作表的行索引。只读 Int32。 |
| [Value](../../aspose.slides.charts/ichartdatacell/value) { get; set; } | 获取或设置单元格的值。可读写 Object。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Calculate](../../aspose.slides.charts/ichartdatacell/calculate)(bool) | 如果单元格包含一个公式，则值将根据该公式更新。 |

### 另见

* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->