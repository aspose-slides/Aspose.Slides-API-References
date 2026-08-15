---
title: GetWorksheetNames()
second_title: Aspose.Slides for C++ API 參考
description: 檢索 Excel 工作簿中所有工作表的名稱。
type: docs
weight: 40
url: /zh-hant/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() 方法

檢索 [Excel](../../) 工作簿中所有工作表的名稱。

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
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

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IList](../../../system.collections.generic/ilist/)
* 類別 [String](../../../system/string/)
* 類別 [IExcelDataWorkbook](../)
* 命名空間 [Aspose::Slides::Excel](../../)
* 程式庫 [Aspose.Slides](../../../)