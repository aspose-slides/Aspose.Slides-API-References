---
title: ITable
second_title: Aspose.Slides for .NET API 参考
description: 表示幻灯片上的表格
type: docs
weight: 6650
url: /zh/aspose.slides/itable/
---
## ITable interface

表示幻灯片上的表格。

```csharp
public interface ITable : IBulkTextFormattable, IGraphicalObject
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AsIBulkTextFormattable](../../aspose.slides/itable/asibulktextformattable) { get; } | 允许获取基本的 IBulkTextFormattable 接口。 只读[`IBulkTextFormattable`](../ibulktextformattable)。 |
| [AsIGraphicalObject](../../aspose.slides/itable/asigraphicalobject) { get; } | 允许获取基本 IGraphicalObject 接口。 只读[`IGraphicalObject`](../igraphicalobject)。 |
| [Columns](../../aspose.slides/itable/columns) { get; } | 返回列的集合。 只读[`IColumnCollection`](../icolumncollection)。 |
| [FirstCol](../../aspose.slides/itable/firstcol) { get; set; } | 确定表格的第一列是否必须以特殊格式绘制。 读/写Boolean。 |
| [FirstRow](../../aspose.slides/itable/firstrow) { get; set; } | 确定表格的第一行是否必须以特殊格式绘制。 读/写Boolean。 |
| [HorizontalBanding](../../aspose.slides/itable/horizontalbanding) { get; set; } | 确定偶数行是否必须以不同的格式绘制。 读/写Boolean。 |
| [Item](../../aspose.slides/itable/item) { get; } | 返回指定列和行索引处的单元格。 只读[`ICell`](../icell)。 |
| [LastCol](../../aspose.slides/itable/lastcol) { get; set; } | 确定表格的最后一列是否必须以特殊格式绘制。 读/写Boolean。 |
| [LastRow](../../aspose.slides/itable/lastrow) { get; set; } | 确定表格的最后一行是否必须以特殊格式绘制。 读/写Boolean。 |
| [RightToLeft](../../aspose.slides/itable/righttoleft) { get; set; } | 判断表格是否有从右到左的阅读顺序。 读写Boolean。 |
| [Rows](../../aspose.slides/itable/rows) { get; } | 返回行的集合。 只读[`IRowCollection`](../irowcollection)。 |
| [StylePreset](../../aspose.slides/itable/stylepreset) { get; set; } | 获取或设置内置表格样式。 读/写[`TableStylePreset`](../tablestylepreset)。 |
| [TableFormat](../../aspose.slides/itable/tableformat) { get; } | 返回包含此表格式属性的 TableFormat 对象。 只读[`ITableFormat`](../itableformat)。 |
| [VerticalBanding](../../aspose.slides/itable/verticalbanding) { get; set; } | 确定偶数列是否必须以不同的格式绘制。 读/写Boolean。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [MergeCells](../../aspose.slides/itable/mergecells)(ICell, ICell, bool) | 合并相邻单元格。 |

### 也可以看看

* interface [IBulkTextFormattable](../ibulktextformattable)
* interface [IGraphicalObject](../igraphicalobject)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
