---
title: InsertClone()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: निर्दिष्ट आकार की एक प्रतिलिपि बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर आकार संग्रह में सम्मिलित करता है।
type: docs
weight: 560
url: /hi/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) विधि

निर्दिष्ट आकार की एक प्रतिलिपि बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर आकार संग्रह में सम्मिलित करता है।

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | शून्य-आधारित अनुक्रमणिका जहाँ क्लोन किए गए आकार को सम्मिलित किया जाता है। |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | क्लोन करने के लिए [IShape](../../ishape/)। |
| x | **float** | क्लोन किए गए आकार की फ्रेम के x-निर्देशांक, पॉइंट में। |
| y | **float** | क्लोन किए गए आकार की फ्रेम के y-निर्देशांक, पॉइंट में। |
| width | **float** | क्लोन किए गए आकार की फ्रेम की चौड़ाई, पॉइंट में। |
| height | **float** | क्लोन किए गए आकार की फ्रेम की ऊँचाई, पॉइंट में। |

### Return Value

नया बनाया गया [IShape](../../ishape/)।

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) विधि

निर्दिष्ट आकार की एक प्रतिलिपि बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर आकार संग्रह में सम्मिलित करता है। नया आकार *sourceShape* की चौड़ाई और ऊँचाई को बरकरार रखता है।

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | शून्य-आधारित अनुक्रमणिका जहाँ क्लोन किए गए आकार को सम्मिलित किया जाता है। |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | क्लोन करने के लिए [IShape](../../ishape/)। |
| x | **float** | क्लोन किए गए आकार की फ्रेम के x-निर्देशांक, पॉइंट में। |
| y | **float** | क्लोन किए गए आकार की फ्रेम के y-निर्देशांक, पॉइंट में। |

### Return Value

नया बनाया गया [IShape](../../ishape/)।

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) विधि

निर्दिष्ट आकार की एक प्रतिलिपि बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर आकार संग्रह में सम्मिलित करता है। क्लोन किया गया आकार मूल के स्थान और आकार को बरकरार रखता है।

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### Arguments

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| index | **int32_t** | शून्य-आधारित अनुक्रमणिका जहाँ क्लोन किए गए आकार को सम्मिलित किया जाता है। |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | क्लोन करने के लिए [IShape](../../ishape/)। |

### Return Value

नया बनाया गया [IShape](../../ishape/)।

## संदर्भ

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IShape](../../ishape/)
* क्लास [ShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)