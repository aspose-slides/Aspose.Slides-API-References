---
title: GetCells()
second_title: Aspose.Slides برای C++ API مرجع
description: یک مجموعه از cells را از workbook بر می‌گرداند که با formula مشخص شده مطابقت دارند.
type: docs
weight: 1
url: /fa/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) متد

مجموعه‌ای از cells را از workbook بر می‌گرداند که با formula مشخص شده مطابقت دارند.

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```

### پارامترها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | یک formula یا عبارت بازه (به عنوان مثال "Sheet1!A1:B3") که برای شناسایی cells هدف استفاده می‌شود. |
| skipHiddenCells | **bool** | اگر **true** باشد، cells مخفی (مثلاً در ردیف‌های مخفی یا ستون‌های مخفی) از نتیجه حذف می‌شوند. |

### مقدار بازگشت

یک فهرست read-only از cells که با formula مشخص شده مطابقت دارند.

## توضیحات



مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* کلاس [IExcelDataCell](../../iexceldatacell/)
* کلاس [String](../../../system/string/)
* کلاس [IExcelDataWorkbook](../)
* فضای‌نام [Aspose::Slides::Excel](../../)
* کتابخانه [Aspose.Slides](../../../)