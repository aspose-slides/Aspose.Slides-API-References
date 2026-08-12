---
title: AddPictureFrame()
second_title: Aspose.Slides के लिये C++ API संदर्भ
description: निर्दिष्ट इमेज वाला नया पिक्चर फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।
type: docs
weight: 443
url: /hi/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) method

निर्दिष्ट इमेज वाला नया पिक्चर फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) में मौजूद शेप टाइप को निर्दिष्ट करता है, सभी प्रकार की लाइनों को छोड़कर:

[ShapeType::Line](../../shapetype/),

[ShapeType::StraightConnector1](../../shapetype/),

[ShapeType::BentConnector2](../../shapetype/),

[ShapeType::BentConnector3](../../shapetype/),

[ShapeType::BentConnector4](../../shapetype/),

[ShapeType::BentConnector5](../../shapetype/),

[ShapeType::CurvedConnector2](../../shapetype/),

[ShapeType::CurvedConnector3](../../shapetype/),

[ShapeType::CurvedConnector4](../../shapetype/),

[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | पिक्चर फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | पिक्चर फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | पिक्चर फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | पिक्चर फ्रेम की ऊँचाई, पॉइंट्स में। |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | पिक्चर फ्रेम में दिखाने के लिए [IPPImage](../../ippimage/)। |

### Return Value

नया बनाया गया [IPictureFrame](../../ipictureframe/)।

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IPictureFrame](../../ipictureframe/)
* क्लास [IPPImage](../../ippimage/)
* क्लास [ShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)