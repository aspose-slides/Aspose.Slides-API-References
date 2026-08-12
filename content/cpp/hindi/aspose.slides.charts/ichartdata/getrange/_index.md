---
title: GetRange()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: चार्ट डेटा रेंज प्राप्त करता है।
type: docs
weight: 170
url: /hi/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() मेथड


चार्ट डेटा रेंज प्राप्त करता है।

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```


### वापसी मान

सेल्स डेटा रेंज फ़ॉर्मूला। उदाहरण: "Sheet1!$A$1:$C$4"
## टिप्पणियाँ




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [IChartData](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)