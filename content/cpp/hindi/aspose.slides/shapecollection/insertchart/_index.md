---
title: InsertChart()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और निर्दिष्ट अनुक्रमणिका पर इसे शैलियों के संग्रह में सम्मिलित करता है।
type: docs
weight: 92
url: /hi/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) विधि


एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और निर्दिष्ट अनुक्रमणिका पर इसे शैलियों के संग्रह में सम्मिलित करता है।

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | बनाने के लिए चार्ट का प्रकार। |
| x | **float** | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए चार्ट की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए चार्ट की ऊँचाई, पॉइंट्स में। |
| index | **int32_t** | शेप कलेक्शन में नए चार्ट को सम्मिलित करने के लिए शून्य-आधारित अनुक्रमणिका। |

### रिटर्न वैल्यू

नया बनाया गया [Charts::IChart](../../../aspose.slides.charts/ichart/)।

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) विधि


एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और निर्दिष्ट अनुक्रमणिका पर इसे शैलियों के संग्रह में सम्मिलित करता है।

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | बनाने के लिए चार्ट का प्रकार। |
| x | **float** | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए चार्ट की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए चार्ट की ऊँचाई, पॉइंट्स में। |
| index | **int32_t** | शेप कलेक्शन में नए चार्ट को सम्मिलित करने के लिए शून्य-आधारित अनुक्रमणिका। |
| initWithSample | **bool** | True को नए चार्ट को नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारम्भ करने के लिये; false को श्रृंखला के बिना और केवल न्यूनतम सेटिंग्स के साथ चार्ट बनाने के लिये, जिससे निर्माण तेज़ होता है। |

### रिटर्न वैल्यू

नया बनाया गया [Charts::IChart](../../../aspose.slides.charts/ichart/)।

## देखें

* एनम [ChartType](../../../aspose.slides.charts/charttype/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IChart](../../../aspose.slides.charts/ichart/)
* क्लास [ShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)