---
title: SetExternalWorkbook()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: बाहरी कार्यपुस्तिका को चार्ट के डेटा स्रोत के रूप में सेट करता है। चार्ट डेटा लक्ष्य कार्यपुस्तिका से अपडेट किया जाएगा।
type: docs
weight: 183
url: /hi/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) विधि

बाहरी कार्यपुस्तिका को चार्ट के डेटा स्रोत के रूप में सेट करता है। [Chart](../../chart/) डेटा लक्ष्य कार्यपुस्तिका से अपडेट किया जाएगा।

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | लक्ष्य कार्यपुस्तिका का पथ |

## Remarks

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) विधि

बाहरी कार्यपुस्तिका को चार्ट के डेटा स्रोत के रूप में सेट करता है।

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | लक्ष्य कार्यपुस्तिका का पथ |
| updateChartData | **bool** | यदि मान false है तो केवल कार्यपुस्तिका पथ अपडेट किया जाएगा। [Chart](../../chart/) डेटा लक्ष्य कार्यपुस्तिका से लोड और अपडेट नहीं किया जाएगा। इसे तब उपयोग किया जा सकता है जब लक्ष्य कार्यपुस्तिका मौजूद न हो या उपलब्ध न हो। यदि मान true है तो चार्ट डेटा लक्ष्य कार्यपुस्तिका से अपडेट होगा। |

## Remarks

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## See Also

* Class [String](../../../system/string/)
* Class [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)