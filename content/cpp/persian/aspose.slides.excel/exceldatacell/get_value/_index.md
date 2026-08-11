---
title: get_Value()
second_title: Aspose.Slides برای مرجع API C++
description: مقدار موجود در سلول Excel را دریافت می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() متد


مقدار موجود در سلول [Excel](../../) را دریافت می‌کند.

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## نکات


مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [ExcelDataCell](../)
* فضای نام [Aspose::Slides::Excel](../../)
* کتابخانه [Aspose.Slides](../../../)