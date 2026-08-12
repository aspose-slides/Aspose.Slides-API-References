---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides for C++ API संदर्भ
description: "यदि संग्रह में पहले से ही दिए गए इंडेक्स वाले डेटा पॉइंट मौजूद है, तो वह डेटा पॉइंट लौटाता है। यदि संग्रह में इंडेक्स index == N वाला डेटा पॉइंट नहीं है (जब इस संग्रह में डेटा पॉइंट्स की संख्या N से कम या बराबर हो), तो यह कमी वाले डेटा पॉइंट्स जोड़ता है और अंतिम (जिसका अनुरोधित इंडेक्स है) को लौटाता है। उदाहरण के तौर पर, संग्रह के इंडेक्स {0, 1, 2} हैं, और अनुरोधित इंडेक्स 5 है। तब मेथड कमी वाले डेटा पॉइंट्स जोड़ता है: {0, 1, 2, 3, 4, 5} और इंडेक्स 5 वाले डेटा पॉइंट को लौटाता है।"
type: docs
weight: 170
url: /hi/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) मेथड

यदि संग्रह में पहले से *index* इंडेक्स वाला डेटा पॉइंट मौजूद है तो वह डेटा पॉइंट वापस करता है। यदि संग्रह में *index* == N वाले डेटा पॉइंट नहीं है (जब इस संग्रह में डेटा पॉइंट्स की संख्या N से कम या बराबर हो) तो कम डेटा पॉइंट्स जोड़ता है और अंतिम (जो अनुरोधित इंडेक्स वाला है) को वापस करता है। उदाहरण के लिए, संग्रह के इंडेक्स {0, 1, 2} हैं, और अनुरोधित इंडेक्स 5 है। तब मेथड कम डेटा पॉइंट्स जोड़ता है: {0, 1, 2, 3, 4, 5} और इंडेक्स 5 वाले डेटा पॉइंट को लौटाता है।

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **uint32_t** | इंडेक्स। |

### रिटर्न वैल्यू

अनुरोधित इंडेक्स वाले डेटा पॉइंट को वापस करता है।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartDataPoint](../../ichartdatapoint/)
* क्लास [ChartDataPointCollection](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)