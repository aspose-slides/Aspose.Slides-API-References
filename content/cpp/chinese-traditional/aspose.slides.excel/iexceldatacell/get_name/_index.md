---
title: get_Name()
second_title: Aspose.Slides for C++ API 參考文件
description: "取得圖表資料儲存格的名稱。唯讀 System::String."
type: docs
weight: 14
url: /zh-hant/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() method


取得圖表資料儲存格的名稱。唯讀 [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
```

## 備註


範例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## 另見

* 類別 [String](../../../system/string/)
* 類別 [IExcelDataCell](../)
* 命名空間 [Aspose::Slides::Excel](../../)
* 函式庫 [Aspose.Slides](../../../)