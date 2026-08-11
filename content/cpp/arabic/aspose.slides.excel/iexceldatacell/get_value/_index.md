---
title: get_Value()
second_title: "Aspose.Slides لواجهة برمجة تطبيقات C++"
description: "يحصل على القيمة الموجودة في خلية Excel. للقراءة فقط System::Object."
type: docs
weight: 1
url: /ar/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() طريقة

يحصل على القيمة الموجودة في الخلية [Excel](../../). قراءة فقط [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
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
* فئة [IExcelDataCell](../)
* نطاق [Aspose::Slides::Excel](../../)
* مكتبة [Aspose.Slides](../../../)