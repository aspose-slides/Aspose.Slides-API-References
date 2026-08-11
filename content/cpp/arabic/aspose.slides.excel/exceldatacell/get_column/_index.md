---
title: get_Column()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على الفهرس الصفري للعمود في ورقة العمل حيث توجد الخلية. قراءة فقط int32_t.
type: docs
weight: 40
url: /ar/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() طريقة

يحصل على الفهرس الصفري للعمود في ورقة العمل حيث تقع الخلية. قراءة فقط **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## انظر أيضًا

* الفئة [ExcelDataCell](../)
* مساحة الاسم [Aspose::Slides::Excel](../../)
* المكتبة [Aspose.Slides](../../../)