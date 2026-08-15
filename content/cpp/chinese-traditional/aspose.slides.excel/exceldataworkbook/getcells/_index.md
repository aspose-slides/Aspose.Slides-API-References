---
title: GetCells()
second_title: Aspose.Slides for C++ API 參考
description: 擷取與指定公式相符的工作簿儲存格集合。
type: docs
weight: 14
url: /zh-hant/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) 方法

擷取與指定公式相符的工作簿儲存格集合。

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | 用於識別目標儲存格的公式或範圍表達式 (e.g., \"Sheet1!A1:B3\")。 |
| skipHiddenCells | **bool** | 如果 **true**，隱藏的儲存格（例如隱藏的列或欄）將從結果中排除。 |

### 返回值

返回符合指定公式的唯讀儲存格清單。

## 備註



範例： 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* 類別 [IExcelDataCell](../../iexceldatacell/)
* 類別 [String](../../../system/string/)
* 類別 [ExcelDataWorkbook](../)
* 命名空間 [Aspose::Slides::Excel](../../)
* 函式庫 [Aspose.Slides](../../../)