---
title: get_Label()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: डेटा पॉइंट स्तर के डेटा लेबल को दर्शाता है। Treemap और Sunburst श्रृंखला प्रकारों के लिए लागू किया जाता है। केवल पढ़ने योग्य IDataLabel.
type: docs
weight: 14
url: /hi/aspose.slides.charts/ichartdatapointlevel/get_label/
---
## IChartDataPointLevel::get_Label() विधि


डेटा पॉइंट स्तर के डेटा लेबल को दर्शाता है। Treemap और Sunburst श्रृंखला प्रकारों के लिए लागू किया जाता है। केवल पढ़ने योग्य [IDataLabel](../../idatalabel/).

```cpp
virtual System::SharedPtr<IDataLabel> Aspose::Slides::Charts::IChartDataPointLevel::get_Label()=0
```

## टिप्पणी



```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Sunburst, 50.0f, 50.0f, 500.0f, 400.0f);
auto series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPointLevel = series->get_DataPoints()->idx_get(0)->get_DataPointLevels()->idx_get(1);

dataPointLevel->get_Label()->get_DataLabelFormat()->set_ShowCategoryName(false);
dataPointLevel->get_Label()->get_DataLabelFormat()->set_ShowValue(true);
dataPointLevel->get_Label()->get_DataLabelFormat()->set_ShowSeriesName(true);

dataPointLevel = series->get_DataPoints()->idx_get(12)->get_DataPointLevels()->idx_get(1);
dataPointLevel->get_Label()->get_TextFormat()->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Solid);
dataPointLevel->get_Label()->get_TextFormat()->get_PortionFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(Color::get_Red());
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IDataLabel](../../idatalabel/)
* क्लास [IChartDataPointLevel](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)