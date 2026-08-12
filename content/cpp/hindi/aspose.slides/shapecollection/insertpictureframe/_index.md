---
title: InsertPictureFrame()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट छवि को सम्मिलित करते हुए एक नया चित्र फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर shape collection में डालता है।
type: docs
weight: 456
url: /hi/aspose.slides/shapecollection/insertpictureframe/
---
## ShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) विधि

निर्दिष्ट छवि को सम्मिलित करने वाला नया चित्र फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर shape collection में सम्मिलित करता है।

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | शून्य-आधारित अनुक्रमणिका जहाँ चित्र फ्रेम डालना है। |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) में शामिल shape type को निर्दिष्ट करता है, सभी प्रकार की रेखाओं को छोड़कर:  

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
| x | **float** | चित्र फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | चित्र फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | चित्र फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | चित्र फ्रेम की ऊँचाई, पॉइंट्स में। |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | चित्र फ्रेम में प्रदर्शित करने के लिए [IPPImage](../../ippimage/)। |

### वापसी मान

नया निर्मित [IPictureFrame](../../ipictureframe/)।

## देखें

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)