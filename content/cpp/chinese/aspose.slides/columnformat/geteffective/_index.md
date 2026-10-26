---
title: GetEffective()
second_title: Aspose.Slides for C++ API 参考
description: 获取在继承和表格样式应用后的有效表列格式属性。
type: docs
weight: 1
url: /zh/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() method

获取在继承和表格样式应用后的有效表列格式属性。

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```

### 返回值

一个 [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)。
## 备注

此示例演示如何获取不同表格逻辑部分的有效填充格式。请注意，单元格格式始终具有比行格式更高的优先级，行格式比列格式更高，列格式比整个表格更高。因此最终始终使用 CellFormatEffectiveData 属性来绘制表格。以下代码仅作为 API 示例。 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// 输出和比较
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* 类 [ColumnFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)