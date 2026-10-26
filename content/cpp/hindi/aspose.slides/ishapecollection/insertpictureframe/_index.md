---
title: InsertPictureFrame()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट छवि को सम्मिलित करता हुआ नया पिक्चर फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप कलेक्शन में सम्मिलित करता है।
type: docs
weight: 417
url: /hi/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) विधि

निर्दिष्ट छवि को सम्मिलित करता हुआ एक नया पिक्चर फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप कलेक्शन में सम्मिलित करता है।

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | पिक्चर फ्रेम को सम्मिलित करने हेतु शून्य-आधारित अनुक्रमांक। |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) में सम्मिलित शेप टाइप को निर्दिष्ट करता है, सभी प्रकार की लाइनों को छोड़कर:<br>[ShapeType::Line](../../shapetype/),<br>[ShapeType::StraightConnector1](../../shapetype/),<br>[ShapeType::BentConnector2](../../shapetype/),<br>[ShapeType::BentConnector3](../../shapetype/),<br>[ShapeType::BentConnector4](../../shapetype/),<br>[ShapeType::BentConnector5](../../shapetype/),<br>[ShapeType::CurvedConnector2](../../shapetype/),<br>[ShapeType::CurvedConnector3](../../shapetype/),<br>[ShapeType::CurvedConnector4](../../shapetype/),<br>[ShapeType::CurvedConnector5](../../shapetype/)। |
| x | **float** | पिक्चर फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | पिक्चर फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | पिक्चर फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | पिक्चर फ्रेम की ऊँचाई, पॉइंट्स में। |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | पिक्चर फ्रेम में प्रदर्शित करने के लिए [IPPImage](../../ippimage/)। |

### वापसी मान

नया बनाया गया [IPictureFrame](../../ipictureframe/)।

## सम्बंधित देखें

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IPictureFrame](../../ipictureframe/)
* क्लास [IPPImage](../../ippimage/)
* क्लास [IShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)