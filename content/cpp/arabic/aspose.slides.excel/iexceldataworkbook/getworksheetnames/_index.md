---
title: GetWorksheetNames()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يسترجع أسماء جميع أوراق العمل الموجودة في دفتر عمل Excel.
type: docs
weight: 40
url: /ar/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() طريقة


يقوم باسترجاع أسماء جميع أوراق العمل الموجودة في دفتر العمل [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```


### قيمة الإرجاع

قائمة بأسماء أوراق العمل
## ملاحظات



مثال: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IList](../../../system.collections.generic/ilist/)
* فئة [String](../../../system/string/)
* فئة [IExcelDataWorkbook](../)
* مساحة الاسم [Aspose::Slides::Excel](../../)
* مكتبة [Aspose.Slides](../../../)