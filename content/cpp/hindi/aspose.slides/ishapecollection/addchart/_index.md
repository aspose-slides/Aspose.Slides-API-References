---
title: AddChart()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे आकार संग्रह के अंत में जोड़ता है।
type: docs
weight: 27
url: /hi/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) method

एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे आकार संग्रह के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | जोड़ने के लिए चार्ट का प्रकार। |
| x | **float** | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | चार्ट की चौड़ाई, पॉइंट्स में। |
| height | **float** | चार्ट की ऊँचाई, पॉइंट्स में। |

### रिटर्न वैल्यू

नया निर्मित [Charts::IChart](../../../aspose.slides.charts/ichart/)।

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) method

एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे आकार संग्रह के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | जोड़ने के लिए चार्ट का प्रकार। |
| x | **float** | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | चार्ट की चौड़ाई, पॉइंट्स में। |
| height | **float** | चार्ट की ऊँचाई, पॉइंट्स में। |
| initWithSample | **bool** | सैंपल श्रृंखला डेटा और सेटिंग्स के साथ नया चार्ट प्रारंभ करने के लिए true; बिना श्रृंखला और केवल न्यूनतम सेटिंग्स के चार्ट बनाने के लिए false, जिससे निर्माण तेज़ होता है। |

### रिटर्न वैल्यू

नया निर्मित [Charts::IChart](../../../aspose.slides.charts/ichart/)।

## संबंधित देखें

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)