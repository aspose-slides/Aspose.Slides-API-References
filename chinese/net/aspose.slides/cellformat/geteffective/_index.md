---
title: GetEffective
second_title: Aspose.Slides for .NET API 参考
description: 获取有效的表格单元格格式属性并应用了继承和表格样式
type: docs
weight: 80
url: /zh/net/aspose.slides/cellformat/geteffective/
---
## CellFormat.GetEffective method

获取有效的表格单元格格式属性，并应用了继承和表格样式。

```csharp
public ICellFormatEffectiveData GetEffective()
```

### 返回值

A[`ICellFormatEffectiveData`](../../icellformateffectivedata)。

### 例子

此示例演示了为不同的表逻辑部分获取有效的填充格式。 请注意，单元格格式的优先级始终高于行格式，行 - 高于列，列 - 高于整个表格。 所以最后 CellFormatEffectiveData 属性总是用来绘制表格。以下代码只是 API 的一个示例。

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
    ITable tbl = pres.Slides[0].Shapes[0] as ITable;
    IFillFormatEffectiveData tableFillFormatEffective = tbl.TableFormat.GetEffective().FillFormat;
    IFillFormatEffectiveData rowFillFormatEffective = tbl.Rows[0].RowFormat.GetEffective().FillFormat;
    IFillFormatEffectiveData columnFillFormatEffective = tbl.Columns[0].ColumnFormat.GetEffective().FillFormat;
    IFillFormatEffectiveData cellFillFormatEffective = tbl[0, 0].CellFormat.GetEffective().FillFormat;
    /* Output and comparison */
}
```

### 也可以看看

* interface [ICellFormatEffectiveData](../../icellformateffectivedata)
* class [CellFormat](../../cellformat)
* 命名空间 [Aspose.Slides](../../cellformat)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->