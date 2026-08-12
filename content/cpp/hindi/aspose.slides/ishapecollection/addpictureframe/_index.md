---
title: AddPictureFrame()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट छवि को सम्मिलित करने वाला नया चित्र फ़्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।
type: docs
weight: 404
url: /hi/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) विधि

एक नया चित्र फ़्रेम बनाता है जिसमें निर्दिष्ट छवि होती है और इसे आकार संग्रह के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) में मौजूद आकार प्रकार को निर्दिष्ट करता है, सभी प्रकार की रेखाओं को छोड़कर:  

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
| x | **float** | चित्र फ़्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | चित्र फ़्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | चित्र फ़्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | चित्र फ़्रेम की ऊँचाई, पॉइंट्स में। |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | चित्र फ़्रेम में प्रदर्शित करने के लिए [IPPImage](../../ippimage/)। |

### रिटर्न मान

नया बनाया गया [IPictureFrame](../../ipictureframe/)।

## देखें

* एनम [ShapeType](../../shapetype/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IPictureFrame](../../ipictureframe/)
* क्लास [IPPImage](../../ippimage/)
* क्लास [IShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)