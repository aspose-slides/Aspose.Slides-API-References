---
title: GetChartsFromWorksheet()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يسترجع قاموسًا يحتوي على الفهارس وأسماء جميع المخططات في ورقة العمل المحددة داخل دفتر عمل Excel.
type: docs
weight: 27
url: /ar/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) method


يسترجع قاموسًا يحتوي على الفهارس وأسماء جميع المخططات في ورقة العمل المحددة ضمن دفتر عمل [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | اسم ورقة العمل للبحث عن المخططات. |

### Return Value

قاموس حيث المفتاح هو فهرس المخطط والقيمة هي اسم المخطط.
## Remarks



مثال: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## See Also

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IDictionary](../../../system.collections.generic/idictionary/)
* فئة [String](../../../system/string/)
* فئة [IExcelDataWorkbook](../)
* مساحة الاسم [Aspose::Slides::Excel](../../)
* مكتبة [Aspose.Slides](../../../)