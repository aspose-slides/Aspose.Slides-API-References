---
title: InsertChart()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया चार्ट बनाता है, इसे नमूना सीरीज़ डेटा और सेटिंग्स के साथ आरंभ करता है, और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।
type: docs
weight: 53
url: /hi/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) मेथड

एक नया चार्ट बनाता है, इसे नमूना सीरीज़ डेटा और सेटिंग्स के साथ आरंभ करता है, और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```

### परामितियाँ

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | बनाए जाने वाले चार्ट का प्रकार। |
| x | **float** | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए चार्ट की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए चार्ट की ऊँचाई, पॉइंट्स में। |
| index | **int32_t** | shape संग्रह में नए चार्ट को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |

### रिटर्न वैल्यू

नया निर्मित [Charts::IChart](../../../aspose.slides.charts/ichart/)।

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) मेथड

एक नया चार्ट बनाता है, इसे नमूना सीरीज़ डेटा और सेटिंग्स के साथ आरंभ करता है, और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```

### परामितियाँ

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | बनाए जाने वाले चार्ट का प्रकार। |
| x | **float** | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए चार्ट की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए चार्ट की ऊँचाई, पॉइंट्स में। |
| index | **int32_t** | shape संग्रह में नए चार्ट को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| initWithSample | **bool** | True यदि नए चार्ट को नमूना सीरीज़ डेटा और सेटिंग्स के साथ आरंभ करना है; false यदि चार्ट को बिना सीरीज़ के और केवल न्यूनतम सेटिंग्स के साथ बनाना है, जिससे निर्माण तेज़ हो जाता है। |

### रिटर्न वैल्यू

नया निर्मित [Charts::IChart](../../../aspose.slides.charts/ichart/)।

## देखें

* एन्यूम [ChartType](../../../aspose.slides.charts/charttype/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IChart](../../../aspose.slides.charts/ichart/)
* क्लास [IShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)