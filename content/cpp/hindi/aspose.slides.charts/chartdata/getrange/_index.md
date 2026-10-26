---
title: GetRange()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: चार्ट डेटा रेंज प्राप्त करता है।
type: docs
weight: 157
url: /hi/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() विधि


चार्ट डेटा रेंज प्राप्त करता है।

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### रिटर्न मान

सेल डेटा रेंज फ़ॉर्मूला। E.g: \"Sheet1!$A$1:$C$4\"
## टिप्पणियाँ




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [ChartData](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)