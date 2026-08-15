---
title: get_Column()
second_title: Aspose.Slides for C++ API 參考
description: 取得儲存格所在工作表中欄位的零基索引。唯讀 int32_t.
type: docs
weight: 40
url: /zh-hant/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() 方法

取得儲存格所在工作表中欄位的零基索引。唯讀 **int32_t**。

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## 備註

範例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## 參閱

* 類別 [IExcelDataCell](../)
* 命名空間 [Aspose::Slides::Excel](../../)
* 程式庫 [Aspose.Slides](../../../)