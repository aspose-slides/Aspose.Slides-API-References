---
title: InsertClone()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट आकार की एक प्रति बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है।
type: docs
weight: 508
url: /hi/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) method

निर्दिष्ट आकार की एक प्रति बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है।

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | क्लोन किए गए आकार को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) को क्लोन करने के लिए। |
| x | **float** | क्लोन किए गए आकार के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | क्लोन किए गए आकार के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | क्लोन किए गए आकार के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | क्लोन किए गए आकार के फ्रेम की ऊँचाई, पॉइंट्स में। |

### रिटर्न वैल्यू

नया बनाया गया [IShape](../../ishape/)।

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) method

निर्दिष्ट आकार की एक प्रति बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। नई आकृति *sourceShape* की चौड़ाई और ऊँचाई को बरकरार रखती है।

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | क्लोन किए गए आकार को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) को क्लोन करने के लिए। |
| x | **float** | क्लोन किए गए आकार के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | क्लोन किए गए आकार के फ्रेम का y-निर्देशांक, पॉइंट्स में। |

### रिटर्न वैल्यू

नया बनाया गया [IShape](../../ishape/)।

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) method

निर्दिष्ट आकार की एक प्रति बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। क्लोन की गई आकृति मूल की स्थिति और आकार को बरकरार रखती है।

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | क्लोन किए गए आकार को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) को क्लोन करने के लिए। |

### रिटर्न वैल्यू

नया बनाया गया [IShape](../../ishape/)।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IShape](../../ishape/)
* क्लास [IShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)