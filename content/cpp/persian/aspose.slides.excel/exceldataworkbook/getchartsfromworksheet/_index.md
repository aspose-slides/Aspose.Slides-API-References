---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides برای C++ مرجع API
description: یک دیکشنری شامل شاخص‌ها و نام‌های تمام نمودارها در ورق کاری مشخص شده یک کتاب کار Excel را برمی‌گرداند.
type: docs
weight: 40
url: /fa/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) متد


یک دیکشنری شامل شاخص‌ها و نام‌های تمام نمودارها در ورق کاری مشخص شده از یک دفتر کار [Excel](../../) برمی‌گرداند.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | نام ورق کاری که برای یافتن نمودارها جستجو می‌شود. |

### مقدار بازگشت

یک دیکشنری که در آن کلید، شاخص نمودار و مقدار، نام نمودار است.
## یادداشت



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
* کلاس [ExcelDataWorkbook](../)
* فضای‌نام [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)