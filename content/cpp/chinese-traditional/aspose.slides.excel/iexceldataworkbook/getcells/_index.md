---
title: GetCells()
second_title: Aspose.Slides for C++ API 參考文件
description: 從工作簿中檢索符合指定公式的單元格集合。
type: docs
weight: 1
url: /zh-hant/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) 方法


檢索工作簿中符合指定公式的單元格集合。

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | 用於識別目標單元格的公式或範圍表示式（例如 "Sheet1!A1:B3"）。 |
| skipHiddenCells | **bool** | 如果 **true**，則會從結果中排除隱藏的單元格（例如隱藏的列或欄）。 |

### 返回值

一個只讀的單元格清單，符合指定的公式。

## 備註



範例： 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## 另見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* 類別 [IExcelDataCell](../../iexceldatacell/)
* 類別 [String](../../../system/string/)
* 類別 [IExcelDataWorkbook](../)
* 命名空間 [Aspose::Slides::Excel](../../)
* 函式庫 [Aspose.Slides](../../../)