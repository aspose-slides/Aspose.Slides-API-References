---
title: get_Name()
second_title: Aspose.Slides لمرجع API لـ C++
description: "يحصل على اسم خلية بيانات المخطط. للقراءة فقط System::String."
type: docs
weight: 14
url: /ar/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() طريقة


يحصل على اسم خلية بيانات المخطط. للقراءة فقط [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## انظر أيضاً

* فئة [String](../../../system/string/)
* فئة [IExcelDataCell](../)
* مساحة اسم [Aspose::Slides::Excel](../../)
* مكتبة [Aspose.Slides](../../../)