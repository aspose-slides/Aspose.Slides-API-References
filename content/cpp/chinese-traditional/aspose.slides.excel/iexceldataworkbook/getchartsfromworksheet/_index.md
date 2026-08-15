---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides for C++ API 參考
description: 檢索一個字典，其中包含指定工作表中所有圖表的索引和名稱，屬於 Excel 工作簿。
type: docs
weight: 27
url: /zh-hant/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) 方法


檢索一個字典，其中包含指定工作表中所有圖表的索引和名稱，屬於 [Excel](../../) 工作簿。

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 要搜尋圖表的工作表名稱。 |

### 返回值

A dictionary where the key is the chart index and the value is the chart name.
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

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IDictionary](../../../system.collections.generic/idictionary/)
* 類別 [String](../../../system/string/)
* 類別 [IExcelDataWorkbook](../)
* 命名空間 [Aspose::Slides::Excel](../../)
* 程式庫 [Aspose.Slides](../../../)