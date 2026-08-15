---
title: GetEffective()
second_title: Aspose.Slides for C++ API 參考
description: 取得套用繼承與表格樣式後的有效表格格式屬性。
type: docs
weight: 40
url: /zh-hant/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() 方法


取得套用繼承與表格樣式後的有效表格格式屬性。

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```


### 返回值

一個 [ITableFormatEffectiveData](../../itableformateffectivedata/).
## 備註



此範例示範如何取得不同表格邏輯部分的有效填滿格式。請注意，儲存格格式的優先權始終高於列格式，列高於欄，欄高於整個表格。因此最終仍使用 CellFormatEffectiveData 屬性來繪製表格。以下程式碼僅為 API 範例。
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ITableFormatEffectiveData](../../itableformateffectivedata/)
* 類別 [TableFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)