---
title: GetWorksheetNames()
second_title: Aspose.Slides for C++ API 參考
description: 檢索 Excel 活頁簿中包含的所有工作表名稱。
type: docs
weight: 53
url: /zh-hant/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() 方法


檢索 [Excel](../../) 工作簿中包含的所有工作表名稱。

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
```


### 返回值

工作表名稱的清單
## 備註



範例： 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## 相關參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IList](../../../system.collections.generic/ilist/)
* 類別 [String](../../../system/string/)
* 類別 [ExcelDataWorkbook](../)
* 命名空間 [Aspose::Slides::Excel](../../)
* 程式庫 [Aspose.Slides](../../../)