---
title: GetEffective()
second_title: Aspose.Slides for C++ API 參考
description: 取得套用繼承與表格樣式後的有效表格欄位格式屬性。
type: docs
weight: 1
url: /zh-hant/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() 方法

取得套用繼承與表格樣式後的有效表格欄位格式屬性。

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```

### Return Value

A [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).
## 備註

此範例示範取得不同表格邏輯部分的有效填充格式。請注意，儲存格格式始終比列格式具有更高的優先權，列格式比欄格式優先，欄格式比整個表格優先。因此最終會使用 CellFormatEffectiveData 屬性來繪製表格。以下程式碼僅為 API 的示例。 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// 輸出與比較
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* 類別 [ColumnFormat](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)