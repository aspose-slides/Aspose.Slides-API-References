---
title: GetCells()
second_title: مرجع API Aspose.Slides برای C++
description: مجموعه‌ای از سلول‌ها را از کاربرگی که با فرمول مشخص مطابقت دارند، بازیابی می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) متد

مجموعه‌ای از سلول‌ها را از کاربرگ که با فرمول مشخص مطابقت دارند بازیابی می‌کند.

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | یک فرمول یا عبارت بازه (مثلاً \"Sheet1!A1:B3\") که برای شناسایی سلول‌های هدف استفاده می‌شود. |
| skipHiddenCells | **bool** | اگر **true** باشد، سلول‌های مخفی (مثلاً در ردیف‌ها یا ستون‌های مخفی) از نتایج حذف خواهند شد. |

### مقدار بازگشتی

یک لیست فقط‌خواندنی از سلول‌هایی که با فرمول مشخص مطابقت دارند.

## توضیحات



مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* کلاس [IExcelDataCell](../../iexceldatacell/)
* کلاس [String](../../../system/string/)
* کلاس [ExcelDataWorkbook](../)
* فضای‌نام [Aspose::Slides::Excel](../../)
* کتابخانه [Aspose.Slides](../../../)