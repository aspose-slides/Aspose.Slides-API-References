---
title: AddAutoShape()
second_title: Aspose.Slides for C++ API संदर्भ
description: डिफ़ॉल्ट फ़ॉर्मेटिंग के साथ एक नया ऑटो शेप बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।
type: docs
weight: 313
url: /hi/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) method

डिफ़ॉल्ट फ़ॉर्मेटिंग के साथ एक नया ऑटो शेप बनाता है और उसे शेप कलेक्शन के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | जोड़ने के लिए ऑटो शेप का [ShapeType](../../shapetype/)। |
| x | **float** | शेप के फ्रेम का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | **float** | शेप के फ्रेम का y-कोऑर्डिनेट, पॉइंट्स में। |
| width | **float** | शेप के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | शेप के फ्रेम की ऊँचाई, पॉइंट्स में। |

### Return Value

नया बनाया गया [IAutoShape](../../iautoshape/)।

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) method

एक नया ऑटो शेप बनाता है और उसे शेप कलेक्शन के अंत में जोड़ता है, वैकल्पिक रूप से इसे डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग के साथ इनिशियलाइज़ करता है।

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | जोड़ने के लिए ऑटो शेप का [ShapeType](../../shapetype/)। |
| x | **float** | शेप के फ्रेम का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | **float** | शेप के फ्रेम का y-कोऑर्डिनेट, पॉइंट्स में। |
| width | **float** | शेप के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | शेप के फ्रेम की ऊँचाई, पॉइंट्स में। |
| createFromTemplate | **bool** | true होने पर नए शेप पर डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग (सरल शैली, केंद्रित टेक्स्ट, और खाली नहीं नाम) लागू करता है; false होने पर सभी प्रॉपर्टीज़ डिफ़ॉल्ट मानों के साथ शेप बनाता है। |

### Return Value

नया बनाया गया [IAutoShape](../../iautoshape/)।

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)