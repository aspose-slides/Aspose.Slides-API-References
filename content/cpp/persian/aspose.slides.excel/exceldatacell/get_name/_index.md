---
title: get_Name()
second_title: Aspose.Slides برای C++ مرجع API
description: نام سلول داده‌ای نمودار را برمی‌گرداند.
type: docs
weight: 14
url: /fa/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() متد

نام سلول داده‌ای نمودار را برمی‌گرداند.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
```

## توضیحات

مثال:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```

## مراجع

* کلاس [String](../../../system/string/)
* کلاس [ExcelDataCell](../)
* فضای‌نام [Aspose::Slides::Excel](../../)
* کتابخانه [Aspose.Slides](../../../)