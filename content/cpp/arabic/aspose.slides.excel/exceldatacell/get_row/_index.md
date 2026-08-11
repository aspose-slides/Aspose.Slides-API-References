---
title: get_Row()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على الفهرس الصفري للصف في ورقة العمل حيث توجد الخلية. للقراءة فقط int32_t.
type: docs
weight: 27
url: /ar/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() طريقة

يحصل على الفهرس الصفري للصف في ورقة العمل حيث تقع الخلية. للقراءة فقط **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## انظر أيضًا

* الصنف [ExcelDataCell](../)
* المجال [Aspose::Slides::Excel](../../)
* المكتبة [Aspose.Slides](../../../)