---
title: get_Format()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: डेटा पॉइंट लेवल की फ़ॉर्मेटिंग प्रॉपर्टीज़ को दर्शाता है। पढ़ें IFormat.
type: docs
weight: 1
url: /hi/aspose.slides.charts/chartdatapointlevel/get_format/
---
## ChartDataPointLevel::get_Format() मेथड


डेटा पॉइंट लेवल की फ़ॉर्मेटिंग प्रॉपर्टीज़ को दर्शाता है। पढ़ें [IFormat](../../iformat/).

```cpp
System::SharedPtr<IFormat> Aspose::Slides::Charts::ChartDataPointLevel::get_Format() override
```

## टिप्पणियाँ



```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Treemap, 50.0f, 50.0f, 500.0f, 400.0f);
auto series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPointLevel = series->get_DataPoints()->idx_get(7)->get_DataPointLevels()->idx_get(2);
dataPointLevel->get_Format()->get_Fill()->set_FillType(FillType::Solid);
dataPointLevel->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(Color::get_Red());
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IFormat](../../iformat/)
* क्लास [ChartDataPointLevel](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)