---
title: InsertConnector()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक नया कनेक्टर शेप बनाता है और इसे निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है, डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है।
type: docs
weight: 391
url: /hi/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) मेथड

एक नया कनेक्टर शेप बनाता है और इसे निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है, डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है।

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | कनेक्टर शेप को सम्मिलित करने हेतु शून्य-आधारित इंडेक्स। |
| shapeType | [ShapeType](../../shapetype/) | इन्सर्ट करने के लिए कनेक्टर शेप का [ShapeType](../../shapetype/)। |
| x | **float** | कनेक्टर के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | कनेक्टर के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | कनेक्टर के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | कनेक्टर के फ्रेम की ऊँचाई, पॉइंट्स में। |

### Return Value

नया निर्मित [IConnector](../../iconnector/)।

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) मेथड

एक नया कनेक्टर शेप बनाता है और इसे निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है।

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | कनेक्टर शेप को सम्मिलित करने हेतु शून्य-आधारित इंडेक्स। |
| shapeType | [ShapeType](../../shapetype/) | इन्सर्ट करने के लिए कनेक्टर शेप का [ShapeType](../../shapetype/)। |
| x | **float** | कनेक्टर के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | कनेक्टर के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | कनेक्टर के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | कनेक्टर के फ्रेम की ऊँचाई, पॉइंट्स में। |
| createFromTemplate | **bool** | डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करने के लिए true (खाली नहीं नाम, साधारण शैली); कनेक्टर को डिफ़ॉल्ट प्रॉपर्टी मानों के साथ बनाने के लिए false। |

### Return Value

नया निर्मित [IConnector](../../iconnector/)।

## देखें

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IConnector](../../iconnector/)
* क्लास [IShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)