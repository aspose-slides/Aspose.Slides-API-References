---
title: get_Value()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحصل على القيمة الموجودة في خلية Excel.
type: docs
weight: 1
url: /ar/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() طريقة

يحصل على القيمة الموجودة في الخلية [Excel](../../).

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [ExcelDataCell](../)
* مساحة الاسم [Aspose::Slides::Excel](../../)
* مكتبة [Aspose.Slides](../../../)