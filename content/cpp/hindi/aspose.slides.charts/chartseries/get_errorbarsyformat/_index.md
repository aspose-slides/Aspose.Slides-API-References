---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides for C++ API संदर्भ
description: Y दिशा के साथ श्रृंखला के ErrorBars को दर्शाता है।
type: docs
weight: 235
url: /hi/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() विधि

Y दिशा के साथ श्रृंखला के ErrorBars को दर्शाता है।

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## टिप्पणियाँ

Y दिशा वाले ErrorBars area, bar, line, scatter और bubble प्रकार की श्रृंखला के लिए उपलब्ध हैं। किसी अन्य प्रकार के चार्ट के लिए यह प्रॉपर्टी null लौटाती है (3D चार्ट सहित)। कस्टम मानों के मामलों में मान निर्दिष्ट करने के लिए DataPoints संग्रह का उपयोग करें ([IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) प्रॉपर्टी के साथ)।

केवल-पढ़ने योग्य [IErrorBarsFormat](../../ierrorbarsformat/).

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IErrorBarsFormat](../../ierrorbarsformat/)
* क्लास [ChartSeries](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)