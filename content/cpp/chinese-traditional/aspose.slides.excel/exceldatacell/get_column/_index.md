---
title: get_Column()
second_title: Aspose.Slides for C++ API 參考
description: 取得位於工作表中儲存格所在欄位的零基索引。唯讀 int32_t.
type: docs
weight: 40
url: /zh-hant/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() 方法


取得位於工作表中儲存格所在欄位的零基索引。唯讀 **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## 備註


範例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## 另請參閱

* 類別 [ExcelDataCell](../)
* 命名空間 [Aspose::Slides::Excel](../../)
* 函式庫 [Aspose.Slides](../../../)