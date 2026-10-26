---
title: GetWorksheetNames()
second_title: Aspose.Slides برای C++ مرجع API
description: نام تمام ورق‌های موجود در کتاب کار Excel را بازیابی می‌کند.
type: docs
weight: 40
url: /fa/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() متد


نام تمام ورق‌های موجود در کتاب کار [Excel](../../) را بازیابی می‌کند.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```


### مقدار بازگشت

فهرستی از نام‌های ورق
## توضیحات



مثال: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IList](../../../system.collections.generic/ilist/)
* کلاس [String](../../../system/string/)
* کلاس [IExcelDataWorkbook](../)
* فضای‌نام [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)