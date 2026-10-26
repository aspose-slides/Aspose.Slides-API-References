---
title: get_Column()
second_title: Aspose.Slides برای C++ مرجع API
description: اندیس صفر مبنای ستون در برگه کاری که سلول در آن قرار دارد را برمی‌گرداند. فقط-خواندنی int32_t.
type: docs
weight: 40
url: /fa/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() متد


اندیس صفر مبنای ستون در برگه کاری که سلول در آن قرار دارد را برمی‌گرداند. فقط-خواندنی **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## همچنین ببینید

* کلاس [IExcelDataCell](../)
* فضای نام [Aspose::Slides::Excel](../../)
* کتابخانه [Aspose.Slides](../../../)