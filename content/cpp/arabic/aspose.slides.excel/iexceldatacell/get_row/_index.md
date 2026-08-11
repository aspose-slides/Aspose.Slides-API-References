---
title: get_Row()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على الفهرس الصفري للصف في ورقة العمل التي توجد فيها الخلية. للقراءة فقط int32_t.
type: docs
weight: 27
url: /ar/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() طريقة


يُعيد الفهرس الصفري للصف في ورقة العمل حيث تقع الخلية. للقراءة فقط **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## انظر أيضًا

* فئة [IExcelDataCell](../)
* نطاق [Aspose::Slides::Excel](../../)
* مكتبة [Aspose.Slides](../../../)