---
title: InsertConnector()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया कनेक्टर आकृति बनाता है और निर्दिष्ट अनुक्रमणिका पर उसे आकृति संग्रह में सम्मिलित करता है, डिफ़ॉल्ट टेम्पलेट शैली लागू करते हुए।
type: docs
weight: 430
url: /hi/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) विधि

एक नया कनेक्टर शैप बनाता है और उसे निर्दिष्ट सूचकांक पर शैप कलेक्शन में सम्मिलित करता है, डिफॉल्ट टेम्पलेट स्टाइलिंग लागू करता है।

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | कनेक्टर शैप को सम्मिलित करने के लिए शून्य-आधारित सूचकांक। |
| shapeType | [ShapeType](../../shapetype/) | इंसेर्ट किए जाने वाले कनेक्टर शैप का [ShapeType](../../shapetype/)। |
| x | **float** | कनेक्टर के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | कनेक्टर के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | कनेक्टर के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | कनेक्टर के फ्रेम की ऊँचाई, पॉइंट्स में। |

### रिटर्न मान

नया बनाया गया [IConnector](../../iconnector/)।

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) विधि

एक नया कनेक्टर शैप बनाता है और उसे निर्दिष्ट सूचकांक पर शैप कलेक्शन में सम्मिलित करता है, वैकल्पिक रूप से डिफॉल्ट टेम्पलेट स्टाइलिंग लागू करता है।

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | कनेक्टर शैप को सम्मिलित करने के लिए शून्य-आधारित सूचकांक। |
| shapeType | [ShapeType](../../shapetype/) | इंसेर्ट किए जाने वाले कनेक्टर शैप का [ShapeType](../../shapetype/)। |
| x | **float** | कनेक्टर के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | कनेक्टर के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | कनेक्टर के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | कनेक्टर के फ्रेम की ऊँचाई, पॉइंट्स में। |
| createFromTemplate | **bool** | डिफॉल्ट टेम्पलेट स्टाइलिंग लागू करने के लिए true (अनखाली नाम, सरल शैली); कनेक्टर को डिफॉल्ट प्रॉपर्टी मानों के साथ बनाने के लिए false। |

### रिटर्न मान

नया बनाया गया [IConnector](../../iconnector/)।

## संबंधित देखें

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IConnector](../../iconnector/)
* क्लास [ShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)