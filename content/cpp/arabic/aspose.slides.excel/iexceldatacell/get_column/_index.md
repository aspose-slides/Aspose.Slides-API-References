---
title: get_Column()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على الفهرس الصفري للعمود في ورقة العمل حيث توجد الخلية. للقراءة فقط int32_t.
type: docs
weight: 40
url: /ar/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() طريقة

يحصل على الفهرس الصفري للعمود في ورقة العمل حيث تقع الخلية. قراءة فقط **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## انظر أيضًا

* الصنف [IExcelDataCell](../)
* النطاق [Aspose::Slides::Excel](../../)
* المكتبة [Aspose.Slides](../../../)