---
title: AddClone()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट आकार की एक प्रति बनाता है और उसे आकार संग्रह के अंत में जोड़ता है।
type: docs
weight: 495
url: /hi/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) विधि

निर्दिष्ट आकृति की एक प्रति बनाता है और उसे आकार संग्रह के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | क्लोन करने के लिए आकृति। |
| x | **float** | क्लोन की गई आकृति के फ्रेम का x-निर्देशांक, बिंदुओं में। |
| y | **float** | क्लोन की गई आकृति के फ्रेम का y-निर्देशांक, बिंदुओं में। |
| width | **float** | क्लोन की गई आकृति के फ्रेम की चौड़ाई, बिंदुओं में। |
| height | **float** | क्लोन की गई आकृति के फ्रेम की ऊँचाई, बिंदुओं में। |

### वापसी मान

नया बनाया गया [IShape](../../ishape/)।

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) विधि

निर्दिष्ट आकृति की एक प्रति बनाता है और उसे आकार संग्रह के अंत में जोड़ता है। नया आकार *sourceShape* की चौड़ाई और ऊँचाई को बरकरार रखता है।

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | क्लोन करने के लिए [IShape](../../ishape/)। |
| x | **float** | क्लोन की गई आकृति के फ्रेम का x-निर्देशांक, बिंदुओं में। |
| y | **float** | क्लोन की गई आकृति के फ्रेम का y-निर्देशांक, बिंदुओं में। |

### वापसी मान

नया बनाया गया [IShape](../../ishape/)।

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) विधि

निर्दिष्ट आकृति की एक प्रति बनाता है और उसे आकार संग्रह के अंत में जोड़ता है। क्लोन किया गया आकार मूल की स्थिति और आकार को बरकरार रखता है।

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | क्लोन करने के लिए [IShape](../../ishape/)। |

### वापसी मान

नया बनाया गया [IShape](../../ishape/)।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IShape](../../ishape/)
* क्लास [IShapeCollection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)