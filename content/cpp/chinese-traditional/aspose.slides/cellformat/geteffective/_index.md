---
title: GetEffective()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得套用繼承與表格樣式後的有效表格儲存格格式屬性。
type: docs
weight: 118
url: /zh-hant/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() 方法

取得套用繼承與表格樣式後的有效表格儲存格格式屬性。

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```

### 回傳值

一個 [ICellFormatEffectiveData](../../icellformateffectivedata/)。

## 備註

此範例示範取得不同表格邏輯部份的有效填充格式。請注意，儲存格格式的優先權永遠高於列格式，列格式高於欄格式，欄格式高於整個表格。因此最終會使用 CellFormatEffectiveData 屬性來繪製表格。以下程式碼僅為 API 範例。 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// 輸出與比較
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ICellFormatEffectiveData](../../icellformateffectivedata/)
* 類別 [CellFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)