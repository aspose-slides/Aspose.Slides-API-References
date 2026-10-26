---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट कार्यपत्रक में सभी चार्ट के अनुक्रमणिका और नामों को सम्मिलित करने वाले शब्दकोश को प्राप्त करता है, जो एक Excel कार्यपुस्तिका में स्थित है।
type: docs
weight: 40
url: /hi/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) विधि

निर्दिष्ट कार्यपत्रक में सभी चार्ट के अनुक्रमणिका और नामों को सम्मिलित करने वाले शब्दकोश को प्राप्त करता है, जो एक [Excel](../../) कार्यपुस्तिका में स्थित है।

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | चार्ट खोजने के लिए कार्यपत्रक का नाम। |

### रिटर्न मान

एक शब्दकोश जहाँ कुंजी चार्ट का अनुक्रमणिका है और मान चार्ट का नाम है।

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

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IDictionary](../../../system.collections.generic/idictionary/)
* क्लास [String](../../../system/string/)
* क्लास [ExcelDataWorkbook](../)
* नामस्थान [Aspose::Slides::Excel](../../)
* लाइब्रेरी [Aspose.Slides](../../../)