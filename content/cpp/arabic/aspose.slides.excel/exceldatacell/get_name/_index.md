---
title: get_Name()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على اسم خلية بيانات المخطط.
type: docs
weight: 14
url: /ar/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() طريقة


يحصل على اسم خلية بيانات المخطط.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## راجع أيضًا

* فئة [String](../../../system/string/)
* فئة [ExcelDataCell](../)
* مساحة الاسم [Aspose::Slides::Excel](../../)
* مكتبة [Aspose.Slides](../../../)