---
title: get_Name()
second_title: Aspose.Slides برای C++ مرجع API
description: "نام سلول دادهٔ نمودار را می‌گیرد. فقط-خواندنی System::String."
type: docs
weight: 14
url: /fa/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() متد

نام سلول دادهٔ نمودار را می‌گیرد. فقط-خواندنی [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
```

## توضیحات

مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```

## همچنین ببینید

* کلاس [String](../../../system/string/)
* کلاس [IExcelDataCell](../)
* فضای‌نام [Aspose::Slides::Excel](../../)
* کتابخانه [Aspose.Slides](../../../)