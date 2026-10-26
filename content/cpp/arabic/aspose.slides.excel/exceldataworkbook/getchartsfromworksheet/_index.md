---
title: GetChartsFromWorksheet()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للـ C++
description: تسترجع قاموسًا يحتوي على الفهارس وأسماء جميع المخططات في ورقة العمل المحددة في مصنف Excel.
type: docs
weight: 40
url: /ar/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) method

تسترجع قاموسًا يحتوي على فهارس وأسماء جميع المخططات في ورقة العمل المحددة في مصنف [Excel](../../).

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | اسم ورقة العمل للبحث عن المخططات. |

### قيمة الإرجاع

قاموس حيث المفتاح هو فهرس المخطط والقيمة هي اسم المخطط.

## ملاحظات



مثال:
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IDictionary](../../../system.collections.generic/idictionary/)
* فئة [String](../../../system/string/)
* فئة [ExcelDataWorkbook](../)
* مساحة الاسم [Aspose::Slides::Excel](../../)
* مكتبة [Aspose.Slides](../../../)