---
title: CalculateFormulas
second_title: Aspose.Slides for .NET API 参考
description: 计算工作簿中的所有公式并更新相应的单元格值
type: docs
weight: 20
url: /zh/aspose.slides.charts/chartdataworkbook/calculateformulas/
---
## ChartDataWorkbook.CalculateFormulas method

计算工作簿中的所有公式并更新相应的单元格值。

```csharp
public void CalculateFormulas()
```

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [CellCircularReferenceException](../../../aspose.slides.spreadsheet/cellcircularreferenceexception) | 工作簿包含带有循环引用的公式。 |
| [CellUnsupportedDataException](../../../aspose.slides.spreadsheet/cellunsupporteddataexception) | 单元格数据不受支持。 |

### 例子

示例显示如何将公式分配给单元格并计算值。 “B4”单元格的值设置为 5。

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.Pie, 100, 100, 300, 400);
    IChartDataWorkbook wb = chart.ChartData.ChartDataWorkbook;
    wb.GetCell(0, "B2", 2);	
	wb.GetCell(0, "B3", 3);	
    wb.GetCell(0, "B4").Formula = "B2+B3";
    wb.CalculateFormulas();
    ...
}
```

### 也可以看看

* class [ChartDataWorkbook](../../chartdataworkbook)
* 命名空间 [Aspose.Slides.Charts](../../chartdataworkbook)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
