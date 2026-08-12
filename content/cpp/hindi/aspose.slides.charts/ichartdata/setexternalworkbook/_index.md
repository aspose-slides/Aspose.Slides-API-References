---
title: SetExternalWorkbook()
second_title: Aspose.Slides for C++ API संदर्भ
description: चार्ट के लिए डेटा स्रोत के रूप में बाहरी कार्यपुस्तिका सेट करता है। चार्ट डेटा लक्ष्य कार्यपुस्तिका से अपडेट किया जाएगा।
type: docs
weight: 196
url: /hi/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) विधि

चार्ट के लिए डेटा स्रोत के रूप में बाहरी कार्यपुस्तिका सेट करता है। [Chart](../../chart/) डेटा लक्ष्य कार्यपुस्तिका से अपडेट किया जाएगा।

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | लक्ष्य कार्यपुस्तिका का पाथ |
## टिप्पणी

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## IChartData::SetExternalWorkbook(System::String, bool) विधि

चार्ट के लिए डेटा स्रोत के रूप में बाहरी कार्यपुस्तिका सेट करता है।

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | लक्ष्य कार्यपुस्तिका का पाथ |
| updateChartData | **bool** | यदि मान false है तो केवल कार्यपुस्तिका पाथ अपडेट होगा। [Chart](../../chart/) डेटा लक्ष्य कार्यपुस्तिका से लोड नहीं होगा और अपडेट नहीं होगा। इसे तब उपयोग किया जा सकता है जब लक्ष्य कार्यपुस्तिका मौजूद न हो या उपलब्ध न हो। यदि मान true है तो चार्ट डेटा लक्ष्य कार्यपुस्तिका से अपडेट होगा। |
## टिप्पणी

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## सम्बंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [IChartData](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)