---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: X दिशा वाले श्रृंखला के ErrorBars को दर्शाता है।
type: docs
weight: 222
url: /hi/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() method

X दिशा वाली श्रृंखला के ErrorBars को दर्शाता है।

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## टिप्पणियाँ

ErrorBars X दिशा के साथ area, bar, scatter और bubble प्रकार की श्रृंखला के लिए उपलब्ध हैं। अन्य सभी प्रकार के चार्ट के लिए यह गुण null लौटाता है (3D चार्ट सहित)। कस्टम मानों के मामले में मान निर्दिष्ट करने के लिए DataPoints संग्रह का उपयोग करें ([IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) गुण के साथ)।

केवल-पढ़ने योग्य [IErrorBarsFormat](../../ierrorbarsformat/). 

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* वर्ग [IErrorBarsFormat](../../ierrorbarsformat/)
* वर्ग [ChartSeries](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)