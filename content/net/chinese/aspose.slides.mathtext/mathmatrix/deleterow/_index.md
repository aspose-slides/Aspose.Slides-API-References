---
title: DeleteRow
second_title: Aspose.Sildes for .NET API Reference
description: 删除指定行
type: docs
weight: 130
url: /zh/aspose.slides.mathtext/mathmatrix/deleterow/
---

## MathMatrix.DeleteRow 方法

删除指定行

```csharp
public void DeleteRow(int rowIndex)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rowIndex | Int32 | 要删除的行的零基索引。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 当你尝试删除矩阵中的最后一行时 |
| ArgumentOutOfRangeException | 如果 rowIndex 小于零或大于或等于 RowCount |

### 示例

示例:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.DeleteRow(0);
```

### 另见

* class [MathMatrix](../../mathmatrix)
* namespace [Aspose.Slides.MathText](../../mathmatrix)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->