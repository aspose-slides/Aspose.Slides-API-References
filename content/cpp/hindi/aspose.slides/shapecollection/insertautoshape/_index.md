---
title: InsertAutoShape()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया ऑटो शेप बनाता है और निर्दिष्ट सूचकांक पर शेप संग्रह में इसे सम्मिलित करता है, डिफ़ॉल्ट टेम्पलेट फ़ॉर्मेटिंग लागू करता है।
type: docs
weight: 378
url: /hi/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) विधि


एक नया ऑटो शेप बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है, डिफ़ॉल्ट टेम्पलेट फ़ॉर्मेटिंग लागू करता है।

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | वह शून्य-आधारित सूचकांक जहाँ नया ऑटो शेप सम्मिलित किया जाता है। |
| shapeType | [ShapeType](../../shapetype/) | इन्सर्ट किए जाने वाले ऑटो शेप का [ShapeType](../../shapetype/)। |
| x | **float** | शेप के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | शेप के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | शेप के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | शेप के फ्रेम की ऊँचाई, पॉइंट्स में। |

### रिटर्न मान

नया बनाया गया [IAutoShape](../../iautoshape/)।

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) विधि


एक नया ऑटो शेप बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है, वैकल्पिक रूप से इसे डिफ़ॉल्ट टेम्पलेट स्टाइलिंग के साथ प्रारंभ करता है।

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | वह शून्य-आधारित सूचकांक जहाँ ऑटो शेप सम्मिलित किया जाता है। |
| shapeType | [ShapeType](../../shapetype/) | इन्सर्ट किए जाने वाले ऑटो शेप का [ShapeType](../../shapetype/)। |
| x | **float** | शेप के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | शेप के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | शेप के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | शेप के फ्रेम की ऊँचाई, पॉइंट्स में। |
| createFromTemplate | **bool** | डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करने के लिए True (जिसमें एक गैर-खाली नाम, सरल शैली, और केंद्रित टेक्स्ट शामिल है); सभी प्रॉपर्टीज़ डिफ़ॉल्ट मानों पर सेट करके शेप बनाने के लिए false। |

### रिटर्न मान

नया बनाया गया [IAutoShape](../../iautoshape/)।

## देखें

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)