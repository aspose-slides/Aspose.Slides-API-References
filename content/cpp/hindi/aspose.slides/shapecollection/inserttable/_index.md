---
title: InsertTable()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया तालिका बनाता है और निर्दिष्ट अनुक्रमांक पर इसे शेप कलेक्शन में सम्मिलित करता है।
type: docs
weight: 482
url: /hi/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) विधि

एक नया टेबल बनाता है और निर्दिष्ट इंडेक्स पर इसे शेप कलेक्शन में सम्मिलित करता है।

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | टेबल को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| x | **float** | टेबल का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | टेबल का y-निर्देशांक, पॉइंट्स में। |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | टेबल के कॉलम की चौड़ाइयों को दर्शाने वाला डबल्स का एरे, पॉइंट्स में। |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | टेबल की पंक्तियों की ऊँचाइयों को दर्शाने वाला डबल्स का एरे, पॉइंट्स में। |

### रिटर्न वैल्यू

नया बनाया गया [ITable](../../itable/)।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [ITable](../../itable/)
* क्लास [ShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)