---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट worksheet में सभी चार्ट के सूचकांक और नाम वाले एक डिक्शनरी को प्राप्त करता है, जो एक Excel workbook का हिस्सा है।
type: docs
weight: 27
url: /hi/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) विधि

निर्दिष्ट worksheet में सभी चार्ट के सूचकांक और नाम वाले डिक्शनरी को प्राप्त करता है, जो एक [Excel](../../) workbook का हिस्सा होते हैं।

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | चार्ट्स को खोजने के लिए worksheet का नाम। |

### वापसी मान

एक डिक्शनरी जहाँ कुंजी chart index है और मान chart name है।

## टिप्पणी

उदाहरण: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [IExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)