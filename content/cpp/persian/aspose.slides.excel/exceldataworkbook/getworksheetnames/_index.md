---
title: GetWorksheetNames()
second_title: مرجع API Aspose.Slides برای C++
description: نام‌های تمام برگه‌های کاری موجود در کتاب‌کار Excel را بازیابی می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() متد


نام‌های تمام صفحات کاری موجود در کتاب کار [Excel](../../) را بازیابی می‌کند.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
```


### مقدار بازگشت

یک فهرست از نام‌های صفحات کاری
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

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [String](../../../system/string/)
* Class [ExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)