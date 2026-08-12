---
title: AddAutoShape()
second_title: Aspose.Slides for C++ API संदर्भ
description: डिफ़ॉल्ट फ़ॉर्मेटिंग के साथ एक नया ऑटो आकार बनाता है और उसे आकार संग्रह के अंत में जोड़ता है।
type: docs
weight: 352
url: /hi/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) मेथड


डिफ़ॉल्ट फ़ॉर्मेटिंग के साथ एक नया ऑटो आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | ऑटो शॉप को जोड़ने का [ShapeType](../../shapetype/) |
| x | **float** | आकार के फ्रेम का x-कोऑर्डिनेट, पॉइंट्स में |
| y | **float** | आकार के फ्रेम का y-कोऑर्डिनेट, पॉइंट्स में |
| width | **float** | आकार के फ्रेम की चौड़ाई, पॉइंट्स में |
| height | **float** | आकार के फ्रेम की ऊँचाई, पॉइंट्स में |

### रिटर्न वैल्यू

नया बनाया गया [IAutoShape](../../iautoshape/)।

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) मेथड


एक नया ऑटो आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से इसे डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग से प्रारम्भ करता है।

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | ऑटो शॉप को जोड़ने का [ShapeType](../../shapetype/) |
| x | **float** | आकार के फ्रेम का x-कोऑर्डिनेट, पॉइंट्स में |
| y | **float** | आकार के फ्रेम का y-कोऑर्डिनेट, पॉइंट्स में |
| width | **float** | आकार के फ्रेम की चौड़ाई, पॉइंट्स में |
| height | **float** | आकार के फ्रेम की ऊँचाई, पॉइंट्स में |
| createFromTemplate | **bool** | डिफ़ॉल्ट टेम्प्लेट स्टाइल (सादा स्टाइल, केंद्रित टेक्स्ट, और गैर-खाली नाम) लागू करने के लिए True; सभी गुणों को उनके डिफ़ॉल्ट मानों पर सेट करके आकार बनाने के लिए false |

### रिटर्न वैल्यू

नया बनाया गया [IAutoShape](../../iautoshape/)।

## देखें

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [ShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)