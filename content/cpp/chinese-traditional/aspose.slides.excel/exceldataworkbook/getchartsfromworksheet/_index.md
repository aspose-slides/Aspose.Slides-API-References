---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 檢索一個字典，其中包含指定 Excel 工作簿工作表中所有圖表的索引和名稱。
type: docs
weight: 40
url: /zh-hant/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) 方法


檢索一個字典，該字典包含指定 [Excel](../../) 工作簿中工作表的所有圖表的索引和名稱。

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 要搜尋圖表的工作表名稱。 |

### 返回值

此字典的鍵是圖表索引，值是圖表名稱。
## 備註



範例: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## 另請參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IDictionary](../../../system.collections.generic/idictionary/)
* 類別 [String](../../../system/string/)
* 類別 [ExcelDataWorkbook](../)
* 命名空間 [Aspose::Slides::Excel](../../)
* 函式庫 [Aspose.Slides](../../../)