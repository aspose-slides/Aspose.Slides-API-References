---
title: GetEffective
second_title: Aspose.Slides for .NET API Reference
description: 获取应用了继承和表样式的有效表格式属性。
type: docs
weight: 30
url: /zh/aspose.slides/tableformat/geteffective/
---

## TableFormat.GetEffective 方法

获取应用了继承和表样式的有效表格式属性。

```csharp
public ITableFormatEffectiveData GetEffective()
```

### 返回值

一个 [`ITableFormatEffectiveData`](../../itableformateffectivedata)。

### 示例

该示例演示了如何获取不同表逻辑部分的有效填充格式。请注意，单元格格式总是比行格式具有更高的优先级，而行格式又高于列格式，列格式又高于整个表。因此，最终 CellFormatEffectiveData 属性总是用于绘制表格。以下代码仅是 API 的一个示例。

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
    ITable tbl = pres.Slides[0].Shapes[0] as Table;
    IFillFormatEffectiveData tableFillFormatEffective = tbl.TableFormat.GetEffective().FillFormat;
    IFillFormatEffectiveData rowFillFormatEffective = tbl.Rows[0].RowFormat.GetEffective().FillFormat;
    IFillFormatEffectiveData columnFillFormatEffective = tbl.Columns[0].ColumnFormat.GetEffective().FillFormat;
    IFillFormatEffectiveData cellFillFormatEffective = tbl[0, 0].CellFormat.GetEffective().FillFormat;
    /* 输出和比较 */
}
```

### 另请参阅

* 接口 [ITableFormatEffectiveData](../../itableformateffectivedata)
* 类 [TableFormat](../../tableformat)
* 命名空间 [Aspose.Slides](../../tableformat)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->