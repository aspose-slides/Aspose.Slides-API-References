---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides for C++ API संदर्भ
description: Y दिशा के साथ श्रृंखला के ErrorBars का प्रतिनिधित्व करता है।
type: docs
weight: 235
url: /hi/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() विधि

Y दिशा वाले ErrorBars को श्रृंखला के साथ दर्शाता है।

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## टिप्पणी

Y दिशा वाले ErrorBars प्रकार area, bar, line, scatter और bubble की श्रृंखला के लिए उपलब्ध हैं। किसी भी अन्य प्रकार के चार्ट के लिए यह प्रॉपर्टी null लौटाती है (जिसमें 3D चार्ट शामिल हैं)। कस्टम मानों के मामले में मान निर्दिष्ट करने के लिए DataPoints संग्रह का प्रयोग करें ([IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) प्रॉपर्टी के साथ)।

केवल-पढ़ने योग्य [IErrorBarsFormat](../../ierrorbarsformat/)।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IErrorBarsFormat](../../ierrorbarsformat/)
* क्लास [IChartSeries](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)