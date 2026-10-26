---
title: get_Row()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得位於工作表中儲存格所在列的零基索引。唯讀 int32_t.
type: docs
weight: 27
url: /zh-hant/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() 方法

取得位於工作表中儲存格所在列的零基索引。唯讀 **int32_t**。

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## 說明

範例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```

## 另見

* 類別 [IExcelDataCell](../)
* 命名空間 [Aspose::Slides::Excel](../../)
* 函式庫 [Aspose.Slides](../../../)