---
title: AddConnector()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: डिफ़ॉल्ट टेम्पलेट शैली के साथ एक नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।
type: docs
weight: 378
url: /hi/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) विधि

डिफ़ॉल्ट टेम्पलेट शैली के साथ एक नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | जोड़ने हेतु कनेक्टर आकार का [ShapeType](../../shapetype/)। |
| x | **float** | कनेक्टर का फ्रेम का x-समन्वय, पॉइंट्स में। |
| y | **float** | कनेक्टर का फ्रेम का y-समन्वय, पॉइंट्स में। |
| width | **float** | कनेक्टर का फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | कनेक्टर का फ्रेम की ऊँचाई, पॉइंट्स में। |

### वापसी मान

नया निर्मित [IConnector](../../iconnector/)।

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) विधि

एक नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट शैली लागू करता है।

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | बनाने हेतु कनेक्टर आकार का [ShapeType](../../shapetype/)। |
| x | **float** | कनेक्टर का फ्रेम का x-समन्वय, पॉइंट्स में। |
| y | **float** | कनेक्टर का फ्रेम का y-समन्वय, पॉइंट्स में। |
| width | **float** | कनेक्टर का फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | कनेक्टर का फ्रेम की ऊँचाई, पॉइंट्स में। |
| createFromTemplate | **bool** | डिफ़ॉल्ट टेम्पलेट शैली (खाली नहीं नाम, सरल शैली) लागू करने के लिए true; कनेक्टर को डिफ़ॉल्ट गुण मानों के साथ बनाने के लिए false। |

### वापसी मान

नया निर्मित [IConnector](../../iconnector/)।

## संबंधित देखें

* एन्युम [ShapeType](../../shapetype/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IConnector](../../iconnector/)
* क्लास [IShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)