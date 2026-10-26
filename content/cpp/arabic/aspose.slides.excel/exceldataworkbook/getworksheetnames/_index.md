---
title: GetWorksheetNames()
second_title: Aspose.Slides للغة C++ مرجع API
description: يقوم باسترجاع أسماء جميع أوراق العمل الموجودة في دفتر عمل Excel.
type: docs
weight: 53
url: /ar/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() طريقة

يسترجع أسماء جميع أوراق العمل الموجودة في دفتر العمل [Excel](../../).

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IList](../../../system.collections.generic/ilist/)
* فئة [String](../../../system/string/)
* فئة [ExcelDataWorkbook](../)
* نطاق [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)