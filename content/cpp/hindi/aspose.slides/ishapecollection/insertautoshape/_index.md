---
title: InsertAutoShape()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया auto shape बनाता है और इसे निर्दिष्ट सूचकांक पर shape collection में सम्मिलित करता है, डिफ़ॉल्ट टेम्पलेट फ़ॉर्मेटिंग लागू करता है।
type: docs
weight: 339
url: /hi/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) विधि

एक नया auto shape बनाता है और इसे निर्दिष्ट सूचकांक पर shape collection में सम्मिलित करता है, डिफ़ॉल्ट टेम्पलेट फ़ॉर्मेटिंग लागू करता है।

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### आर्ग्यूमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | नए auto shape को सम्मिलित करने के लिए शून्य-आधारित सूचकांक। |
| shapeType | [ShapeType](../../shapetype/) | डालने के लिए auto shape का [ShapeType](../../shapetype/)। |
| x | **float** | shape के फ़्रेम का x-निर्देशांक, पॉइंट में। |
| y | **float** | shape के फ़्रेम का y-निर्देशांक, पॉइंट में। |
| width | **float** | shape के फ़्रेम की चौड़ाई, पॉइंट में। |
| height | **float** | shape के फ़्रेम की ऊँचाई, पॉइंट में। |

### वापसी मान

नया बनाया गया [IAutoShape](../../iautoshape/)।

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) विधि

एक नया auto shape बनाता है और इसे निर्दिष्ट सूचकांक पर shape collection में सम्मिलित करता है, वैकल्पिक रूप से इसे डिफ़ॉल्ट टेम्पलेट स्टाइलिंग के साथ आरम्भ करता है।

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### आर्ग्यूमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | auto shape को सम्मिलित करने के लिए शून्य-आधारित सूचकांक। |
| shapeType | [ShapeType](../../shapetype/) | डालने के लिए auto shape का [ShapeType](../../shapetype/)। |
| x | **float** | shape के फ़्रेम का x-निर्देशांक, पॉइंट में। |
| y | **float** | shape के फ़्रेम का y-निर्देशांक, पॉइंट में। |
| width | **float** | shape के फ़्रेम की चौड़ाई, पॉइंट में। |
| height | **float** | shape के फ़्रेम की ऊँचाई, पॉइंट में। |
| createFromTemplate | **bool** | डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करने के लिए True (जिसमें गैर-खाली नाम, सरल शैली, और केंद्रित पाठ शामिल है); सभी गुणों को उनके डिफ़ॉल्ट पर सेट करके shape बनाने के लिए false। |

### वापसी मान

नया बनाया गया [IAutoShape](../../iautoshape/)।

## देखें भी

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)