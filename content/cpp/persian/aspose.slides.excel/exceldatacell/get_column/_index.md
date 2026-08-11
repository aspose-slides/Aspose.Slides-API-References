---
title: get_Column()
second_title: Aspose.Slides برای مرجع API C++
description: شاخص صفر-پایه ستون در کاربرگی که سلول در آن قرار دارد را بر می‌گرداند. فقط‌خواندنی int32_t.
type: docs
weight: 40
url: /fa/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() متد

شاخص صفر-پایه ستون در کاربرگ که سلول در آن قرار دارد را برمی‌گرداند. فقط‌خواندنی **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## توضیحات

مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## همچنین ببینید

* کلاس [ExcelDataCell](../)
* فضای نام [Aspose::Slides::Excel](../../)
* کتابخانه [Aspose.Slides](../../../)