---
title: InsertTable()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया टेबल बनाता है और निर्दिष्ट अनुक्रमांक पर इसे आकार संग्रह में सम्मिलित करता है।
type: docs
weight: 443
url: /hi/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method

एक नया टेबल बनाता है और निर्दिष्ट अनुक्रमांक पर इसे आकार संग्रह में सम्मिलित करता है।

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | टेबल को सम्मिलित करने के लिए शून्य-आधारित अनुक्रमांक। |
| x | **float** | टेबल का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | टेबल का y-निर्देशांक, पॉइंट्स में। |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | टेबल के कॉलम की चौड़ाईयों को दर्शाने वाले डबल्स की एक एरे, पॉइंट्स में। |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | टेबल की पंक्तियों की ऊँचाइयों को दर्शाने वाले डबल्स की एक एरे, पॉइंट्स में। |

### रिटर्न वैल्यू

नए बनाए गए [ITable](../../itable/)।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [ITable](../../itable/)
* क्लास [IShapeCollection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)