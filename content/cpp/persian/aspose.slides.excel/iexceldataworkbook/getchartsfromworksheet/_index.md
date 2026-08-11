---
title: GetChartsFromWorksheet()
second_title: مرجع API Aspose.Slides برای C++
description: یک دیکشنری شامل ایندکس‌ها و نام‌های تمام نمودارها در worksheet مشخص‌شده از یک Excel workbook بازیابی می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) method

یک دیکشنری شامل ایندکس‌ها و نام‌های تمام نمودارها در worksheet مشخص‌شده از یک [Excel](../../) بازیابی می‌کند.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | نام worksheet برای جستجوی نمودارها. |

### مقدار بازگشت

یک دیکشنری که کلید آن ایندکس نمودار و مقدار آن نام نمودار است.

## نکات



مثال:
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IDictionary](../../../system.collections.generic/idictionary/)
* کلاس [String](../../../system/string/)
* کلاس [IExcelDataWorkbook](../)
* فضای نام [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)