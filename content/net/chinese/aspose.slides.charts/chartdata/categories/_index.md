---
title: Categories
second_title: Aspose.Slides for .NET API 参考
description: 获取主要类别或主要和次要类别 ifUseSecondaryCategoriesaspose.slides.charts/chartdata/usesecondarycategories属性为假 只读IChartCategoryCollectionaspose.slides.charts/ichartcategorycollection
type: docs
weight: 10
url: /zh/aspose.slides.charts/chartdata/categories/
---
## ChartData.Categories property

获取主要类别（或主要和次要类别 if[`UseSecondaryCategories`](../usesecondarycategories)属性为假）。 只读[`IChartCategoryCollection`](../../ichartcategorycollection)。

```csharp
public IChartCategoryCollection Categories { get; }
```

### 评论

如果[`UseSecondaryCategories`](../usesecondarycategories)属性为 false 则[`SecondaryCategories`](../secondarycategories) 属性返回 null 并且此Categories属性用于主要 和次要系列。 如果[`UseSecondaryCategories`](../usesecondarycategories)属性为真，则SecondaryCategories中的数据 属性用于次要系列，并且此`Categories`属性用于主要数据 系列。

### 例子

示例。哪些类别与系列相关 - ChartData.Categories 或 ChartData.SecondaryCategories？

```csharp
if (series.PlotOnSecondAxis && series.Chart.ChartData.UseSecondaryCategories)
{
     // 相关类别为 series.Chart.ChartData.SecondaryCategories
}
else
{
     // 相关类别为 series.Chart.ChartData.Categories
}
```

### 也可以看看

* interface [IChartCategoryCollection](../../ichartcategorycollection)
* class [ChartData](../../chartdata)
* 命名空间 [Aspose.Slides.Charts](../../chartdata)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
