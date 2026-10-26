---
title: get_Value()
second_title: Aspose.Slides برای C++ مرجع API
description: "مقداری که در سلول Excel موجود است را بر می‌گرداند. فقط-خواندنی System::Object."
type: docs
weight: 1
url: /fa/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() متد

مقدار موجود در سلول [Excel](../../) را بر می‌گرداند. فقط-خواندنی [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## توضیحات

مثال:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [IExcelDataCell](../)
* فضای‌نام [Aspose::Slides::Excel](../../)
* کتابخانه [Aspose.Slides](../../../)