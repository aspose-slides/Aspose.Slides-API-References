---
title: DeleteColumn
second_title: Aspose.Slides for .NET API 参考
description: 删除指定列
type: docs
weight: 120
url: /zh/aspose.slides.mathtext/mathmatrix/deletecolumn/
---
## MathMatrix.DeleteColumn method

删除指定列

```csharp
public void DeleteColumn(int columnIndex)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | Int32 | 从零开始的索引要删除的列。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| InvalidOperationException | 当您尝试删除矩阵中的最后一列时 |
| ArgumentOutOfRangeException | 如果 columnIndex 小于零或大于或等于 ColumnCount |

### 例子

示例:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.DeleteColumn(0);
```

### 也可以看看

* class [MathMatrix](../../mathmatrix)
* 命名空间 [Aspose.Slides.MathText](../../mathmatrix)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
