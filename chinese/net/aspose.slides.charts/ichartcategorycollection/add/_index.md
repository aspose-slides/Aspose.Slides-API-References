---
title: Add
second_title: Aspose.Slides for .NET API 参考
description: 如果集合中存在类别则返回它否则从 创建新的图表类别IChartDataCellaspose.slides.charts/ichartdatacell并将其添加到集合中
type: docs
weight: 40
url: /zh/net/aspose.slides.charts/ichartcategorycollection/add/
---
## Add(IChartDataCell) {#add}

如果集合中存在类别，则返回它。否则从 创建新的图表类别[`IChartDataCell`](../../ichartdatacell)并将其添加到集合中。

```csharp
public IChartCategory Add(IChartDataCell chartDataCell)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| chartDataCell | IChartDataCell | 用于创建图表类别的单元格。 |

### 返回值

添加或现有类别。

### 也可以看看

* interface [IChartCategory](../../ichartcategory)
* interface [IChartDataCell](../../ichartdatacell)
* interface [IChartCategoryCollection](../../ichartcategorycollection)
* 命名空间 [Aspose.Slides.Charts](../../ichartcategorycollection)
* 部件 [Aspose.Slides](../../../)

---

## Add(object) {#add_1}

创建新的[`IChartCategory`](../../ichartcategory)从值并将其添加到集合中。

```csharp
public IChartCategory Add(object value)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | Object | 价值。 |

### 返回值

添加[`IChartCategory`](../../ichartcategory).

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| InvalidOperationException | 如果超出限制 |

### 评论

此方法添加名称为 AUTO_DATA 的工作表并在那里添加所有值。如果你使用[`IChartDataWorkbook`](../../ichartdataworkbook)要添加或编辑单元格值，请确保不要使用此工作表 使用此方法添加的值的最大数量不得超过 16711680

### 也可以看看

* interface [IChartCategory](../../ichartcategory)
* interface [IChartCategoryCollection](../../ichartcategorycollection)
* 命名空间 [Aspose.Slides.Charts](../../ichartcategorycollection)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
