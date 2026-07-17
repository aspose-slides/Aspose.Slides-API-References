---
title: GetEffective()
second_title: Aspose.Slides C++ API 参考
description: 获取在继承和表格样式应用后的有效表格单元格格式属性。
type: docs
weight: 118
url: /zh/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() 方法

获取在继承和表格样式应用后的有效表格单元格格式属性。

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```

### 返回值

A [ICellFormatEffectiveData](../../icellformateffectivedata/).

## 备注

此示例演示了如何获取不同表格逻辑部分的有效填充格式。请注意，单元格格式始终优先于行格式，行格式优先于列格式，列格式优先于整个表格。因此最终使用 CellFormatEffectiveData 属性来绘制表格。以下代码仅作为 API 示例。 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// 输出和比较
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ICellFormatEffectiveData](../../icellformateffectivedata/)
* 类 [CellFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)